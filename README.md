# Infrastructure Automation with Terraform & AWS

This project demonstrates how to automate infrastructure provisioning on AWS using Terraform with reusable modules and optional CI/CD integration (e.g., Spacelift).

## 🚀 Features

- Modular Terraform setup for reusability and maintainability
- Infrastructure components: VPC, EC2, S3, IAM, etc.
- Environment configurations (e.g., dev, prod)
- GitOps workflow compatibility (Spacelift-ready)
- Open Policy Agent (OPA) support for policy-as-code

## 🛠 Tools Used

- **Terraform** – Infrastructure as Code
- **AWS** – Cloud provider
- **Spacelift (optional)** – Infrastructure CI/CD
- **Open Policy Agent (OPA)** – Policy engine
- **GitHub Actions / GitOps** – Version-controlled automation


## ⚙️ How to Use

1. **Configure AWS CLI credentials**  
   ```bash
   aws configure
cd environments/dev
terraform init
terraform plan
terraform apply
 Use spacelift/stack-config.yaml to automate Terraform plans & applies 
 References
Terraform Docs
AWS Provider
Spacelift
Open Policy Agent
📄 License
This project is licensed under the Apache 2.0 License.

