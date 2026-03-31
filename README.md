
# 📱 DevOps QR Code Generator — NextJS + FastAPI + Docker
 
![NextJS](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
 
> A full-stack QR code generation app with a modern NextJS frontend and Python FastAPI backend — fully containerized as a multi-service Docker application. Built as a DevOps Capstone Project.
 
---
 
## 📌 Problem → Solution → Outcome
 
| | |
|---|---|
| **Problem** | Demonstrate full-stack DevOps skills — a frontend, a backend API, and container orchestration working together as a cohesive system |
| **Solution** | Built a NextJS frontend that calls a FastAPI Python backend to generate QR codes, with both services containerized and communicating via Docker networking |
| **Outcome** | A complete, deployable full-stack application showcasing frontend-backend separation, API design, containerization, and multi-service Docker Compose orchestration |
 
---
 
## 🏗️ Architecture
 
```
  User → [NextJS Frontend :3000]
                │
                ▼
       [FastAPI Backend :8000]  ──►  [QR Code Generation]
                │
          [Docker Network]
```
 
---
 
## 🛠️ Tech Stack
 
| Layer | Technology |
|-------|-----------|
| Frontend | Next.js · React · JavaScript |
| Backend API | Python · FastAPI |
| QR Generation | qrcode Python library |
| Containerization | Docker · Docker Compose |
| API Docs | Swagger UI (auto via FastAPI) |
 
---
 
## 🚀 Quick Start
 
```bash
# Clone
git clone https://github.com/hmahajan299/devops-qr-code.git
cd devops-qr-code
 
# Start with Docker Compose
docker-compose up --build -d
 
# Access
# Frontend  → http://localhost:3000
# API Docs  → http://localhost:8000/docs
```
 
---
 
## 🔑 DevOps Concepts Demonstrated
 
- ✅ **Microservices architecture** — frontend and backend as separate containers
- ✅ **REST API design** with FastAPI and auto-generated Swagger docs
- ✅ **Docker Compose** multi-service orchestration
- ✅ **Cross-container networking** — frontend calls backend by service name
- ✅ **Full-stack containerization** from scratch.
 
---
 
