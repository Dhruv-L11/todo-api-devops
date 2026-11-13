# Todo API DevOps Project

Student: Dhruv (USN: 1MS24CY019)  
Course: DevOps (24CYAEC59)  
Department of CSE (Cyber Security), M. S. Ramaiah Institute of Technology  

## Overview
A production-grade CI/CD and Container Orchestration pipeline featuring:
- Spring Boot 3.3.5 REST API with Actuator
- GitHub Actions & Jenkins Declarative Pipeline (Poll SCM, Automated testing & artifact packaging)
- Ansible Playbook & Custom Role for automated server provisioning and deployment
- Multi-stage Docker containerization
- Kubernetes orchestration (Deployment, ReplicaSet, NodePort Service, ConfigMap, Liveness/Readiness Probes, Zero-downtime Rollback)

## How to Build & Run Locally
```bash
./mvnw clean package
java -jar target/todo-api-1.0.0.jar
curl -s localhost:8080/
curl -s localhost:8080/todos
curl -s localhost:8080/actuator/health
```
