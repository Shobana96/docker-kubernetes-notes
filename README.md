Docker vs Kubernetes – Key Differences and Architecture.md

Docker – Container Platform

Docker is called a container platform because it enables application packaging into lightweight, portable containers that can run on a single host. However, it comes with some limitations:
	•	Docker runs on a single host, and if that host or any critical container goes down, the entire application could be affected.
	•	It does not support key enterprise-level features such as:
	•	Auto-scaling
	•	Auto-healing
	•	Load balancing
	•	API gateway integration
	•	Firewall management
Because of these limitations, Docker alone is generally not used in production environments, especially for large infrastructure needs.

♛️ Kubernetes – Container Orchestration Tool
Kubernetes is a container orchestration tool that addresses the shortcomings of Docker by ensuring application stability and scalability. For example:
	•	If a pod (a group of one or more containers) goes down, Kubernetes automatically brings up a replacement pod to keep the application running.
	•	It supports:
	•	Auto-scaling – to manage load dynamically.
	•	Auto-healing – to ensure availability and stability.
Kubernetes is typically installed as a cluster, which is a group of nodes that work together to run containerized applications.

Kubernetes Architecture

Why is it called K8s? Because there are 8 letters between ‘K’ and ‘s’ in the word "Kubernetes".

Kubernetes architecture is divided into two main parts:

1. Control Plane (Master Node) – Controls all actions
	•	API Server: Acts as the main entry point for all administrative tasks. It decides what information to process and exposes the Kubernetes API to the outside world.
	•	Scheduler: Works based on the information provided by the API server and schedules pods to appropriate worker nodes.
	•	ETCD: A distributed key-value store that stores all cluster-related information in key-value format.
	•	Controller Manager: Manages various controllers like:
	•	ReplicaSet
	•	Replication Controller
	•	Deployment Controller It also supports auto-scaling by ensuring the desired number of pods are running.

2. Data Plane (Worker Nodes) – Executes the actual workload
	•	Kubelet: An agent that ensures the containers (pods) are healthy and running as expected on each node.
	•	Kube-proxy: A network component that manages IP addresses, routing, and basic load balancing for services within the cluster.
	•	Container Runtime: Responsible for running the actual containers. Common runtimes include:
	•	CRI-O
	•	Containerd
	•	Others (e.g., Docker, though it's being deprecated in Kubernetes)



