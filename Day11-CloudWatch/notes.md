# Day 11 - CloudWatch Monitoring

## What is CloudWatch?
- Monitoring service for AWS
- Collects Metrics (CPU, RAM, Disk)
- Creates Alarms
- Sends notification via SNS (Email/SMS)

## Important Metrics:
- CPUUtilization
- StatusCheckFailed
- NetworkIn / NetworkOut
- EBS Read/Write

## How Alarm Works?
Metric > Threshold > Alarm > SNS Topic > Email

Example: 
If CPU > 80% for 5 min -> Send Email to admin@company.com

## Hands-on (AWS Console):
1. CloudWatch > Alarms > Create Alarm
2. Select EC2 > CPUUtilization > Condition > Greater than 80%
3. Create SNS Topic > Add your email
4. Confirm email

## Interview Question:
Q: How to know if EC2 is down?
A: Use CloudWatch StatusCheckFailed alarm.
