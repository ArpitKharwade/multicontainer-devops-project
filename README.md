# 🚀 Multi-Container Application Deployment using Docker & Kubernetes

This project demonstrates a **multi-container application** built using **Node.js and MongoDB**, containerized with **Docker** and orchestrated using **Kubernetes (Minikube)**.  
The project focuses on understanding container communication, configuration management, and persistent storage in a local Kubernetes environment.

---

## 📌 Project Overview

- Backend application built with **Node.js and Express**
- MongoDB used as the database
- Application and database run in **separate containers**
- Containers are managed and orchestrated using **Kubernetes**
- Persistent storage implemented for MongoDB data
- Configuration handled using **Kubernetes ConfigMaps**

---

## 🛠️ Technologies Used

- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Containerization:** Docker  
- **Orchestration:** Kubernetes (Minikube)  
- **Configuration:** ConfigMaps  
- **Storage:** Persistent Volumes (PV) & Persistent Volume Claims (PVC)  
- **Tools:** Git, VS Code  

---

## ⚙️ Application Details

### Node.js Application
- Serves a simple web page
- Accepts email input from users
- Stores submitted emails in MongoDB
- Exposes REST endpoints for data access

### MongoDB
- Runs in a separate container
- Uses Kubernetes Persistent Volumes for data persistence
- Accessed by the Node.js application using Kubernetes service discovery

---

## 🐳 Docker Implementation

- Node.js application is containerized using a custom **Dockerfile**
- Environment variables are used to configure MongoDB connection
- Image can be built and run independently using Docker

---

## ☸️ Kubernetes Deployment

The application is deployed on Kubernetes using:
- **Deployment** for Node.js application
- **Deployment & Service** for MongoDB
- **ConfigMap** for database configuration
- **Persistent Volume & PVC** for MongoDB storage

Key Kubernetes concepts demonstrated:
- Multi-container orchestration
- Service-based communication
- Persistent storage
- Configuration management
- Pod self-healing

---

## 🎯 Learning Outcomes

- Gained hands-on experience with multi-container applications
- Understood container communication using Kubernetes services
- Implemented persistent storage for databases in Kubernetes
- Learned how to manage configuration using ConfigMaps
- Improved understanding of container orchestration fundamentals
  
