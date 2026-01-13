# EC2 Launch Lab – Secure Setup

## 🎯 Objective
Launch a secure Amazon EC2 instance and access it safely.

## ☁️ Services Used
- Amazon EC2
- IAM
- Security Groups
- Key Pairs

## 🧱 Architecture
Single EC2 instance in default VPC with restricted inbound access.

## 🪜 Steps
1. Created key pair
2. Created security group (SSH only from my IP)
3. Launched Amazon Linux 2
4. Connected via SSH

## 🔐 Security Notes
- No open 0.0.0.0/0 ports  
- Least privilege security group  
- Key stored locally, never uploaded

## ✅ Outcome
Successfully deployed and accessed EC2 instance.

## 📘 What I Learned
- How security groups work
- How EC2 networking works
- Why key protection matters
