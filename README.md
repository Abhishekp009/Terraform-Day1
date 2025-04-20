# Terraform Project: Launch EC2 Instance with Security Group

## 🧾 Description
This project provisions a simple EC2 instance in the default VPC with a security group that allows SSH access only from your IP address.

## 📦 AWS Services Used
- EC2
- Security Group
- VPC (default)
- AMI (Ubuntu 20.04)

## 🧰 Prerequisites
- Terraform installed
- AWS CLI configured
- Existing EC2 Key Pair (e.g., `my-key-pair`)

## ⚙️ How to Use

1. Clone the repo:
   ```bash
   git clone [https://github.com/Abhishekp009/Terraform-Day1.git]
   cd terraform-ec2-instance
