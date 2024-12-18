# AWS IAM Policy Audit Tool 🔒

## Overview
This tool automates the process of auditing AWS IAM policies to detect overly permissive roles and potential vulnerabilities.  
Cloud security misconfigurations can lead to serious breaches. This script helps identify risky IAM configurations and improve cloud security posture.

---

## Features
- Detect overly permissive **IAM policies** (e.g., wildcard permissions `*`).
- Generate a summary of all users/roles with **AdministratorAccess**.
- Identify policies that allow **public access**.
- Supports AWS CLI for authentication.

---

## Prerequisites
- **Python 3.8+**
- AWS CLI configured with proper credentials.
- Required Libraries (install via `requirements.txt`):
  ```bash
  pip install boto3 pandas
