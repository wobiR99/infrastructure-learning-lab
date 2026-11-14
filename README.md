# infrastructure-learning-lab

My 2027 path from software engineer to AI infrastructure, worked in public, one module at a time.

**Method:** learn → build → break → fix → document. A module is done when I can build, troubleshoot and reproduce it without the tutorial.

## Modules

| # | Topic | Build |
|---|---|---|
| 01 | Linux, terminal & Bash | A Linux production server: Nginx, systemd, SSH keys, deploy script |
| 02 | Networking | Web infrastructure lab: DNS, Nginx, several app instances |
| 03 | Backend engineering | Production FastAPI service |
| 04 | PostgreSQL, Redis & queues | FastAPI + Postgres + Redis + a worker |
| 05 | Docker | The whole stack containerised |
| 06 | AWS | Production AWS deployment |
| 07 | Terraform & CI/CD | The AWS stack in Terraform, deployed by GitHub Actions (Flagship 1) |
| 08 | Kubernetes | Kubernetes reliability platform |
| 09 | Observability & SRE | Prometheus, Grafana, OpenTelemetry, an incident report (Flagship 2) |
| 10 | Distributed systems | Design docs with trade-offs and failure modes |
| 11 | AI infrastructure | Serve a model with vLLM on a GPU and benchmark it |
| 12 | AI infra capstone | Production AI inference platform with benchmarks (Flagship 3) |

## Layout

- `month-XX-topic/` holds each module's labs, notes and troubleshooting log.
- `notes/` holds the weekly Log, one dated file per week (`log-001.md`, `log-002.md`, …).
