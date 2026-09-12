# Day 25 - K8s Secrets & Env Variables

- Created Secret: my-secret with username & password
- Secret base64 encoded, not plain text
- Deployment env-demo uses secretKeyRef
- ENV: APP_USER, APP_PASSWORD from Secret
- ENV: ENVIRONMENT=production direct value
- Verified via kubectl exec -- env | grep APP
- Concept: Secure credential management in K8s
