# Day 12 - IAM (Identity and Access Management)

## What is IAM?
- To manage users and their permissions
- Never use root account for daily work
- Free service by AWS

## Main Parts:
1. User - A person (e.g., developer1)
2. Group - Collection of users (e.g., Dev-Team)
3. Policy - Permission document (JSON)
4. Role - For AWS services to talk to each other

## Best Practices:
- Don't share root credentials
- Create individual IAM users
- Give least privilege (jitna chahiye utna hi do)
- Enable MFA for root

## Common Policies:
- AmazonS3ReadOnlyAccess
- AmazonEC2FullAccess
- AdministratorAccess

## Hands-on:
1. IAM > Users > Create User > ali-intern
2. Attach Policy > S3ReadOnly
3. Login with that user and try to delete EC2 (will fail)
