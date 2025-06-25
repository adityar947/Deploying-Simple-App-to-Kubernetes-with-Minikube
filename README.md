# 🐳 Deploying a Simple App to Kubernetes with Minikube
A step-by-step guide to deploying, configuring, securing, and monitoring a simple app using Kubernetes on Minikube.

## 📚 Table of Contents
Part 1: From Zero to Local Cluster

Part 2: Enhancing Your Kubernetes Deployment

Part 3: Securing and Routing Your App

Part 4: Monitoring Your Kubernetes App

## How to Use This Repo

### Prerequisites

🛠 How to Use This Repo
Each part builds on the previous one. Follow them in order, or jump to the part that interests you:

```
cd part-1-local-cluster
cd part-2-deployment-enhancements
cd part-3-ingress-security
cd part-4-monitoring
```

Each folder contains:

A self-contained README.md

YAML files and configuration code

Step-by-step instructions for that stage

## 📦 Prerequisites
Minikube

kubectl

Docker

Basic knowledge of Kubernetes and containers

### 🔹 Part 1: From Zero to Local Cluster
✅ Set up Minikube, kubectl, and deploy your first simple Kubernetes app.

📁 Folder: part-1-local-cluster

Highlights:

Start Minikube

Create your first Deployment and Service

Access the app via NodePort

### 🔹 Part 2: Enhancing Your Kubernetes Deployment
🛠️ Add ConfigMaps, Liveness & Readiness Probes, and implement rolling updates.

📁 Folder: part-2-deployment-enhancements

Highlights:

Use ConfigMaps & environment variables

Implement health checks

Use rolling deployments to update your app without downtime

### 🔹 Part 3: Securing and Routing Your App
🔐 Set up Ingress, TLS, and Secrets for a more secure and production-ready deployment.

📁 Folder: part-3-ingress-security

Highlights:

Use Ingress controllers

Secure traffic with TLS via self-signed certs

Store sensitive data using Secrets

### 🔹 Part 4: Monitoring Your Kubernetes App
📈 Set up Prometheus and Grafana in Minikube for monitoring and visualization.

📁 Folder: part-4-monitoring

### Highlights:

Deploy Prometheus and Grafana via Helm or manifests

Visualize metrics and pod health

Create custom dashboards

