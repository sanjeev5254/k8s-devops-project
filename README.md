# Kubernetes DevOps Project 🚀

## Project Overview
This project demonstrates deployment of a web application using:
- Docker
- Kubernetes (Minikube)

## Steps
1. Build Docker image
2. Deploy using Kubernetes
3. Expose service

## Commands Used
```bash
docker build -t my-devops-app .
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
