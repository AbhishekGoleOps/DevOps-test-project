# 🚀 DevOps Real Project

This project demonstrates real-world Git workflows along with Docker integration.

---

## 📌 Features
- Git branching (feature-based workflow)
- Merge conflict creation & resolution
- Git debugging using log, diff, blame
- Dockerized Python application

---

## 🧠 Git Concepts Demonstrated

### 🔹 Branching Strategy
- Created feature branch: `feature-logging`
- Merged into main branch

### 🔹 Merge Conflict Resolution
- Conflict created intentionally between `main` and `feature-logging`
- Resolved manually

### 🔹 Debugging with Git
- `git log --oneline --graph` → visualize history
- `git diff` → identify changes
- `git blame` → track code changes
---
Git Logs screenshot - 

![Git Log](screenshots/git-log.png)
---
Docker app run screenshot - 

![Docker Run](screenshots/docker-run.png)
---

## 🐳 Docker Usage

### Build Image
```bash
docker build -t devops-app .
