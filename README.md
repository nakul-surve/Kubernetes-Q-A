
# 🚀 Kubernetes Interview Q&A

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)
![DevOps](https://img.shields.io/badge/DevOps-Practice-blue)
![Status](https://img.shields.io/badge/Status-Active-success)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-orange)

A curated collection of **Kubernetes interview questions and answers** for beginners to advanced learners.  
Perfect for **DevOps, Cloud, and SRE interview preparation**.

---

## 📚 Table of Contents

- [Basics](#-basics)
- [Core Concepts](#-core-concepts)
- [Networking](#-networking)
- [Storage](#-storage)
- [Advanced Concepts](#-advanced-concepts)

---

# 🔹 Basics

### ❓ What is Kubernetes?
**Answer:**  
Kubernetes is an open-source container orchestration platform that automates deployment, scaling, and management of containerized applications.

---

### ❓ What is a Pod?
**Answer:**  
A Pod is the smallest deployable unit in Kubernetes. It can contain one or more containers that share the same network and storage.

---

### ❓ What is the difference between Pod and Container?
**Answer:**  
- A **container** runs an application  
- A **Pod** wraps one or more containers and manages networking & storage  

---

### ❓ What is a Node?
**Answer:**  
A Node is a worker machine (VM or physical server) where Kubernetes runs containers.

---

### ❓ What is a Cluster?
**Answer:**  
A Cluster is a group of nodes managed by Kubernetes.

---

# 🔹 Core Concepts

### ❓ What is Deployment?
**Answer:**  
A Deployment manages Pods and ensures the desired number of replicas are running. It supports scaling and rolling updates.

---

### ❓ What is ReplicaSet?
**Answer:**  
ReplicaSet ensures that a specified number of Pod replicas are running at all times.

---

### ❓ What is Namespace?
**Answer:**  
Namespace is used to logically separate resources within a cluster.

---

### ❓ What is ConfigMap?
**Answer:**  
ConfigMap stores non-sensitive configuration data as key-value pairs.

---

### ❓ What is Secret?
**Answer:**  
A Secret stores sensitive data like passwords, tokens, and API keys.

---

# 🌐 Networking

### ❓ What is a Service in Kubernetes?
**Answer:**  
A Service exposes Pods to network traffic and provides a stable IP and DNS name.

---

### ❓ Types of Kubernetes Services?
**Answer:**  
- ClusterIP (default)  
- NodePort  
- LoadBalancer  
- ExternalName  

---

### ❓ What is Ingress?
**Answer:**  
Ingress manages external HTTP/HTTPS access to services inside the cluster.

---

### ❓ What is kube-proxy?
**Answer:**  
kube-proxy handles networking and load balancing for services.

---

# 💾 Storage

### ❓ What is Persistent Volume (PV)?
**Answer:**  
PV is a piece of storage in the cluster.

---

### ❓ What is Persistent Volume Claim (PVC)?
**Answer:**  
PVC is a request for storage by a user.

---

# ⚡ Advanced Concepts

### ❓ What is Horizontal Pod Autoscaler (HPA)?
**Answer:**  
HPA automatically scales Pods based on CPU/memory usage.

---

### ❓ What is Rolling Update?
**Answer:**  
Rolling update gradually replaces old Pods with new ones without downtime.

---

### ❓ What is DaemonSet?
**Answer:**  
DaemonSet ensures a Pod runs on all (or selected) nodes.

---

### ❓ What is StatefulSet?
**Answer:**  
StatefulSet is used for stateful applications like databases with stable identity and storage.

---

### ❓ What is kube-apiserver?
**Answer:**  
The main control plane component that exposes the Kubernetes API.

---

### ❓ What is etcd?
**Answer:**  
etcd is a key-value store used to store cluster data.

---

### ❓ What is kubelet?
**Answer:**  
kubelet runs on each node and ensures containers are running in Pods.

---

### ❓ What is Helm?
**Answer:**  
Helm is a package manager for Kubernetes used to deploy applications via charts.

---

### ❓ What are Taints and Tolerations?
**Answer:**  
- **Taints:** Prevent Pods from being scheduled on nodes  
- **Tolerations:** Allow Pods to run on tainted nodes  

---

# 🚀 Future Improvements

- 🔹 Add real-world YAML examples  
- 🔹 Add architecture diagrams  
- 🔹 Add GitOps (ArgoCD) Q&A  
- 🔹 Add troubleshooting scenarios  

---

# 🤝 Contributing

Contributions are welcome!  
Feel free to fork this repo and submit a pull request.

---

# ⭐ Support

If this helped you, consider giving it a ⭐ on GitHub!

---
