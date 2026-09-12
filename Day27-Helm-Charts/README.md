# Day 27 - Helm Package Manager

- Installed Helm v3
- Deployed bitnami/nginx via helm install my-nginx bitnami/nginx
- Created custom chart: helm create my-first-chart
- Managed releases: helm list, helm status, helm uninstall
- Concept: Templating + Package management for K8s

Commands:
helm repo add bitnami https://charts.bitnami.com/bitnami
helm install my-nginx bitnami/nginx
helm create my-first-chart
