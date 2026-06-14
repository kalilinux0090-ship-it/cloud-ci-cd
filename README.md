# CLOUD-105 - Docker CI/CD Automation Project

## Project Overview

This project demonstrates a complete CI/CD pipeline using:

- GitHub Actions
- Docker
- Docker Hub
- AWS EC2
- Linux

When code is pushed to GitHub:

1. GitHub Actions triggers automatically
2. Docker image is built
3. Image is pushed to Docker Hub
4. GitHub Actions connects to AWS EC2 via SSH
5. Latest image is pulled
6. Docker container is redeployed automatically

---

## Tech Stack

- AWS EC2
- Linux
- Git & GitHub
- GitHub Actions
- Docker
- Docker Hub

---

## CI/CD Workflow

Developer Push
↓
GitHub Actions
↓
Docker Build
↓
Docker Hub Push
↓
EC2 Deployment
↓
Application Live

---

## Deployment URL

http://<EC2-PUBLIC-IP>:8081

---

## Screenshots

### GitHub Actions Success

(Add Screenshot)

### Docker Hub Repository

(Add Screenshot)

### Running Application

(Add Screenshot)

---

## Skills Demonstrated

- CI/CD Pipeline Creation
- Docker Containerization
- GitHub Actions Automation
- AWS EC2 Deployment
- SSH Automation
- Docker Hub Registry Management
- DevOps Troubleshooting
