# Hey, I'm Jaroslav
**Senior DevOps / Platform Engineer · Prague · Remote-first**
![Open to work](https://img.shields.io/badge/Open%20to-DevOps%20%2F%20Platform%20Engineer%20roles-brightgreen?style=flat-square)

---

Senior DevOps engineer with **10+ years** designing, automating, and operating cloud infrastructure — primarily on **AWS and Azure**. My core strength is **Infrastructure as Code and platform automation**, from IaC-driven onboarding workflows to modernising EKS infrastructure while keeping costs in check.

> I build systems that are *reproducible, modular, and boring in the best possible way.*

Recent work: Azure cost management and observability tuning at NIBE (~$4k/month saved on Application Insights across ~70 microservices), full EKS ownership (1.27 → 1.35, AL2 → AL2023, gp2 → gp3, killed a 100GB+/month memory leak) and a fully automated customer onboarding platform that cut provisioning from 5 days to minutes across AWS, Gandi DNS, Cassandra, and Confluent Cloud Kafka.

---

## 🛠 Core Stack

![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat-square&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-%235835CC.svg?style=flat-square&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-%23326ce5.svg?style=flat-square&logo=kubernetes&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-%231A1918.svg?style=flat-square&logo=ansible&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-%230072C6.svg?style=flat-square&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=flat-square&logo=docker&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-%23F46800.svg?style=flat-square&logo=grafana&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab%20CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-%232671E5.svg?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## 📌 Recent Highlights

| | |
|---|---|
| **~$4k/mo savings** | Reversed an Application Insights cost spike by tuning sampling across ~70 microservices (Azure) |
| **5 days → minutes** | Customer onboarding via Terraform (AWS, Gandi DNS, Cassandra, Kafka on Confluent Cloud) |
| **EKS 1.27 → 1.35** | Took over a cluster unmaintained for ~5 years: control plane, nodes (AL2 → AL2023), add-ons, Helm services |
| **$5–6k/mo savings** | AWS cost optimisation across EC2, RDS, S3, and NAT Gateway |
| **50× file size reduction** | Linux screen recording service rebuilt with systemd, FFmpeg & Ansible |
| **85% fewer security incidents** | Remediated 100+ high/critical vulnerabilities across AWS infrastructure |
| **30% AWS cost reduction** | Resource optimisation and decommissioning at Merkle |

---

## 🚀 Featured Project

**[wordpress](https://github.com/JaroVasak/wordpress)**: production multi-site WordPress hosting on a single Hetzner server, fully as code. Runs 4 sites for under €2 per site per month.

- Terraform + cloud-init provisioning, with a firewall that only accepts Cloudflare traffic
- Traefik with Cloudflare DNS-01 certificates; isolated Nginx/PHP-FPM containers per site on a shared MariaDB
- One-command site onboarding and backups; secrets injected at runtime, never stored in files
- Daily rollouts that test changes on one site first, with health checks and automatic rollback
- CI: ShellCheck, Terraform tests, config validation, Trivy scanning; Renovate for pinned dependency updates

---

## 💼 Recent Experience

- **Cloud DevOps Engineer · NIBE** (Aug 2026 – Nov 2026) — Azure cost management for a ~$1,000/day environment, Application Insights cost reduction, SRE & alert-quality work
- **Cloud DevOps Engineer · MERIM Digital** (May 2025 – Jul 2026) — Terraform onboarding platform, EKS ownership & upgrades, AWS cost optimisation plan
- **Cloud DevOps Engineer · Accenture** (Feb 2025 – Apr 2025) — large-scale Azure infrastructure with Terraform, Terragrunt & Azure DevOps
- **Cloud DevOps Engineer · Merkle** (Aug 2021 – Feb 2024) — security remediation, 30% AWS cost reduction, CI/CD from scratch

---

## 🎓 Certifications

- AWS Solutions Architect – Associate
- Azure Administrator Associate (AZ-104)
- Azure Fundamentals (AZ-900)
- CCNA Introduction to Networks

---

## 🌍 Find Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-jvasak-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/jvasak)
[![Website](https://img.shields.io/badge/Website-jvasak.com-000000?style=flat-square&logo=safari&logoColor=white)](https://jvasak.com)
[![Email](https://img.shields.io/badge/Email-jaro@jvasak.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:jaro@jvasak.com)

📍 Prague · Remote-first · CET timezone
