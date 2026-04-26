<<<<<<< HEAD
# aws-devops-nodejs-project
=======
# 🚀 AWS DevOps Node.js Project

A containerized Node.js application demonstrating a complete DevOps 
workflow using Docker and AWS cloud architecture design.

---

## 📌 Project Overview

This project demonstrates a DevOps pipeline where a Node.js application is 
containerized using Docker and designed for deployment on AWS cloud 
services including EC2, ECR, ECS, IAM, and CloudWatch.

---

## 🏗️ Architecture Flow

GitHub → EC2 → Docker → ECR → ECS → CloudWatch

---

## ☁️ AWS Services Used

### 🔹 EC2
- Used as build environment
- Docker image created and tested on EC2

### 🔹 ECR (Elastic Container Registry)
- Stores Docker images securely
- Used as image repository for ECS deployment

### 🔹 ECS (Elastic Container Service)
- Runs containerized application
- Uses Fargate for serverless deployment

### 🔹 IAM (Identity and Access Management)
- Manages secure permissions for AWS services
- Controls ECS, ECR, and CloudWatch access

### 🔹 CloudWatch
- Collects and monitors logs
- Helps in debugging and monitoring application

---

## 📁 Project Structure
aws-devops-nodejs-project/ │ ├── app/ │   ├── server.js │   
└── package.json │ ├── ecs/ │   └── task-definition.json │ 
├── iam/ │   └── policy.json │ ├── cloudwatch/ │   └── 
logs.md │ ├── ec2/ │   └── setup.md │ ├── ecr/ │   └── 
notes.md │ ├── Dockerfile ├── .gitignore └── README.md
---

## 🐳 Run Project (Docker)

### Build Image
```bash
docker build -t devops-app .

Run Container : docker run -p 3000:3000 devops-app

open Browser : http://localhost:3000

DevOps Project Running Successfully

Author : Anjle 

DevOps Learning Project
Built for AWS + Docker + CI/CD understanding
>>>>>>> 76ea111 (Initial DevOps project with Docker and AWS architecture)
