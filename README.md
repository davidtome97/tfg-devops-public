<div align="center">

# 🚀 DevOps Automation Platform

### Automated CI/CD Deployment Assistant for AWS

Bachelor's Final Project focused on automating application deployments using modern DevOps practices.

---

![Java](https://img.shields.io/badge/Java-17-orange)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x-brightgreen)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-CI/CD-blue?logo=githubactions)
![AWS](https://img.shields.io/badge/AWS-Cloud-orange?logo=amazonaws)
![SonarCloud](https://img.shields.io/badge/SonarCloud-Code_Quality-blue?logo=sonarcloud)
![License](https://img.shields.io/badge/License-MIT-green)

</div>

---

# 📖 Overview

This project was developed as my Bachelor's Final Project in Computer Engineering at the University of Burgos.

The objective was to design and develop a complete DevOps platform capable of automating cloud application deployments through a guided deployment wizard.

The platform allows developers to configure an application, select deployment technologies and automatically generate the resources required to deploy it using modern CI/CD workflows.

Unlike a traditional academic project, this application simulates a real DevOps workflow by integrating cloud services, containerization, code quality analysis and deployment automation.

---

# ✨ Main Features

✅ Deployment Wizard

Configure applications through a step-by-step assistant.

---

✅ CI/CD Pipeline Generation

Automatically generate deployment configurations for:

- GitHub Actions
- GitLab CI
- Jenkins

---

✅ Docker Integration

Generate Docker and Docker Compose configuration automatically.

---

✅ AWS Deployment

Supports deployment using:

- Amazon EC2
- Amazon ECR
- IAM
- Security Groups

---

✅ Multi Database Support

Choose between:

- PostgreSQL
- MySQL
- MongoDB

---

✅ Environment Configuration

Supports different environments:

- Local
- Production

using separated configuration files.

---

✅ Code Quality

Integration with SonarCloud for automatic static code analysis.

---

✅ Security

Implements:

- Spring Security
- Authentication
- Environment variables
- Secrets management
- Secure deployment configuration

---

# 🏗 Architecture

The application follows a layered architecture based on Spring Boot.

```text
                User
                  │
                  ▼
        Deployment Wizard
                  │
                  ▼
            Spring Boot
                  │
     ┌────────────┼────────────┐
     ▼            ▼            ▼
 Database     Docker      CI/CD Providers
                              │
          GitHub Actions / GitLab / Jenkins
                              │
                              ▼
                         AWS Deployment
```

---

# 🔄 DevOps Workflow

The generated deployment process follows a modern DevOps workflow.

```text
Developer

↓

Git Repository

↓

GitHub Actions

↓

Build

↓

Tests

↓

SonarCloud Analysis

↓

Docker Image

↓

Amazon ECR

↓

Amazon EC2

↓

Running Application
```

---

# 🛠 Technologies

## Backend

- Java 17
- Spring Boot
- Spring MVC
- Spring Security
- Spring Data JPA
- Thymeleaf

## Databases

- PostgreSQL
- MySQL
- MongoDB
- H2

## DevOps

- Docker
- Docker Compose
- GitHub Actions
- GitLab CI
- Jenkins

## Cloud

- AWS EC2
- AWS ECR
- IAM

## Code Quality

- SonarCloud

## Database Versioning

- Flyway

---

# 📸 Screenshots

## Deployment Wizard

<img width="1352" height="798" alt="Captura de pantalla 2026-07-01 a las 14 03 15" src="https://github.com/user-attachments/assets/f344b8a5-9b3e-43a9-bf42-7b8843a31249" />


---

## Dashboard

<img width="1352" height="765" alt="Captura de pantalla 2026-07-01 a las 14 04 14" src="https://github.com/user-attachments/assets/74f092a8-ecf3-43b6-a67c-40bf2eea4a1b" />
<img width="1352" height="765" alt="Captura de pantalla 2026-07-01 a las 14 05 01" src="https://github.com/user-attachments/assets/6c2e0a72-1773-4619-902e-df7c02277890" />


---

## Generated CI/CD Pipelines

(Add your screenshots here)

---

## 📚 Documentation

- [📄 Currículum](docs/cv/CV_David_Tome.pdf)
- [☁️ AWS Certified Cloud Practitioner](docs/cv/aws-cloud-practitioner.pdf)
- [🏗 AWS Certified Solutions Architect Associate](docs/cv/aws-solutions-architect.pdf)
- [📚 Memoria completa del TFG](docs/memoria/memoria.pdf)

# 🚀 Running the Project

## Requirements

- Java 17
- Docker
- Docker Compose
- PostgreSQL (optional)

Clone repository

```bash
git clone https://github.com/davidtome97/tfg-devops-public.git
```

Run

```bash
docker compose up
```

---

# 🔐 Security

The platform follows several security best practices.

- User authentication
- Spring Security
- Secure environment configuration
- Secrets management
- Protected endpoints
- Environment separation
- Secure deployment workflow

---

# 🎯 Project Objectives

The main goals of the project were:

- Apply DevOps principles
- Automate deployment processes
- Integrate cloud services
- Generate CI/CD pipelines
- Support multiple databases
- Containerize applications
- Simulate enterprise deployment workflows

---

# 📈 Future Improvements

- Kubernetes support
- Terraform integration
- Ansible integration
- Monitoring with Prometheus & Grafana
- Helm Charts
- Multi-cloud deployment
- Automated Infrastructure as Code

---

# 👨‍💻 Author

**David Tomé Arnaiz**

Computer Engineer

AWS Certified Solutions Architect – Associate

AWS Certified Cloud Practitioner

Currently learning **Terraform (Infrastructure as Code)**

LinkedIn:
www.linkedin.com/in/david-tome-arnaiz-442729399


GitHub:
https://github.com/davidtome97/tfg-devops-public.git

---

# 📄 License

This project is licensed under the MIT License.
