# CI/CD Pipeline Demo with GitHub Actions, Docker, and Kubernetes

This project demonstrates a simple CI/CD pipeline using **GitHub Actions**, **Docker**, and **Kubernetes**. It includes a basic "Hello World" web application built with **Python Flask**, containerized with Docker, and deployed to a Kubernetes cluster.

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [How It Works](#how-it-works)
- [Setup Instructions](#setup-instructions)
- [CI/CD Pipeline](#cicd-pipeline)
- [Kubernetes Deployment](#kubernetes-deployment)
- [Future Improvements](#future-improvements)
- [License](#license)

---

## Project Overview
This project is a simple "Hello World" web application that showcases a fully automated CI/CD pipeline. The pipeline includes:
1. **Continuous Integration (CI):** Automatically builds and tests the application using GitHub Actions.
2. **Containerization:** Packages the application into a Docker image.
3. **Continuous Deployment (CD):** Deploys the application to a Kubernetes cluster.

---

## Technologies Used
- **GitHub Actions:** For CI/CD automation.
- **Docker:** For containerizing the application.
- **Kubernetes:** For orchestrating the deployment.
- **Python Flask:** For the web application.

---

## How It Works
1. The application is a simple Flask web server that responds with "Hello, World!" when accessed.
2. When code is pushed to the `main` branch, GitHub Actions:
   - Runs unit tests.
   - Builds a Docker image.
   - Pushes the image to Docker Hub.
   - Deploys the application to a Kubernetes cluster.

---

## Setup Instructions

### Prerequisites
- Docker installed locally.
- Kubernetes cluster (e.g., Minikube for local testing).
- Docker Hub account (for pushing images).
- GitHub repository.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
