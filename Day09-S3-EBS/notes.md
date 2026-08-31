# Day 9 - EBS and S3

## What is EBS?
- Elastic Block Store
- Attached to EC2
- Like C: drive
- Data persists after reboot
- Used for OS and applications

## What is S3?
- Simple Storage Service
- Object storage
- Like Google Drive
- 99.999999999% durable
- Used for backup, static website hosting

## Hands-on Today:
1. Created S3 bucket: infracloud-day9-ali
2. Uploaded Day 8 Nginx file to S3
3. Learned EBS snapshot concept

## Command Used:
aws s3 ls
aws s3 mb s3://infracloud-day9-ali
aws s3 cp index.html s3://infracloud-day9-ali/
