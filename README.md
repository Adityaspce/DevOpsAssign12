# DevOpsAssign12

## 📘 Project Overview

This project automates the complete deployment lifecycle of a **Django web application** using a DevOps toolchain comprising **Terraform**, **Ansible**, **Docker**, and **AWS**.  
It provisions infrastructure, configures environments, deploys containers, and enables continuous integration and testing — all from code.

---

## 🏗️ Architecture Overview

**Workflow Summary:**
1. **Terraform** provisions AWS infrastructure (EC2 instance, security group, and SSH key).  
2. **Ansible** connects to the EC2 instance and deploys Docker containers for Django and PostgreSQL.  
3. **Docker** manages isolated, consistent runtime environments.  
4. **CI/CD (GitHub Actions/Jenkins)** automates the build, test, and deploy stages.  
5. **Selenium** validates login and registration functionalities post-deployment.

---

## 🧩 Tools and Technologies

| Tool | Purpose |
|------|----------|
| **Terraform** | Infrastructure provisioning on AWS |
| **Ansible** | Configuration management and deployment |
| **Docker** | Containerization of Django and PostgreSQL |
| **PostgreSQL** | Backend database |
| **GitHub Actions / Jenkins** | CI/CD pipeline automation |
| **Selenium** | UI automation for functional testing |
| **AWS EC2** | Host for Docker containers |

---



