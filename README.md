# AWS S3 Cross-Region Replication

This project contains CloudFormation templates to set up:

1. **Primary S3 bucket** in ca-central-1
2. **Destination S3 bucket** in us-east-1
3. Cross-region replication between the buckets using an IAM role

## Files

- `primary.yaml` – Primary bucket + replication config
- `destination.yaml` – Destination bucket config

