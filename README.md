# Kubernetes Production DevOps Platform

Production-style DevOps platform demonstrating containerization, Kubernetes orchestration, CI/CD automation, monitoring, and alerting.

---

## 🚀 Overview

This project simulates a real-world DevOps environment where a containerized application is deployed, monitored, and managed using modern cloud-native tools.

---

## 🛠️ Tech Stack

- Docker
- Kubernetes
- GitHub Actions
- Prometheus
- Grafana
- Alertmanager

---

## ⚙️ Features

- CI/CD pipeline using GitHub Actions
- Kubernetes deployment with multiple replicas
- Service exposure via NodePort
- Prometheus metrics collection
- Grafana dashboards
- Alertmanager alerting

---

## 🏗️ Architecture

```mermaid
flowchart LR

A[Developer Push] --> B[GitHub]
B --> C[GitHub Actions]
C --> D[Docker Build]
D --> E[Container Registry]
E --> F[Kubernetes Cluster]
F --> G[Pods]
G --> H[Service]
G --> I[Prometheus]
I --> J[Grafana]
I --> K[Alertmanager]
