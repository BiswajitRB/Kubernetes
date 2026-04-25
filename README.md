# ☸️ Kubernetes Practice Repository

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/3/39/Kubernetes_logo_without_workmark.svg" alt="Kubernetes Logo" width="180"/>
  &nbsp;&nbsp;&nbsp;
  <img src="https://kind.sigs.k8s.io/logo/logo.png" alt="Kind Logo" width="180"/>
</p>

<p align="center">
  <b>Practical Kubernetes Deployment using Kind (Kubernetes in Docker)</b>
</p>

<p align="center">
  This repository contains Kubernetes YAML files for deploying applications using <b>Kind</b>  
  and demonstrates hands-on <b>DevOps</b> skills with real deployment practices.
</p>

---

## 🚀 Technologies Used

<p align="center">

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kind](https://img.shields.io/badge/Kind-000000?style=for-the-badge&logo=kubernetes&logoColor=white)
![Kubectl](https://img.shields.io/badge/Kubectl-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![YAML](https://img.shields.io/badge/YAML-CB171E?style=for-the-badge&logo=yaml&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

</p>

---

## 🏗️ Using Kind (Kubernetes in Docker)

Kind allows you to run local Kubernetes clusters using Docker containers as nodes.

It is useful for:

- Learning Kubernetes
- Testing deployments
- CI/CD pipeline practice
- DevOps project demonstrations

---
## ⚙️ Commands to Run with Kind

### 1️⃣ Install Kind

```bash
go install sigs.k8s.io/kind@latest

## 📁 Repository Structure

```text
k8s/
│
├── nginx/
│
├── portfolio/
│
├── deployment.yml
│
├── namespace.yml
│
├── pod-portfolio.yml
│
├── pod-config.yml
│
├── kind-config.yml
│
└── README.md
