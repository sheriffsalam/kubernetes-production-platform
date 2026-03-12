# Kubernetes Production DevOps Platform

A production-style DevOps platform demonstrating containerization, Kubernetes orchestration, CI/CD automation, monitoring, and alerting.

This project simulates how modern cloud-native applications are built, deployed, monitored, and maintained in real-world DevOps environments.

---

## Project Overview

This platform deploys a containerized Python application into a Kubernetes cluster and integrates monitoring and alerting to simulate a production-ready infrastructure.

Key capabilities demonstrated:

• Containerized application deployment  
• Kubernetes orchestration  
• CI/CD automation pipeline  
• Infrastructure monitoring  
• Metrics visualization dashboards  
• Automated alerting system

---

## Tech Stack

Infrastructure & DevOps

- Docker
- Kubernetes
- Minikube
- Helm
- GitHub Actions

Monitoring & Observability

- Prometheus
- Grafana
- Alertmanager

Application

- Python
- Flask

---

## Architecture

```mermaid
flowchart LR

A[Developer Push Code] --> B[GitHub Repository]

B --> C[GitHub Actions CI/CD]

C --> D[Docker Build]

D --> E[Docker Registry]

E --> F[Kubernetes Cluster]

F --> G[Application Pods]

F --> H[Service]

G --> I[Prometheus Monitoring]

I --> J[Grafana Dashboards]

I --> K[Alertmanager]

K --> L[Email / Alerts]

Author

Sheriff Salam

DevOps / Cloud / Platform Engineer

GitHub: https://github.com/sheriffsalam
