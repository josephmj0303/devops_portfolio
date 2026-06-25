# 🚀 DevOps Portfolio — Production-Grade Platform Engineering
![AWS](https://img.shields.io/badge/AWS-Cloud-orange?logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-Cloud-blue?logo=microsoftazure&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Orchestration-326CE5?logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Containers-2496ED?logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-IaC-7B42BC?logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-Automation-EE0000?logo=ansible&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-CI/CD-2088FF?logo=githubactions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-CI/CD-D24939?logo=jenkins&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-CI/CD-FC6D26?logo=gitlab&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-GitOps-EF7B4D?logo=argo&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-Quality-4E9BCD?logo=sonarqube&logoColor=white)
![Nexus](https://img.shields.io/badge/Nexus-Artifacts-1B9E3E?logo=sonatype&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-Security-1904DA?logo=aqua&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-Monitoring-E6522C?logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-Dashboard-F46800?logo=grafana&logoColor=white)

---

## 👨‍💻 About Me

Cloud DevOps Engineer with **hands-on experience in** designing and deploying scalable, cloud-native platforms on **AWS and Azure**.

I design and implement **end-to-end cloud-native platforms**, covering:

- Microservices architectures on Kubernetes (EKS, k3s)
- CI/CD pipelines (GitHub Actions, Jenkins, GitLab CI)
- GitOps workflows (ArgoCD)
- Infrastructure as Code (Terraform, Ansible)
- Container security scanning (Trivy)
- Observability and monitoring (Prometheus, Grafana, CloudWatch)
- Multi-cloud deployments (AWS & Azure PaaS)

📍 Focused on building scalable, automated, and observable cloud platforms — from infrastructure provisioning to production deployment.

---

## 💼 Professional Experience

### DevOps Engineer | 2+ Years Experience

✔️ Production AWS and Azure infrastructure management  
✔️ Kubernetes platform operations (EKS & k3s)  
✔️ GitHub Actions and Jenkins CI/CD automation  
✔️ GitOps implementation using ArgoCD  
✔️ Infrastructure provisioning using Terraform and Ansible  
✔️ Monitoring, alerting and reliability engineering  
✔️ Container security scanning and deployment governance  


In addition to professional experience, this portfolio contains 20+ DevOps projects spanning Kubernetes, multi-cloud infrastructure, GitOps, observability, and platform engineering.

---

## 🧱 System Architecture Overview

![Architecture\_diagram](assets/architecture.png)

This portfolio represents a complete DevOps ecosystem:

* Containerized microservices (Docker)
* Kubernetes orchestration (k3s & EKS)
* CI/CD automation (GitHub Actions, GitLac CI & Jenkins)
* GitOps deployments (ArgoCD)
* Infrastructure provisioning (Terraform)
* Security scanning (Trivy)
* Monitoring and observability (Prometheus, Grafana, Alertmanager)

📌 Designed as a complete platform engineering portfolio rather than a collection of isolated projects.

---

## 🔄 System Flow

### 🌐 Application Flow

User → CloudFront → Load Balancer → Kubernetes Cluster → Microservices → Database

### ⚙️ CI/CD Flow

Developer → GitHub → GitHub Actions → Docker Build → Container Registry → ArgoCD → Kubernetes

### 📊 Observability Flow

Application → Prometheus → Grafana Dashboards → Alertmanager

### 🔐 Security Flow

Source Code → Trivy Scan → CI Pipeline → Container Registry → Kubernetes Deployment

---

## 🛠 Technology Matrix

| Category   | Technologies                                  |
| ---------- | --------------------------------------------- |
| Cloud      | AWS, Azure                                    |
| Containers | Docker, Kubernetes                            |
| IaC        | Terraform, Ansible                            |
| CI/CD      | GitHub Actions, Jenkins, GitLab CI            |
| GitOps     | ArgoCD                                        |
| Security   | Trivy, IAM, RBAC                              |
| Monitoring | Prometheus, Grafana, Alertmanager, CloudWatch |
| Databases  | PostgreSQL, MySQL, MSSQL                      |
| Scripting  | Bash, Python                                  |

---

## 📦 Core Platform Projects

Each project represents a **specific layer of a real-world DevOps platform**, working together as a complete system.

---

## 🔹 1. Emart DevOps Platform 

**End-to-End DevOps Platform on Kubernetes using GitOps**

Demonstrates a complete production-style deployment pipeline — Kubernetes orchestration, GitOps, CI/CD, observability, and container security.

- **Stack:** Kubernetes (k3s), ArgoCD, GitHub Actions, Prometheus, Grafana, Trivy
- **App:** Node.js, Java, Angular microservices

### 🔥 Highlights

- GitOps workflow using ArgoCD with a dedicated manifests repo
- Automated CI/CD pipelines via GitHub Actions
- Microservices deployed on k3s using Docker and Kubernetes manifests
- Prometheus + Grafana for observability
- **Trivy container security scanning** integrated into CI pipeline

👉 Repositories:
- [emart-devops-platform](https://github.com/josephmj0303/emart-devops-platform)
- [emart-gitops](https://github.com/josephmj0303/emart-gitops)

---

## 🔹 2. VProfile GitOps EKS Platform
**Production-Grade GitOps Platform on AWS EKS**

- **Stack**: Terraform, AWS EKS, ArgoCD, Helm, GitHub Actions, Amazon ECR, AWS Load Balancer Controller, SonarCloud, Slack

### 🔥 Highlights

- AWS EKS infrastructure provisioned and managed with Terraform
- GitOps deployments using ArgoCD with Auto Sync, Self-Healing, and Helm-based application delivery
- CI/CD pipelines with GitHub Actions, SonarCloud Quality Gates, and automated image publishing to Amazon ECR
- Secure Kubernetes integrations using AWS Load Balancer Controller and IRSA (IAM Roles for Service Accounts)
- Real-time deployment notifications through Slack for pipeline and release visibility

👉 Repositories:
- [vprofile-app](https://github.com/josephmj0303/vprofile-app)
- [vprofile-gitops](https://github.com/josephmj0303/vprofile-gitops)
- [vprofile-gitops-infra](https://github.com/josephmj0303/vprofile-gitops-infra)

---

## 🔹 3. AWS EKS .NET Microservices Platform

**Enterprise-grade Kubernetes deployment on AWS**

- **Stack:** Amazon EKS, Terraform, .NET Core, Docker, GitHub Actions, Prometheus, Grafana

### 🔥 Highlights

- Terraform-provisioned VPC, RDS PostgreSQL, EKS cluster
- ALB/NGINX Ingress for external traffic routing
- Fully automated CI/CD pipelines via GitHub Actions
- Prometheus + Grafana for cluster and application-level monitoring

👉 Repository:
- [aws-eks-dotnet-microservices-platform](https://github.com/josephmj0303/aws-eks-dotnet-microservices-platform)

---

## 🔹 4. AWS Cloud-Native E-Commerce Platform

**Highly Available & Scalable AWS Architecture**

- **Stack:** EC2, ALB, S3, CloudFront, RDS PostgreSQL, Terraform, GitHub Actions

### 🔥 Highlights

- Full Terraform IaC for all AWS resources
- EC2, ALB, S3 + CloudFront CDN, RDS PostgreSQL
- VPC with public/private subnets, security groups, NAT gateway
- GitHub Actions CI/CD for zero-touch deployments

👉 Repository:
- [aws-cloud-native-ecommerce-platform](https://github.com/josephmj0303/aws-cloud-native-ecommerce-platform)

---

## 🔹 5. Jenkins + SonarQube + Nexus CI Pipeline

**Production-Style CI with Quality Gates & Artifact Management**

- **Stack:** Jenkins, SonarQube, Nexus Repository Manager, Slack

### 🔥 Highlights

- Automated build → SonarQube quality gate → Nexus artifact publish → Slack alert
- Quality gates enforce code coverage thresholds and block deployments on vulnerability failures
- Nexus Repository Manager configured for versioned artifact storage and reuse

👉 Repository:
- [jenkins-sonarqube-nexus-ci](https://github.com/josephmj0303/jenkins-sonarqube-nexus-ci)

---

## 🔹 6. Monitoring & Observability Stack

**Production-grade monitoring system**

- **Stack:** Prometheus, Grafana, Alertmanager, Python Flask

### 🔥 Highlights

- Production-grade metrics collection and log aggregation for a Python Flask app
- Custom Grafana dashboards for real-time visibility into application and infrastructure health
- Alertmanager rules configured for proactive multi-channel incident notification

👉 Repository:
- [monitoring-and-observability](https://github.com/josephmj0303/monitoring-and-observability)

---

## ⚡ Additional Projects

### 🔸 Azure DevOps E-Commerce Platform

- Migrated production e-commerce from VPS (AlmaLinux + PostgreSQL) to Azure PaaS
- Azure App Service, PostgreSQL Flexible Server, Static Web Apps via Terraform
- GitHub Actions pipeline for automated build, test, and release
- Demonstrates **multi-cloud capability**

👉 [ecommerce-azure-devops-platform](https://github.com/josephmj0303/ecommerce-azure-devops-platform)

---

### 🔸 WordPress on Kubernetes (Helm + NGINX)

- WordPress deployed on AWS Kubernetes using Helm and NGINX Ingress Controller
- Persistent storage via PVC for stateful workload management
- TLS termination and custom domain routing via Kubernetes Ingress

👉 [wordpress-k8s-helm-nginx](https://github.com/josephmj0303/wordpress-k8s-helm-nginx)

---

### 🔸 Emart Microservices Docker Deployment

- Docker Compose-based microservices setup
- Nginx reverse proxy

👉 [emart-microservices-docker](https://github.com/josephmj0303/emart-microservices-docker)

---

### 🔸 AWS CI/CD with Elastic Beanstalk

- CodePipeline, CodeBuild, S3, RDS

👉 [aws-cicd-elasticbeanstalk](https://github.com/josephmj0303/aws-cicd-elasticbeanstalk)

---

## 🔐 Security Practices

✔️ Trivy container vulnerability scanning  
✔️ IAM and RBAC implementation  
✔️ Secure CI/CD pipelines  
✔️ Infrastructure security best practices  
✔️ GitOps deployment governance  
✔️ Least privilege access controls  
✔️ Secure image management practices  

---

## 🚨 Reliability & Failure Handling

✔️ Kubernetes self-healing and pod recovery  
✔️ Rolling deployments for zero downtime  
✔️ Health checks and readiness probes  
✔️ Infrastructure monitoring and alerting  
✔️ Automated deployment rollback capabilities  
✔️ High availability cloud architecture  
✔️ Incident detection and response workflows 

---

## 🏛 Engineering Capabilities

* Cloud Infrastructure Engineering
* Kubernetes Platform Operations
* Infrastructure as Code
* GitOps & Continuous Delivery
* CI/CD Automation
* Multi-Cloud Architecture
* Platform Reliability Engineering
* Observability & Monitoring
* Container Security
* Production Support

---

## 🔄 DevOps Maturity Evolution

| Stage | Implementation |
|---|---|
| Traditional | VM-based deployments (EC2) |
| Containerised | Docker-based microservices |
| Orchestrated | Kubernetes (k3s, EKS) |
| Automated | CI/CD pipelines (GitHub Actions, Jenkins) |
| Quality-Gated | SonarQube + Nexus artifact management |
| GitOps | ArgoCD-based deployments |
| Secured | Trivy container scanning in CI pipeline |
| Observable | Prometheus + Grafana + Alertmanager |

---

## 📄 Resume

👉 [View / Download Resume](resume/Joseph_MJ_DevOps_Engineer_Resume.pdf)

---

## 📬 Contact

- GitHub: [github.com/josephmj0303](https://github.com/josephmj0303)
- LinkedIn: [linkedin.com/in/josephmj-devops](https://www.linkedin.com/in/josephmj-devops)
- Email: josephmj333@gmail.com
- Website: https://joedevopslab.xyz

---

## ⭐ Final Note

This portfolio reflects **hands-on DevOps engineering experience** — from infrastructure provisioning and CI/CD automation to production deployment, security, and observability.

It demonstrates the ability to:

- Design scalable, fault-tolerant architectures
- Automate infrastructure and deployments end-to-end
- Enforce quality and security gates in CI/CD pipelines
- Operate and monitor distributed systems in production

---

⭐ If you find this portfolio valuable, feel free to explore the repositories and connect!

