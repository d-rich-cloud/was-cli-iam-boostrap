# was-cli-iam-boostrap

# aws-cloud-bootstrap

## Overview
This repository documents the secure initialization of an AWS learning environment, focusing on Identity and Access Management (IAM) and Command Line Interface (CLI) integration.

## Security Principles Applied
- **Least Privilege:** Created a dedicated `Dave-Admin` IAM user for daily operations.
- **Root Protection:** Root account secured with MFA and stored for emergency use only.
- **Credential Hygiene:** Documented the process of rotating Access Keys after accidental exposure (Security Incident Response).

## Implementation Steps
1. **AWS CLI v2 Installation:**
   ```bash
   curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
   unzip awscliv2.zip
   sudo ./aws/install
