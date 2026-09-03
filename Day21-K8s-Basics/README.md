# Day 21 - Kubernetes Started
- kubectl installed
- minikube started with docker driver
- Fixed: segmentation fault by reinstalling minikube
- Commands:
  kubectl version --client
  minikube start --driver=docker
  kubectl get nodes
  kubectl run my-first-pod --image=nginx
  kubectl get pods
- Status: my-first-pod Running

