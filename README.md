# Kairi Muroki

Platform / Cloud / SRE-focused engineer building reproducible infrastructure,
developer platforms, and reliability labs.

設計図だけで終わらせず、実行結果・障害実験・運用上の限界まで記録することを
大切にしています。各リポジトリでは、個人検証と本番運用経験を明確に区別しています。

## Selected work

| Project | What it demonstrates | Core stack |
| --- | --- | --- |
| [Self-Service Developer Platform](https://github.com/Kkasuga904/self-service-developer-platform) | Service contract, Golden Path, GitOps, policy guardrails, multi-team boundaries, and disposable EKS validation | Go, EKS, Terraform, Argo CD, Helm, Kyverno, Prometheus |
| [Production-Oriented AWS Container Platform](https://github.com/Kkasuga904/production-oriented-aws-container-platform) | Private container platform with least-privilege identity, reviewed delivery, SLI/SLOs, and incident evidence | AWS, Terraform, ECS Fargate, RDS, GitHub Actions, FastAPI |
| [Kubernetes Reliability Lab](https://github.com/Kkasuga904/kubernetes-reliability-lab) | Reproducible failure experiments for probes, rollouts, PDB, HPA, graceful shutdown, and resource behavior | Kubernetes, kind, FastAPI, Docker |
| [PostgreSQL Performance & Operations Lab](https://github.com/Kkasuga904/postgresql-performance-lab) | Measured labs for indexes, lock waits, deadlocks, isolation, VACUUM, connections, and troubleshooting | PostgreSQL, SQL, Docker Compose |

## Engineering approach

- Prefer observed evidence over architecture-only claims.
- Treat security, least privilege, operability, and cleanup as design inputs.
- Automate repeatable validation in CI and document what was not validated.
- Explain trade-offs and failure boundaries instead of labeling demos “production-ready.”

## Focus areas

`AWS` · `Kubernetes` · `Terraform` · `Go` · `GitHub Actions` · `GitOps` ·
`Platform Engineering` · `SRE` · `Observability` · `PostgreSQL`
