
# 🚀 CI/CD DevSecOps Pipeline Deployment on AWS EKS (tetris-Style Architecture)

## 📌 Project Overview

This project demonstrates a complete **DevSecOps CI/CD pipeline** that automatically builds, scans, and deploys a containerized application to **AWS EKS** using modern DevOps tools.

The pipeline integrates **security scanning, containerization, Kubernetes orchestration, and automated deployments** using GitOps principles.

The application used for deployment is a **Tetris web application**, which is containerized using Docker and deployed to Kubernetes.

---

# 🏗 Architecture Diagram

![Architecture Diagram](devsecops-tetris-eks/images/architecture.gif)

---

# 🔁 CI/CD Pipeline Workflow

1.Developer pushes code to GitHub

2.Jenkins pipeline starts

3.SonarQube performs code analysis

4.Dependencies installed using NPM

5.OWASP dependency scanning

6.Trivy file scan

7.Docker image build

8.Docker image pushed to DockerHub

9.Image scanned with Trivy

10.Jenkins updates Kubernetes manifest

11.ArgoCD detects change

12.Application deployed automatically to EKS

---
# 🧰 Tools & Technologies Used

| Tool                   | Purpose                       |
| ---------------------- | ----------------------------- |
| AWS EC2                | Jenkins Server                |
| AWS EKS                | Kubernetes Cluster            |
| Terraform              | Infrastructure as Code        |
| Jenkins                | CI/CD Pipeline                |
| Docker                 | Containerization              |
| DockerHub              | Container Registry            |
| SonarQube              | Code Quality Analysis         |
| OWASP Dependency Check | Dependency Vulnerability Scan |
| Trivy                  | Container Security Scan       |
| ArgoCD                 | GitOps Deployment             |
| Kubernetes             | Container Orchestration       |
| GitHub                 | Source Code Repository        |


---

