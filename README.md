# Secure AWS Landing Zone with Terraform (ca-central-1)

An enterprise-grade, security-focused AWS network foundation built with Terraform to establish a modular, scalable, and cost-conscious cloud infrastructure baseline in Canada Central (`ca-central-1`).

## 🗺️ Architecture Overview
- **Custom VPC:** Isolated CIDR block (`10.20.0.0/16`)
- **Multi-AZ Public Subnets:** 2 Public Subnets for internet-facing resources
- **Multi-AZ Private Subnets:** 2 Private Subnets isolated from direct internet entry
- **Internet Gateway:** Configured for public subnet egress/ingress
- **Route Tables:** Explicitly separated route table associations for network isolation

## 🚀 Tech Stack
- **Cloud Provider:** Amazon Web Services (AWS)
- **Infrastructure as Code:** Terraform (>= 1.0.0)
- **Region:** `ca-central-1` (Canada Central)
- **Version Control:** GitHub

## 🔧 Deployment Steps
1. Clone the repository:
   ```bash
   git clone <your-repo-link>
   cd aws-landing-zone-ca
   terraform init
   terraform validate
   terraform apply

   Author: Muhammad Azam | AWS Cloud Engineer

   
