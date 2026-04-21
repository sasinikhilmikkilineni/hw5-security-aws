# Homework 5 Security

This repository contains the Python application used in Part B of the assignment.

## Part B
The application uses the AWS SDK (boto3) to access Amazon S3 from an EC2 instance.

## Key Concept
The EC2 instance uses an IAM role with read-only access to S3.  
No AWS credentials are stored in the code.  
Temporary credentials are automatically retrieved using the EC2 Instance Metadata Service (IMDSv2).

## File
- app.py – lists S3 buckets using IAM role authentication
