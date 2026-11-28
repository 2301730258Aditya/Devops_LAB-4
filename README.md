# ENSP461 Lab 4: Advanced Deployment Strategies & Enterprise DevOps

- **Student:** YOUR_NAME (YOUR_ROLL_NUMBER)
- **Environment:** Ubuntu 24.04 LTS (WSL2), Docker, Kubernetes (Minikube), Jenkins, HashiCorp Vault
- **Repository:** https://github.com/YOUR_GITHUB_USERNAME/devops-lab-4

## Structure
- `app/` — Flask + SQLite microservice with health, persistence, secret-fingerprint, and fault-injection endpoints
- `tests/` — Automated unit and integration test suites (CI/CD pipeline gates)
- `Jenkinsfile` — Declarative CI/CD pipeline with test gates and secret masking
- `dr/` — Disaster Recovery backup, integrity verification, restore, and failover scripts
- `k8s/blue-green/` — Kubernetes Blue-Green deployment manifests and zero-downtime switcher
- `k8s/canary/` — Kubernetes Canary deployment manifests, weighted router, and automated rollback controller
- `gitops/` — Declarative Kubernetes manifests and automated GitOps reconciliation loop
- `secrets/` — HashiCorp Vault least-privilege policy, scoped token setup, secret rotation, and K8s Secret sync
- `docs/` — Captured command logs and terminal screenshots

## Student template notice
Adapted from instructor-distributed example repository. Historical reports, screenshots, logs and generated infrastructure state are intentionally excluded. Run the exercises yourself and add your own evidence. Configure your own GitHub repository and environment before running.
Create the namespace with `kubectl create namespace lab4-student` before deploying the manifests.
