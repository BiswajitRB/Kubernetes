# ☸️ Kubernetes Practice Repository![Kubernetes Logo](https://upload.wikimedia.org/wikipedia/commons/3/39/Kubernetes_logo_without_workmark.svg)This repository contains Kubernetes YAML files for deploying applications using **Kind (Kubernetes in Docker)**.It helps demonstrate practical DevOps skills using:- :contentReference[oaicite:0]{index=0}- :contentReference[oaicite:1]{index=1}- :contentReference[oaicite:2]{index=2}- kubectl- YAML- :contentReference[oaicite:3]{index=3}---# 🏗 Kind Logo![Kind Logo](https://kind.sigs.k8s.io/logo/logo.png)---# 📁 Repository Structure```textk8s-practice/│├── namespace.yaml├── deployment.yaml├── service.yaml├── configmap.yaml│├── README.md│└── screenshots/

🏗 Architecture
Developer   ↓GitHub Repository   ↓kubectl apply -f *.yaml   ↓Kind Cluster   ↓Namespace (devops-practice)   ↓Deployment (nginx-deployment)   ↓Pods (2 Replicas)   ↓Service (NodePort)   ↓Browser Access

⚙️ Kind Commands
Install Kind
go install sigs.k8s.io/kind@latest
Create Kind Cluster
kind create cluster --name devops-cluster
Check Clusters
kind get clusters
Get Nodes
kubectl get nodes
Apply Kubernetes YAML Files
kubectl apply -f namespace.yamlkubectl apply -f deployment.yamlkubectl apply -f service.yamlkubectl apply -f configmap.yaml
Verify Deployment
kubectl get all -n devops-practice
Delete Kind Cluster
kind delete cluster --name devops-cluster

🚀 Deployment Example
Create Namespace
kubectl apply -f namespace.yaml
Deploy Application
kubectl apply -f deployment.yaml
Expose Service
kubectl apply -f service.yaml
Configure Environment
kubectl apply -f configmap.yaml

📸 Screenshots
Add screenshots of:


Kind cluster running


Pods status


Services


Browser output


inside the screenshots/ folder.

📌 Purpose
This project is created for:


DevOps Practice


Kubernetes Learning


Interview Preparation


Resume Projects


GitHub Portfolio Improvement



👨‍💻 Author
Biswajit Andia
MCA Student | DevOps Learner | Cloud & Automation Enthusiast
