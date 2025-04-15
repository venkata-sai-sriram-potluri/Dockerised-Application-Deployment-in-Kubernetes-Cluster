# Dockerised-Application-Deployment-in-Kubernetes-Cluster


This project demonstrates end-to-end containerization and deployment of a multi-component application using Docker, Kubernetes, and AWS cloud services. It highlights best practices in building, testing, and deploying containerized applications with scalability and reliability.

## 🔧 Technologies Used

- Docker
- Docker Compose
- Kubernetes
- Amazon Elastic Kubernetes Service (EKS)
- Amazon Elastic Block Store (EBS)
- Application Load Balancer (ALB)
- Docker Hub

## 📌 Project Overview

This setup includes:

- Building Docker images from application source code for consistent environments across development and production.
- Testing multi-container applications using Docker Compose to simulate production-like configurations.
- Pushing Docker images to Docker Hub for centralized access and reuse across environments.
- Deploying the application to a Kubernetes cluster with Deployment and Service resources for orchestration and scaling.
- Configuring Ingress and Load Balancing using AWS Application Load Balancer to manage external traffic.
- Integrating persistent storage using Amazon EBS volumes to support stateful application components.

## 🚀 Features

- End-to-end CI/CD ready containerization pipeline.
- Scalable and resilient deployment on Kubernetes.
- Centralized image management using Docker Hub.
- Load-balanced application traffic with high availability.
- Persistent volume integration for databases and stateful services.
