# AWS IAM Security Configuration Project

## Project Overview
This project demonstrates hands-on experience with AWS Identity and Access Management (IAM).  
The goal is to configure IAM users, roles, groups, and security policies following AWS best practices.

## Services Used
- AWS IAM

## Features Implemented
- Created IAM users with least-privilege access
- Configured IAM groups and attached managed policies
- Created IAM roles for EC2 with S3 read-only permissions
- Enabled basic security settings like MFA and password policies

## IAM Setup Details

### IAM Users
- admin-user (Administrator access)
- developer-user (Read-only S3 access)

### IAM Groups
- Admins: AdministratorAccess
- Developers: AmazonS3ReadOnlyAccess

### IAM Role
- EC2-S3-ReadRole
- Allows EC2 instances to read data from S3

## Security Best Practices Followed
- Enabled MFA for admin user
- Used IAM roles instead of hardcoded credentials
- Applied least privilege principle

## Learning Outcome
- Gained practical knowledge of AWS IAM
- Understood access control and cloud security fundamentals
- Learned to manage users and roles securely

## Maintainer
Manju Bhargavi
