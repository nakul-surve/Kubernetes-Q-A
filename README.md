🔹 1. What is Kubernetes?

Answer:
Kubernetes is an open-source container orchestration platform that automates deployment, scaling, and management of containerized applications.

🔹 2. What is a Pod?

Answer:
A Pod is the smallest deployable unit in Kubernetes. It can contain one or more containers that share the same network and storage.

🔹 3. What is the difference between Pod and Container?

Answer:

A container runs an application
A Pod wraps one or more containers and manages networking & storage

🔹 4. What is a Node?

Answer:
A Node is a worker machine (VM or physical server) where Kubernetes runs containers.

🔹 5. What is a Cluster?

Answer:
A Cluster is a group of nodes managed by Kubernetes.

🔹 6. What is Deployment?

Answer:
A Deployment is used to manage and maintain a desired number of Pods, allowing updates, rollbacks, and scaling.

🔹 7. What is ReplicaSet?

Answer:
ReplicaSet ensures that a specified number of Pod replicas are running at all times.

🔹 8. What is Service in Kubernetes?

Answer:
A Service exposes Pods to network traffic and provides a stable IP and DNS name.


🔹 9. Types of Kubernetes Services?
Answer:
ClusterIP (default)
NodePort
LoadBalancer
ExternalName

🔹 10. What is ConfigMap?

Answer:
ConfigMap stores non-sensitive configuration data as key-value pairs.

🔹 11. What is Secret?

Answer:
A Secret stores sensitive data like passwords, tokens, and API keys.

🔹 12. What is Namespace?

Answer:
Namespace is used to logically separate resources within a cluster.

🔹 13. What is Ingress?

Answer:
Ingress manages external HTTP/HTTPS access to services inside the cluster.

🔹 14. What is Horizontal Pod Autoscaler (HPA)?

Answer:
HPA automatically scales Pods based on CPU/memory usage.

🔹 15. What is Rolling Update?

Answer:
Rolling update gradually replaces old Pods with new ones without downtime.

🔹 16. What is DaemonSet?

Answer:
DaemonSet ensures a Pod runs on all (or selected) nodes.

🔹 17. What is StatefulSet?

Answer:
StatefulSet is used for stateful applications like databases with stable identity and storage.

🔹 18. What is Persistent Volume (PV)?

Answer:
PV is a piece of storage in the cluster.

🔹 19. What is Persistent Volume Claim (PVC)?

Answer:
PVC is a request for storage by a user.

🔹 20. What is kube-apiserver?

Answer:
It is the main control plane component that exposes Kubernetes API.
