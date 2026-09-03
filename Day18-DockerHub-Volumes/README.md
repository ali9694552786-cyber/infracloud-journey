# Day 18 - Docker Hub + Volumes

## Docker Hub
- Image: alidockerad/my-custom-website:v1
- Commands:
  docker login
  docker tag my-custom-website:v1 alidockerad/my-custom-website:v1
  docker push alidockerad/my-custom-website:v1

## Docker Volumes
- Volume is permanent storage
- Without volume, data deleted with container
- Commands:
  docker volume create my-data
  docker run -v my-data:/data nginx

## Verified
- Data persists even after container deletion

