# 🚀 Production-Grade DevOps CI/CD Automation Pipeline

<div align="center">

![DevOps](https://img.shields.io/badge/DevOps-CI%2FCD-blue?style=for-the-badge)
![Jenkins](https://img.shields.io/badge/Jenkins-Automation-red?style=for-the-badge)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Orchestration-326ce5?style=for-the-badge)
![Terraform](https://img.shields.io/badge/Terraform-IaC-844FBA?style=for-the-badge)
![AWS](https://img.shields.io/badge/AWS-Cloud-orange?style=for-the-badge)

### ⚡ End-to-End Production Style CI/CD Pipeline Automation Project

</div>

---

# 📌 Overview

This project demonstrates a **Production-Level DevOps CI/CD Automation Pipeline** built using modern DevOps tools and cloud technologies.

The primary goal of this project is to simulate a real-world enterprise DevOps workflow where code changes are automatically integrated, tested, and deployed using a fully automated CI/CD pipeline.

The project covers the complete DevOps lifecycle including:

- Application Development
- Source Code Management
- Continuous Integration
- Continuous Deployment
- Infrastructure as Code (IaC)
- Kubernetes Deployment
- Automation using Jenkins
- GitHub Webhook Integration

This repository is designed for students, beginners, and DevOps enthusiasts who want hands-on experience with industry-standard DevOps practices.

---

# 🎯 Objectives

✅ Build a real-world CI/CD pipeline

✅ Automate build, test, and deployment workflows

✅ Implement Jenkins Pipeline automation

✅ Integrate GitHub Webhooks with Jenkins

✅ Deploy applications using Kubernetes

✅ Manage infrastructure using Terraform

✅ Follow professional DevOps project structure

---

# 🛠 Tech Stack

| Category | Technologies |
|---|---|
| Frontend | HTML, CSS, JavaScript |
| Version Control | Git, GitHub |
| CI/CD Tool | Jenkins |
| Container Orchestration | Kubernetes |
| Infrastructure as Code | Terraform |
| Cloud Platform | AWS |
| IDE | VS Code |
| Automation | GitHub Webhooks |

---

# ⚡ Key Features

- 🚀 Automated CI/CD Pipeline
- 🔥 Jenkins Pipeline Automation
- 🔗 GitHub Webhook Trigger Integration
- ☸ Kubernetes Deployment Configuration
- 🌍 Terraform Infrastructure Provisioning
- 📦 Automated Build & Deployment Process
- 📁 Professional DevOps Folder Structure
- ⚙ Industry-Level Workflow Simulation
- 🧪 Build → Test → Deploy Pipeline Stages
- 💻 Modern DevOps Dashboard UI

---

# 📂 Project Structure

```bash
production-cicd-pipeline/
│
├── app/
│   ├── index.html
│   ├── style.css
│   └── app.js
│
├── jenkins/
│   └── Jenkinsfile
│
├── k8s/
│   ├── deployment.yaml
│   └── service.yaml
│
├── terraform/
│   └── main.tf
│
├── screenshots/
│
└── README.md
```

---

# 🚀 CI/CD Pipeline Architecture

```text
        Developer Pushes Code
                  │
                  ▼
          GitHub Repository
                  │
                  ▼
       GitHub Webhook Trigger
                  │
                  ▼
          Jenkins Pipeline
          ┌──────────────┐
          │ Build Stage  │
          └──────────────┘
                  │
                  ▼
          ┌──────────────┐
          │  Test Stage  │
          └──────────────┘
                  │
                  ▼
          ┌──────────────┐
          │ Deploy Stage │
          └──────────────┘
                  │
                  ▼
      Kubernetes Deployment
                  │
                  ▼
 Terraform Infrastructure Provisioning
```

---

# ⚙ Jenkins Pipeline Workflow

## ✅ Build Stage

The Jenkins pipeline automatically starts the build process whenever code is pushed to GitHub.

### Tasks Performed:
- Source code checkout
- Dependency validation
- Build execution

---

## ✅ Test Stage

The application workflow and pipeline execution are validated automatically.

### Tasks Performed:
- Pipeline validation
- Build verification
- Workflow testing

---

## ✅ Deploy Stage

The deployment process is executed automatically using Jenkins Pipeline scripts.

### Tasks Performed:
- Kubernetes deployment
- Service exposure
- Infrastructure provisioning

---

# 🔥 Jenkins Features Implemented

✅ Jenkins Installation & Configuration

✅ Jenkins Pipeline Job Setup

✅ Jenkinsfile Integration

✅ GitHub Repository Connection

✅ GitHub Webhook Automation

✅ Automatic Build Triggering

✅ Pipeline Stage Execution

✅ Successful CI/CD Workflow

---

# ☸ Kubernetes Deployment

Kubernetes is used for container orchestration and deployment management.

## Deployment Files

```bash
deployment.yaml
service.yaml
```

## Apply Kubernetes Configuration

```bash
kubectl apply -f k8s/deployment.yaml
kubectl apply -f k8s/service.yaml
```

---

# 🌍 Terraform Infrastructure Setup

Terraform is used to provision infrastructure using Infrastructure as Code (IaC) principles.

## Terraform Commands

```bash
terraform init
terraform apply
```

## Infrastructure Benefits

- Automated provisioning
- Reusable infrastructure
- Scalable cloud deployment
- Infrastructure consistency

---

# 🔗 GitHub & Jenkins Integration

GitHub is integrated with Jenkins using webhooks for automatic pipeline execution.

## Integration Components

- GitHub Repository
- Jenkins Pipeline
- GitHub Webhook
- Automatic Trigger System

## Webhook URL

```text
http://YOUR-IP:8080/github-webhook/
```

## Enabled Event

✅ Push Event Trigger

---

# 🚀 Step-by-Step Project Setup

# 1️⃣ Clone Repository

```bash
git clone <repository-url>
```

---

# 2️⃣ Open Project

Open the project in:

```text
VS Code
```

---

# 3️⃣ Run Frontend Application

Use Live Server Extension in VS Code.

---

# 4️⃣ Configure Jenkins

## Install Jenkins

- Install Jenkins
- Unlock Jenkins
- Install Suggested Plugins
- Create Admin User

## Create Pipeline Job

- Create New Item
- Select Pipeline
- Configure GitHub Repository
- Add Jenkinsfile Path

---

# 5️⃣ Configure GitHub Repository

- Push project to GitHub
- Connect repository with Jenkins
- Configure branch specifier

---

# 6️⃣ Configure GitHub Webhook

Add the following webhook URL in GitHub:

```text
http://YOUR-IP:8080/github-webhook/
```

## Enable:
✅ Just the push event

---

# 7️⃣ Trigger Jenkins Pipeline

Click:

```text
Build Now
```

Pipeline automatically performs:

```text
Build → Test → Deploy
```

---

# 📸 Project Screenshots

## 🚀 DevOps Dashboard

<img width="1366" height="768" alt="dashboard" src="https://github.com/user-attachments/assets/b1366cc8-3579-47bf-97c3-1c4fa5e9afba" />


### Vs code all Screenshots
<img width="1366" height="768" alt="app" src="https://github.com/user-attachments/assets/624f0ae2-a044-4eaf-83c2-e3ffaecd6f3a" />
<img width="1366" height="768" alt="index html" src="https://github.com/user-attachments/assets/49ab1f41-4e46-4732-927b-885222e8de06" />
<img width="1366" height="768" alt="style cssjpg" src="https://github.com/user-attachments/assets/aebb3e51-5a53-47a5-91ad-b28c889e9a2d" />
<img width="1366" height="768" alt="jenkinsfile" src="https://github.com/user-attachments/assets/44eeda17-c502-49a6-9d81-26235b67703d" />
<img width="1366" height="768" alt="deployed yml" src="https://github.com/user-attachments/assets/f6d40aca-1967-4cad-bb63-55a267ca1b8a" />
<img width="1366" height="768" alt="hpa yml" src="https://github.com/user-attachments/assets/ff28a30a-d85b-4c6d-9931-378ce67bcd72" />
<img width="1366" height="768" alt="ingress yaml" src="https://github.com/user-attachments/assets/d79ff3fd-f4bc-4789-bab9-3e0f89562061" />
<img width="1366" height="768" alt="secret yaml" src="https://github.com/user-attachments/assets/4689397c-d4b6-4a51-b128-eccc3123e064" />
<img width="1366" height="768" alt="service yaml" src="https://github.com/user-attachments/assets/c493c72e-c132-4755-ad72-8755e4e098f3" />
<img width="1366" height="768" alt="grafnasetup md" src="https://github.com/user-attachments/assets/1fa2c8ec-b832-4951-a331-5f424900a961" />
<img width="1366" height="768" alt="main tf" src="https://github.com/user-attachments/assets/6baf4308-524e-4ff9-a967-ada134f38c70" />

## Jenkins Sreenshot
<img width="1366" height="768" alt="jenkins1" src="https://github.com/user-attachments/assets/9a39aba5-de90-4ff5-b878-b9654c2c7c38" />
<img width="1366" height="768" alt="jenkins2" src="https://github.com/user-attachments/assets/9ecba6ac-618e-4d96-a9c0-abd600637200" />
<img width="1366" height="768" alt="jenkins3" src="https://github.com/user-attachments/assets/f288950b-a98a-4028-90fe-12255b7d4ac0" />
<img width="1366" height="768" alt="jenkins4" src="https://github.com/user-attachments/assets/9faa75b7-75c8-4374-b304-cae8247cca89" />
<img width="1366" height="768" alt="jenkins5" src="https://github.com/user-attachments/assets/56b91090-d290-4ffa-aa56-09570565a0a4" />
<img width="1366" height="768" alt="jenkis6" src="https://github.com/user-attachments/assets/0c2ff167-6e86-4bc2-832b-6261908f1827" />

---

# 📈 Project Outcome

Successfully implemented:

✅ End-to-End CI/CD Automation

✅ Jenkins Pipeline Integration

✅ GitHub Webhook Automation

✅ Kubernetes Deployment Workflow

✅ Terraform Infrastructure Provisioning

✅ Production-Level DevOps Architecture

✅ Real Industry DevOps Workflow

---

# 🔄 Real-World DevOps Workflow

```text
Developer Commit
        ↓
GitHub Repository
        ↓
Webhook Trigger
        ↓
Jenkins Pipeline
        ↓
Build Stage
        ↓
Test Stage
        ↓
Deploy Stage
        ↓
Kubernetes Deployment
```

---

# 💡 Learning Outcomes

Through this project, the following DevOps concepts were learned:

- CI/CD Pipeline Automation
- Jenkins Pipeline Configuration
- GitHub Webhook Integration
- Kubernetes Basics
- Terraform Infrastructure Management
- DevOps Workflow Automation
- Infrastructure as Code
- Production-Level Project Structure

---

# 🚀 Future Enhancements

- Docker Containerization
- AWS EC2 Deployment
- SonarQube Code Quality Analysis
- Prometheus Monitoring
- Grafana Dashboard Integration
- Jenkins Shared Libraries
- Production Kubernetes Cluster
- NGINX Ingress Controller
- ArgoCD GitOps Deployment

---

# ⭐ Support & Contribution

If you found this project useful:

⭐ Star the Repository

🍴 Fork the Project

📢 Share with Others

🚀 Connect on LinkedIn

---

---

# ✅ Project Status

🟢 GitHub Integrated

🟢 Jenkins Connected

🟢 Webhook Working Successfully

🟢 CI/CD Pipeline Running

🟢 Kubernetes Deployment Configured

🟢 Terraform Infrastructure Provisioned

🟢 Production DevOps Workflow Completed Successfully 🚀

# 👨‍💻 Author

## Tejas Kherade

### AWS Cloud & DevOps Enthusiast 🚀

### Skills:
- Linux
- AWS
- Jenkins
- Terraform
- Kubernetes
- Git & GitHub
- CI/CD Automation
