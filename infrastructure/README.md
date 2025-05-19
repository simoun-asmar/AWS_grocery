#  Infrastructure Setup – AWS Grocery Project

This folder contains the Terraform code to provision AWS infrastructure for the AWS Grocery project.

---

## 📦 Resources Deployed

- **VPC** with two public subnets (`eu-central-1a`, `eu-central-1b`)
- **Internet Gateway** and **Route Table** for public access
- **EC2 Instance** (Amazon Linux) with a security group for SSH
- **RDS Instance** (PostgreSQL) with its own security group
- **Security Groups** to control traffic

---

##  How to Use

```bash
# 1. Initialize Terraform
terraform init

# 2. Preview the Infrastructure Plan
terraform plan

# 3. Apply the Configuration to Create the Resources
terraform apply

# 4. Destroy the Infrastructure (When Done)
terraform destroy
```
