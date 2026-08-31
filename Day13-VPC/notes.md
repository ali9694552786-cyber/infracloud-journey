# Day 13 - VPC (Virtual Private Cloud)

## What is VPC?
- Your own private network in AWS cloud
- Isolated from other customers
- You control IP range, subnets, gateways

## Main Components:
1. VPC - 10.0.0.0/16 (65k IPs)
2. Public Subnet - 10.0.1.0/24 - For Web Servers, has Internet
3. Private Subnet - 10.0.2.0/24 - For Database, no Internet
4. Internet Gateway (IGW) - Connects VPC to Internet
5. Route Table - Tells traffic where to go
6. Security Group - Firewall

## Hands-on Plan:
1. Create VPC: 10.0.0.0/16
2. Create 2 Subnets in different AZs
3. Create IGW and attach to VPC
4. Update Route Table: 0.0.0.0/0 -> IGW
5. Launch EC2 in Public Subnet

## Interview Line:
"VPC me hum public aur private subnets banate hain security ke liye. Database ko private me rakhte hain."
