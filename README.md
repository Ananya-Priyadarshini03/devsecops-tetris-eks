
# 🚀 CI/CD DevSecOps Pipeline Deployment on AWS EKS (tetris-Style Architecture)

## 📌 Project Overview

This project demonstrates a complete **DevSecOps CI/CD pipeline** that automatically builds, scans, and deploys a containerized application to **AWS EKS** using modern DevOps tools.

The pipeline integrates **security scanning, containerization, Kubernetes orchestration, and automated deployments** using GitOps principles.

The application used for deployment is a **Tetris web application**, which is containerized using Docker and deployed to Kubernetes.

---

# 🏗 Architecture Diagram

![Architecture](images/architecture.png)

---

# 🔁 CI/CD Pipeline Workflow

1. Developer pushes code to GitHub
2. Jenkins pipeline is triggered
3. Code quality scan using SonarQube
4. Dependency vulnerability scan using OWASP Dependency Check
5. Docker image is built
6. Docker image is pushed to DockerHub
7. Container image security scan using Trivy
8. Kubernetes deployment manifest is updated
9. ArgoCD detects changes from Git repository
10. Application is automatically deployed to AWS EKS

---

# 🛠 Tech Stack

- AWS EKS
- Jenkins
- Docker
- Kubernetes
- ArgoCD
- Terraform
- SonarQube
- OWASP Dependency Check
- Trivy
- GitHub

---

# 📂 Project Structure
