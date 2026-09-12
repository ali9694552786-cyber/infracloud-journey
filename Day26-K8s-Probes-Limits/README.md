# Day 26 - K8s Probes & Resource Limits

- Deployment: healthy-app
- Resources: requests cpu 100m mem 128Mi, limits cpu 200m mem 256Mi
- LivenessProbe: httpGet / :80 delay 5s period 10s
- ReadinessProbe: httpGet / :80 delay 3s period 5s
- Verified via kubectl describe pod | grep Probe
- Concept: Self-healing and resource management
