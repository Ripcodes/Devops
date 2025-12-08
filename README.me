# ⚙️ MedGrid – DevOps & CI/CD Infrastructure (Hybrid Pipeline)

A complete end-to-end **Hybrid CI/CD Infrastructure** built for the MedGrid Hospital Management System.
This project demonstrates how DevOps pipelines operate in both **traditional (Freestyle)** and **modern (Pipeline-as-Code)** architectures, using a fully simulated **on-premise environment** connected to GitHub cloud triggers.

---

## 🏥 Overview

MedGrid DevOps is designed to bring **automation, reliability, and observability** to a hospital’s software deployment lifecycle.
The system integrates **GitHub → Jenkins → SonarQube → Nexus → Local Server** into a seamless chain for building, scanning, storing, and deploying artifacts.

This entire infrastructure runs **locally**, making it perfect for labs, demos, and on-premise enterprise simulations without cloud costs.

---

## ✨ DevOps Highlights

### 🔄 Pipeline Automation

* **Hybrid Trigger System** using GitHub Actions → Jenkins webhook.
* **Zero-Touch Builds** fired automatically on each push to main.
* **Dual Implementation**:

  * Jenkins Freestyle (legacy)
  * Jenkins Declarative Pipeline (modern)

### 🛠️ Infrastructure Automation

* **Local Datacenter Simulation** with Jenkins + SonarQube + Nexus.
* **Node.js Environment Automation** with Bash installers.
* **Service Controls** using custom scripts (start/stop/restart).

### 🧪 Quality Control

* **SonarQube Code Scanning** for bugs, smells, security.
* **Strict Quality Gates** enforce production stability.
* **Dependency Vulnerability Checks** built-in.

---

## 🏗️ System Architecture (CI/CD Flow)

```
┌─────────────────┐    ┌───────────────────┐     ┌───────────────────┐
│ GitHub Repo     │    │ Jenkins (Local)   │     │  SonarQube        │
│                 │───►│ Freestyle/CI/CD   │◄───►│ Static Analysis   │
│ - Webhook Event │    │ Pipeline-as-Code  │     │ Quality Gate      │
└─────────────────┘    └─────────┬─────────┘     └───────────────────┘
                                  │
                                  ▼
                         ┌─────────────────┐
                         │ Nexus Repository│
                         │ - Artifacts     │
                         │ - Versioning    │
                         └───────┬─────────┘
                                  │
                                  ▼
                         ┌─────────────────┐
                         │ Local Server    │
                         │ - Deploy App    │
                         │ - Restart App   │
                         └─────────────────┘
```

---

## 🚀 Core Functionality

### 🔧 Continuous Integration (CI)

* GitHub → Jenkins auto-sync
* GitHub Actions "sanity checker"
* Build status instantly shown in GitHub

### 🚀 Continuous Deployment (CD)

* Compress app → `.tgz` artifact
* Upload to Nexus repository
* Deploy to local server with rollback

### 📊 Quality Gates

* 🟢 Pass → Deployment continues
* 🟡 Warnings → Allowed but marked unstable
* 🔴 Fail → Pipeline stops instantly

---

## 🔄 Modes of Implementation

### **1️⃣ Jenkins Freestyle (Legacy Mode)**

* Manual step-by-step configuration
* Best for beginners, linear pipelines
* Uses Shell scripts + Sonar plugin stages

### **2️⃣ Pipeline as Code (Modern Mode)**

* Entire CI/CD logic inside `.jenkins` files
* Stored in version control
* Supports multi-stage workflows
* Located under: `pipelines/`

---

## ⚡ Quick Start

### Prerequisites

* Jenkins → 8080
* SonarQube → 9000
* Nexus → 8081
* Java 11/17
* Node.js (LTS)

### 1. Clone Repository

```bash
git clone <repository-url>
cd MedGrid-DevOps
```

### 2. Configure Jenkins

* Install:

  * NodeJS Plugin
  * SonarQube Scanner Plugin
* Add:

  * Node.js setup
  * Nexus credentials
  * Sonar server token

### 3. Choose Your Pipeline Mode

✔ **Pipeline Job:** point to `pipelines/medgrid_deploy.jenkins`
✔ **Freestyle Job:** use steps from `scripts/`

---

## 🔐 Demo Credentials (Local Setup)

```
Jenkins       → admin / admin123
SonarQube     → admin / admin
Nexus         → admin / admin123
SSH Server    → user@localhost
```

---

## 📁 Project Structure

```
MedGrid-DevOps/
├── pipelines/
│   ├── build.jenkins
│   └── release.jenkins
├── scripts/
│   ├── build.sh
│   ├── deploy.sh
│   └── cleanup.sh
├── config/
│   ├── sonar-project.properties
│   └── nexus-config.json
├── .github/workflows/
│   └── trigger.yml
└── README.md
```

---

## 🔧 Manual Execution (Without Jenkins)

### Run Sonar Scan

```bash
sonar-scanner \
  -Dsonar.projectKey=medgrid \
  -Dsonar.sources=. \
  -Dsonar.host.url=http://localhost:9000 \
  -Dsonar.login=<token>
```

### Deploy Manually

```bash
chmod +x scripts/deploy.sh
./scripts/deploy.sh --env=production
```

---

## 🧪 CI/CD Testing Checklist

* [ ] GitHub → Jenkins webhook triggers job
* [ ] SonarQube blocks bad code
* [ ] Artifact appears in Nexus
* [ ] Deployment restarts service
* [ ] Rollback works correctly

---

## 🔒 Security Features

* No hardcoded credentials
* Jenkins Credential Manager used
* SSH-based deployment
* Captured SHA1/MD5 integrity checks
* Role-based access (Admin/Read-only)

