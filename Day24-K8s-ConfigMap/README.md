# Day 24 - ConfigMap Custom Website

- Created index.html with custom message
- ConfigMap: my-html from file
- Mounted ConfigMap to /usr/share/nginx/html
- Deployment: my-custom-web with 2 replicas
- Service: NodePort exposed
- Output: Hello Mehaboob - Day 24 Live!
- Concept: Decoupling config from image
