# 🎮 CraftOps

> Minecraft server infrastructure on AWS — from manual setup to full automation with Terraform, Ansible, and observability.

## 📖 About

Personal project to run a Minecraft Java Edition server on AWS, built progressively from manual setup to a fully automated, monitored infrastructure. The goal is to apply and document real-world cloud and DevOps practices in a hands-on environment.

## 🏗️ Architecture

> Architecture diagram will be added as the project evolves.

## 🛠️ Stack

- **Cloud:** AWS (EC2, EBS, Elastic IP, Security Groups, Lambda, EventBridge, CloudWatch)
- **OS:** Ubuntu Server 24.04 LTS
- **Game:** Minecraft Java Edition (Vanilla)
- **IaC:** Terraform
- **Configuration:** Ansible
- **Observability:** CloudWatch / Prometheus + Grafana (TBD)

## 📂 Structure

```
craftops/
├── terraform/        # Infrastructure as Code
├── ansible/          # Configuration management
├── docs/             # Documentation and diagrams
└── scripts/          # Utility scripts
```

## 📋 Prerequisites

- AWS account with IAM user (AdministratorAccess + MFA)
- AWS CLI configured
- Terraform installed
- Ansible installed

## 📄 License

MIT