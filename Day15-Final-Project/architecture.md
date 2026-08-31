# Day 15 - Final Architecture

1. Create VPC 10.0.0.0/16
2. 2 Public Subnets in ap-south-1a, ap-south-1b
3. Internet Gateway + Route Table
4. 2 EC2 with Nginx + User Data
5. Create AMI of EC2
6. S3 Bucket for logs backup
7. CloudWatch Alarm on CPU > 80%
8. IAM User with ReadOnly Access for intern
9. Application Load Balancer in front of 2 EC2s

This is Production Ready Setup for small company.
Cost: ~ $10-15/month with t2.micro
