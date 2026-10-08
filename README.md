# Kubernetes Docker Web Application

## Project Overview

A hands-on DevOps project demonstrating how to build a Docker image and deploy a web application on Kubernetes.

## Technologies Used

- Docker
- Kubernetes
- Kubernetes Deployment
- Kubernetes Pods
- Kubernetes Service
- Docker Desktop
- kubectl
- HTML/CSS
- Git & GitHub

## Architecture

Developer
   ↓
Dockerfile
   ↓
Docker Image
   ↓
Kubernetes Deployment
   ↓
3 Kubernetes Pods
   ↓
Kubernetes Service
   ↓
Web Application

## Kubernetes Features Demonstrated

- Deployment
- Pods
- Replica management
- NodePort Service
- Self-healing
- Scaling
- kubectl commands
- Containerized web application

## Deployment

The application was deployed using a Kubernetes Deployment with 3 replicas.

## Scaling Test

The application was successfully scaled from:

3 Pods → 5 Pods → 3 Pods

## Self-Healing Test

One Pod was manually deleted and Kubernetes automatically created a replacement Pod.

## Application

The application displays:

"Kubernetes Web Application"

## Author

Mohan Kumar Reddy