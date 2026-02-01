# GitHub Actions CI/CD – Bank Application

This repository demonstrates an end-to-end CI/CD pipeline implemented using **GitHub Actions** for deploying a **Bank Application** to a Kubernetes cluster.

## 🚀 Project Overview
The pipeline automates:
- Code checkout and build
- Static code analysis using SonarQube
- Docker image build and push to Docker Hub
- Deployment to Kubernetes using manifests

## 🧩 CI/CD Workflow Stages
1. Source Checkout – Fetch code from GitHub repository
2. Build Stage – Build the application
3. Code Quality Analysis – SonarQube scan with Quality Gate validation
4. Docker Image Build – Create container image using Dockerfile
5. Image Push – Push image to Docker Hub
6. Kubernetes Deployment – Deploy application to EKS cluster

## 🛠 Tech Stack
- GitHub Actions
- Docker & Docker Hub
- SonarQube
- AWS EKS
- Kubernetes
- Spring Boot

## ✅ Key Features
- Fully automated CI/CD pipeline
- Integrated code quality and security checks
- Containerized application deployment
- Scalable Kubernetes-based deployment
- No external CI server required

## 📌 Prerequisites
- GitHub account
- Docker Hub account
- AWS EKS cluster
- SonarQube server

## 📈 Outcome
- CI/CD stages completed successfully
- Docker image published to Docker Hub
- Quality Gate passed in SonarQube
- Application deployed and accessible via Kubernetes Service
