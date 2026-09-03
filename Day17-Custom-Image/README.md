# Day 17 - Custom Docker Image

## Dockerfile Explained
- FROM - base image (nginx)
- COPY - apni file image me dalna
- EXPOSE - port batana
- CMD - container start hote hi kya chalna hai

## Commands Used
- docker build -t my-custom-website:v1 .
- docker run -d -p 8081:80 --name day17-website my-custom-website:v1
- curl localhost:8081

## Result
My own HTML is now running inside Docker!

