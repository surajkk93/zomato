# Zomato Clone - CI/CD Pipeline

This repository contains the code and configuration for deploying a Zomato Clone application using a Continuous Integration and Continuous Deployment (CI/CD) pipeline. The pipeline is built using Jenkins, SonarQube, Trivy, and OWASP Dependency-Check for security scanning, Docker for containerization, and AWS for deployment.

## Features

- **CI/CD Pipeline**: Automates the process of building, testing, and deploying the Zomato Clone application.
- **SonarQube Integration**: Performs static code analysis to ensure code quality and security.
- **OWASP Dependency-Check**: Scans the application dependencies for known vulnerabilities.
- **Trivy Security Scan**: Performs a container security scan to identify vulnerabilities in the Docker image.
- **Docker Containerization**: The application is built into a Docker container for easy deployment.
- **Deployment to AWS**: The containerized application is deployed to AWS Elastic Kubernetes Service (EKS) using Docker Hub.

## Prerequisites

To use this project, make sure you have the following installed and configured:

- **Jenkins**: For CI/CD pipeline execution.
- **Docker**: For building and pushing Docker images.
- **SonarQube**: For code quality analysis.
- **Trivy**: For container vulnerability scanning.
- **OWASP Dependency-Check**: For dependency vulnerability scanning.
- **AWS CLI**: For deploying the application to AWS.
- **Kubernetes CLI (kubectl)**: For interacting with AWS EKS.

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/surajkk93/zomato.git
cd zomato-clone-cicd
