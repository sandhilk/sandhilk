### Hi, I'm Sandhil 👋

**DevOps · Platform · Site Reliability Engineer** based in the UK.

I run production Kubernetes for a UK telco: 12+ clusters on-prem and on AWS EKS, GitOps with ArgoCD, GitLab CI with image scanning and signing, Terraform, Vault, and Prometheus/Grafana, with 24/7 on-call. I like turning a recurring incident into automation so it never pages anyone again.

#### 🔧 Featured work

| Project | What it shows |
|---|---|
| [**backup-doctor**](https://github.com/sandhilk/backup-doctor) | A weekly fire drill for backups: restores the newest Postgres backup into a throwaway database, verifies the data, measures real **RTO and RPO**, and reports in plain English. Runs read-only in your own environment. CI throws empty, truncated, stale and half-deleted backups at it, and every one is caught. |
| [**k8s-stateful-platform**](https://github.com/sandhilk/k8s-stateful-platform) | HA Postgres (CloudNativePG), RabbitMQ and Redis on Kubernetes, with S3 backups, alerts linked to runbooks, and CI that kills the primary and restores from backup on every push. **Failover 4s · restore 34s.** |
| [**sanvi**](https://github.com/sandhilk/sanvi) | A demo gym-wear shop as four Python microservices on Kubernetes: Postgres, RabbitMQ quorum queues with a dead-letter queue, Redis, Prometheus metrics, non-root read-only containers, Trivy scanning and an end-to-end test on every push. |
| [**terraform-kubernetes-nfs-volume**](https://github.com/sandhilk/terraform-kubernetes-nfs-volume) | A Terraform module for NFS-backed PersistentVolumes, with input validation, native Terraform tests and a GitHub Actions pipeline. |

#### 🧰 Stack

`Kubernetes` `EKS` `Helm` `Kustomize` `ArgoCD` `Terraform` `GitLab CI` `GitHub Actions` `AWS` `Vault` `Prometheus` `Grafana` `PostgreSQL` `RabbitMQ` `Python` `Bash` `Linux` `Trivy` `cosign`

#### 📫 Find me

[LinkedIn](https://www.linkedin.com/in/sandhilkypa) · Open to DevOps, Platform and SRE roles across the UK
