# Homework 5 Security

This repository contains the Python application used in Part B of the assignment.

## Part B
The application uses boto3 to access Amazon S3 from an Amazon EC2 instance using an IAM role with read-only access.

## Files
- `app.py` - Python script that lists S3 buckets using IAM role-based authentication

## Notes
No AWS access keys are hardcoded in the application. Temporary credentials are retrieved automatically through the EC2 Instance Metadata Service (IMDSv2).
