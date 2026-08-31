# Day 14 - Load Balancer & Auto Scaling

## What is Load Balancer?
- Distributes traffic to multiple EC2s
- No single point of failure
- Types: ALB (HTTP), NLB (TCP), CLB (Old)

## How it works?
User -> Load Balancer -> Target Group (EC2-1, EC2-2, EC2-3)
Health Checks every 30 sec

## Auto Scaling:
- Automatically increases/decreases EC2
- Example: CPU > 70% -> Add 1 more EC2
- Saves money

## Hands-on:
1. Create 2 EC2 in different AZs
2. Create Target Group
3. Create ALB and attach target group
4. Test ALB DNS

## Real World:
Flipkart sale me 100 se 1000 server Auto Scaling se bante hain.
