# DevOps Platform Architecture

```mermaid
flowchart LR

Developer --> GitHub

GitHub --> GitHubActions

GitHubActions --> DockerBuild

DockerBuild --> DockerHub

DockerHub --> Kubernetes

Kubernetes --> Pods

Pods --> Service

Service --> Users

Pods --> Prometheus

Prometheus --> Grafana

Prometheus --> Alertmanager