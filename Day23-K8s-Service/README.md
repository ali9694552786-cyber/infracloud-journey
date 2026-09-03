# Day 23 - Service Exposed via NodePort

- Service Type: NodePort
- Port: 80:31324
- Endpoints: 3 pods (10.244.0.7, .8, .9)
- Test: curl localhost:8080 -> Welcome to nginx!
- Fix: Used port-forward because Docker driver needs terminal open

Live Service Success!
