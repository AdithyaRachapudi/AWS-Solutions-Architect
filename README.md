# AWS Solutions Architect Terraform Project

## 🚀 Overview
This project demonstrates Infrastructure as Code (IaC) using Terraform to set up an AWS environment with a **VPC, public subnet, EC2 web server, and security group**. The goal is to showcase AWS architecture best practices for high availability and security.

## ✅ Features
- **VPC & Subnet**: Creates a dedicated network environment.
- **EC2 Instance**: Deploys a web server using Amazon Linux 2.
- **Security Group**: Configured to allow HTTP (port 80) traffic.
- **Scalability & Modularity**: Easily expandable with Auto Scaling and Load Balancer.

## 🛠 Deployment Steps
### **Prerequisites**
- AWS CLI configured with proper credentials.
- Terraform installed on your system.

### **Steps**
1. Clone this repository:
   ```bash
   git clone https://github.com/AdithyaRachapudi/AWS-Solutions-Architect.git
   cd AWS-Solutions-Architect
   ```
2. Initialize Terraform:
   ```bash
   terraform init
   ```
3. Plan the infrastructure:
   ```bash
   terraform plan
   ```
4. Apply changes to deploy resources:
   ```bash
   terraform apply -auto-approve
   ```
5. To destroy the infrastructure when done:
   ```bash
   terraform destroy -auto-approve
   ```

## 📌 Future Enhancements
- Add an **Auto Scaling Group** and **Load Balancer**.
- Integrate **RDS for database storage**.
- Use **Terraform modules** for better structure.

## 👨‍💻 Author
- **Adithya Rachapudi**
- Connect on [LinkedIn](https://www.linkedin.com/in/adithyarachapudi/)
- Added README file with project details
