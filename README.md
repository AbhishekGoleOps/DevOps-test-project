# 🚀 DevOps Test Project (Git + Docker + CI/CD + Kubernetes)

This project demonstrates an end-to-end DevOps workflow:
Git → Docker → CI/CD → Kubernetes deployment.

---

## 📌 Project Overview

In this project, I implemented:

- Git feature branch workflow
- Merge conflict resolution
- Docker containerization
- CI/CD pipeline using GitHub Actions
- Docker image push to Docker Hub
- Kubernetes deployment using KIND

---

## 🔄 Complete Workflow


---

## 🧠 What I Learned

### 🔹 Git
- Branching strategy (`feature-*`)
- Merge conflicts and resolution
- Debugging using:
  - `git log`
  - `git diff`
  - `git blame`

### 🔹 Docker
- Writing Dockerfile
- Building images
- Running containers

### 🔹 CI/CD (GitHub Actions)
- Creating workflow YAML
- Triggering pipeline on push
- Using secrets securely
- Automating Docker build & push

### 🔹 Kubernetes
- Writing deployment.yaml
- Deploying application using KIND
- Pulling image from Docker Hub

---

## 🛠️ Step-by-Step Setup Guide

### 1️⃣ Clone Repo

```bash
git clone https://github.com/AbhishekGoleOps/DevOps-test-project.git
cd DevOps-test-project
```
2️⃣ Run Application Locally
```bash
python app.py
```
3️⃣ Build Docker Image
```bash
docker build -t devops-app .
```
5️⃣ Kubernetes Deployment
```bash
kubectl apply -f deployment.yaml
kubectl get pods
```
6️⃣ CI/CD Pipeline

On every push:

- GitHub Actions runs automatically
- Builds Docker image
- Pushes image to Docker Hub

🔐 GitHub Secrets Required

Go to GitHub → Settings → Secrets → Actions

Add:

- DOCKER_USERNAME
- DOCKER_PASSWORD (Docker Hub token)

📁 Project Structure

```bash
.
├── app.py
├── Dockerfile
├── deployment.yaml
├── .github/workflows/main.yml
└── screenshots/
```
📖 My DevOps Journey

This project was built as part of my DevOps learning path:

Git → Docker → Kubernetes → CI/CD

The goal was to simulate real-world DevOps workflows used in production environments.

