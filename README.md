# Task 3 - DevOps Internship: Docker Provisioning with Terraform

## 🚀 Objective
Provision a local Docker container using **Terraform** to demonstrate Infrastructure as Code (IaC).

## 🛠 Tools Used
- Terraform v1.12.2
- Docker Desktop on Windows
- Docker Provider for Terraform

## ⚙ What This Does
- Pulls the `nginx:latest` Docker image
- Provisions a Docker container named `nginx_container`
- Maps container port 80 to localhost port 8080

## 📂 Files
- `main.tf` — Terraform configuration
- `.terraform.lock.hcl` — Provider lock file
- `screenshots/` — Output of terminal and browser

## 🖥️ Output
### ✅ Terraform Apply Success
![Terraform Apply Screenshot](screentshots/terraform apply.png)

### 🌐 NGINX Page
![NGINX Screenshot](screentshots/nginx.png)

## 🧹 Cleanup
To destroy the container:
```bash
terraform destroy
