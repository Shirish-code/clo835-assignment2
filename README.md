# CLO835 Assignment 2 - Kubernetes Manifests

This repo contains Kubernetes manifests for:
- Web application (employees)
- MySQL database

Manifests included:
- Pods
- ReplicaSets
- Deployments
- Services (Web: NodePort 30000, MySQL: ClusterIP)

Folder structure:
- k8s/pods
- k8s/replicasets
- k8s/deployments
- k8s/services

## Container Images (ECR)
- Web:
  - 389641759352.dkr.ecr.us-east-1.amazonaws.com/employees:v1
  - 389641759352.dkr.ecr.us-east-1.amazonaws.com/employees:v2
- DB:
  - 389641759352.dkr.ecr.us-east-1.amazonaws.com/mysql:v1

## Cluster
- kind cluster name: clo835
- NodePort used for web service: 30000
- Namespaces: web, db
