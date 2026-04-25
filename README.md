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
⚙️ Commands to Run with Kind
1️⃣ Install Kind
go install sigs.k8s.io/kind@latest

2️⃣ Verify Installation
kind versionkubectl version --clientdocker --version

3️⃣ Create Cluster using Kind Config
kind create cluster --name my-cluster --config kind-config.yml

4️⃣ Check Cluster Information
kubectl cluster-infokubectl get nodeskubectl get namespaces

5️⃣ Apply Namespace
kubectl apply -f namespace.yml

6️⃣ Apply ConfigMap
kubectl apply -f pod-config.yml

7️⃣ Deploy Portfolio Pod
kubectl apply -f pod-portfolio.yml

8️⃣ Apply Deployment
kubectl apply -f deployment.yml

9️⃣ Check Running Resources
kubectl get podskubectl get deploymentskubectl get serviceskubectl get all

🔟 View Logs
kubectl logs <pod-name>

1️⃣1️⃣ Delete Kind Cluster
kind delete cluster --name my-cluster

🎯 Project Purpose
This project demonstrates:
✔ Kubernetes deployment skills
✔ Kind local cluster setup
✔ YAML configuration management
✔ DevOps practical knowledge
✔ GitHub project showcase

👨‍💻 Author
Biswajit Andia
DevOps Enthusiast | MCA Student | Learning Docker, Kubernetes & CI/CD

⭐ Support
If you like this project, give it a ⭐ on GitHub.
