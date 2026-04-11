# 🚀 DevOps Portfolio — Production-Grade Platform Engineering
![AWS](https://img.shields.io/badge/AWS-Cloud-orange?logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-Cloud-blue?logo=microsoftazure&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Orchestration-326CE5?logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Containers-2496ED?logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-IaC-7B42BC?logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-CI/CD-2088FF?logo=githubactions&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-GitOps-EF7B4D?logo=argo&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-Monitoring-E6522C?logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-Dashboard-F46800?logo=grafana&logoColor=white)
![Alertmanager](https://img.shields.io/badge/Alertmanager-Alerts-E6522C?logo=prometheus&logoColor=white)

DevOps Engineer specializing in **Kubernetes, AWS, and GitOps-driven platform engineering**.

I design and implement **end-to-end cloud-native platforms**, covering:

- Microservices architectures
- Kubernetes orchestration (k3s & EKS)
- CI/CD and GitOps workflows
- Infrastructure as Code (Terraform)
- Observability and monitoring systems

📍 Focused on building scalable backend platforms and deployment systems in cloud-native environments.

---

# 🧱 System Architecture Overview

![Architecture_diagram](assets/architecture.png)

This portfolio represents a complete DevOps ecosystem:

- Containerized microservices (Docker)
- Kubernetes orchestration (k3s, EKS)
- CI/CD pipelines (GitHub Actions)
- GitOps deployments (ArgoCD)
- Infrastructure provisioning (Terraform)
- Monitoring (Prometheus, Grafana)

📌 Designed as a **cohesive DevOps platform**, not a collection of isolated projects.

---

# 🔄 System Flow

### 🌐 Application Flow
User → CDN (CloudFront) → Load Balancer → Kubernetes Cluster → Microservices → Database (RDS)

### ⚙️ CI/CD Flow
Developer → GitHub → GitHub Actions → Docker Build → Container Registry → Kubernetes Deployment (ArgoCD)

### 📊 Observability Flow
Application → Prometheus → Grafana Dashboards → Alertmanager

---

# 📦 Core Platform Projects

Each project represents a **specific layer of a real-world DevOps platform**, working together as a complete system.

## 🔹 1. Emart DevOps Platform (Flagship Project)

**End-to-End DevOps Platform on Kubernetes using GitOps**

This project demonstrates a **complete production-style deployment pipeline**, integrating Kubernetes orchestration, GitOps workflows, CI/CD automation, and observability.

* Kubernetes (k3s), ArgoCD, GitHub Actions
* Microservices-based e-commerce system
* Integrated observability and deployment automation

### 🔥 Highlights

* Implemented **GitOps workflow using ArgoCD**
* Built **automated CI/CD pipelines**
* Deployed **microservices architecture on Kubernetes**
* Integrated **monitoring and alerting stack**

👉 Repositories:
- [emart-devops-platform](https://github.com/josephmj0303/emart-devops-platform)
- [emart-gitops](https://github.com/josephmj0303/emart-gitops)

---

## 🔹 2. AWS EKS .NET Microservices Platform

**Enterprise-grade Kubernetes deployment on AWS**

* Amazon EKS, Terraform, Docker, GitHub Actions
* ASP.NET Core microservices

### 🔥 Highlights

* Provisioned infrastructure using **Terraform**
* Deployed microservices on **EKS cluster**
* Built **fully automated CI/CD pipelines**
* Used **ECR for container registry**

👉 Repository: 
- [aws-eks-dotnet-microservices-platform](https://github.com/josephmj0303/aws-eks-dotnet-microservices-platform)

---

## 🔹 3. AWS Cloud-Native E-Commerce Platform

**Highly Available & Scalable AWS Architecture**

* S3, CloudFront, ALB, EC2, RDS (PostgreSQL)

### 🔥 Highlights

* Built and deployed a cloud-native e-commerce platform on AWS
* Automated deployments using GitHub Actions CI/CD
* Implemented scalable architecture (ALB, RDS, CloudFront)
* Solved real-world infra issues (DNS, routing, deployment failures)

👉 Repository: 
- [aws-cloud-native-ecommerce-platform](https://github.com/josephmj0303/aws-cloud-native-ecommerce-platform)

---

## 🔹 4. VProfile GitOps EKS Platform

**Full GitOps + IaC Implementation**

* Terraform, Helm, ArgoCD, GitHub Actions, EKS

### 🔥 Highlights

* Split architecture into:

  * Infrastructure (Terraform)
  * Application deployment (GitOps)
* Implemented **Helm-based deployments**
* Built **complete GitOps lifecycle**

👉 Repositories:

* [vprofile-gitops-eks-platform](https://github.com/josephmj0303/vprofile-gitops-eks-platform)
* [vprofile-gitops-app-deploy](https://github.com/josephmj0303/vprofile-gitops-app-deploy)
* [vprofile-gitops-iac](https://github.com/josephmj0303/vprofile-gitops-iac)

---

## 🔹 5. Monitoring & Observability Stack

**Production-grade monitoring system**

* Prometheus, Grafana, Alertmanager
* Python Flask application instrumentation

### 🔥 Highlights

* Implemented **metrics collection and visualization**
* Configured **alerting system**
* Designed **dashboard for real-time monitoring**

👉 Repository: 
- [monitoring-and-observability](https://github.com/josephmj0303/monitoring-and-observability)

---

# ⚡ Additional Projects

### 🔸 Emart Microservices Docker Deployment

* Docker Compose-based microservices setup
* Nginx reverse proxy
  👉 [emart-microservices-docker](https://github.com/josephmj0303/emart-microservices-docker)

---

### 🔸 Azure DevOps E-Commerce Platform

* Migration to **Azure PaaS architecture**
* Demonstrates **multi-cloud capability**
  👉 [ecommerce-azure-devops-platform](https://github.com/josephmj0303/ecommerce-azure-devops-platform)

---

### 🔸 AWS CI/CD with Elastic Beanstalk

* CodePipeline, CodeBuild, S3, RDS
  👉 [aws-cicd-elasticbeanstalk](https://github.com/josephmj0303/aws-cicd-elasticbeanstalk)

---

# 🧠 Production Practices Implemented

- Infrastructure provisioning using Terraform (IaC)
- GitOps-based continuous delivery using ArgoCD
- Fully automated CI/CD pipelines (GitHub Actions)
- Scalable microservices deployment using Kubernetes
- High availability architecture (multi-AZ, load balancing)
- End-to-end observability (metrics, dashboards, alerting)
- Secure configuration and secret management

---

# 🚨 Reliability & Failure Handling

- Kubernetes self-healing via pod restarts and rescheduling
- Rolling deployments to ensure zero downtime
- Health checks and readiness probes for service stability
- Alerting on critical metrics via Prometheus & Alertmanager

---

# 🏛️ Engineering Impact & Capabilities

- Designed and deployed **microservices-based platforms on Kubernetes**
- Implemented **GitOps workflows for automated deployments**
- Built **fully automated CI/CD pipelines across multiple environments**
- Provisioned **cloud infrastructure using Terraform**
- Integrated **end-to-end observability stack**
- Demonstrated **multi-cloud capability (AWS + Azure)**

---

# 🔄 DevOps Maturity Evolution

| Stage        | Implementation                        |
|--------------|---------------------------------------|
| Traditional  | VM-based deployments (EC2)            |
| Containerized| Docker-based microservices            |
| Orchestrated | Kubernetes (k3s, EKS)                 |
| Automated    | CI/CD pipelines (GitHub Actions)      |
| GitOps       | ArgoCD-based deployments              |
| Observable   | Prometheus + Grafana + Alertmanager   |

---

# 📄 Resume
👉 [View / Download Resume](resume/Joseph_MJ_DevOps_Engineer_Resume.pdf)

---

# 📬 Contact

* GitHub: https://github.com/josephmj0303
* LinkedIn: www.linkedin.com/in/josephmj-devops

---

# ⭐ Final Note

This portfolio represents **hands-on DevOps engineering experience**, focusing on building **real-world, production-style systems** rather than isolated demos.

It reflects my ability to:

* Design scalable architectures
* Automate infrastructure and deployments
* Operate and monitor distributed systems

---

⭐ If you find this portfolio valuable, feel free to explore the repositories and connect!

