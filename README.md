
# 🚀 CI/CD DevSecOps Pipeline Deployment on AWS EKS (tetris-Style Architecture)

![Docker](https://img.shields.io/badge/Docker-Container-blue)
![Jenkins](https://img.shields.io/badge/Jenkins-CI-red)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Orchestration-blue)
![ArgoCD](https://img.shields.io/badge/ArgoCD-GitOps-orange)
![AWS](https://img.shields.io/badge/AWS-EKS-yellow)

---

🎮 Deploying Tetris using CI/CD DevSecOps on EKS

This project demonstrates a complete DevSecOps CI/CD pipeline for deploying the Tetris application using modern DevOps tools such as Docker, Jenkins, Argo CD, and Amazon EKS.

The pipeline automates building, containerizing, and deploying the application to a Kubernetes cluster.

---

📌 Project Overview

The goal of this project is to implement a CI/CD pipeline that automatically builds, tests, and deploys the Tetris application.

Key objectives of this project:

1.Automate application build and deployment

2.Implement DevSecOps best practices

3.Deploy applications on Kubernetes

4.Use GitOps for continuous deployment

---


## 🏗 Architecture Diagram

<p align="center">
  <img src="images/architecture.gif"/>
</p>

---

# 🔁 CI/CD Pipeline Workflow

1️⃣ Developer pushes source code to GitHub

2️⃣ Jenkins automatically triggers the CI pipeline.

3️⃣ Jenkins builds the application and creates a container image using Docker.

4️⃣ The Docker image is pushed to DockerHub.

5️⃣ Kubernetes deployment files are stored in the repository.

6️⃣ Argo CD continuously monitors the repository for changes.

7️⃣ When a change is detected, ArgoCD automatically deploys the application to Amazon EKS.

8️⃣ The Tetris application becomes available through the Kubernetes service.


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

