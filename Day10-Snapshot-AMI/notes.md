# Day 10 - Snapshot and AMI

## Snapshot
- Backup of EBS Volume
- Stored in S3 automatically by AWS
- Incremental backup (pehle full, fir sirf changes)
- Use: Data backup

## AMI (Amazon Machine Image)
- Backup of full EC2 instance
- Includes OS, software, config
- Use: To launch new EC2 quickly
- AMI = Snapshot + Metadata

## Hands-on Lab (AWS Console):
1. EC2 > Volumes > Select Volume > Actions > Create Snapshot
2. EC2 > Instances > Select Instance > Actions > Image > Create Image (AMI)

## Real World Use:
Company ka 1 server ka AMI bana lo, fir usse 10 same server bana sakte ho.

## Commands for Local Backup (if no AWS):
tar -czvf backup-day10.tar.gz ~/infracloud-day1
