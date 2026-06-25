<div align="center">

# 👋 Hey, I'm Abo Morad

### Junior Cloud Engineer · Linux SysAdmin at Heart · Infrastructure Enthusiast

*"If it's not automated, it's not done yet."*

</div>

---

## 🧠 About Me

I'm a Junior Cloud Engineer who comes from a **SysAdmin background** — which means I think about infrastructure the way an ops person does: stability first, automation always, and never trust a system you can't monitor.

I work at the intersection of **Linux systems**, **cloud infrastructure**, and **DevOps tooling** — building environments that are reproducible, observable, and (hopefully) don't wake anyone up at 3 AM.

- 🐧 Started with Linux administration, now living in the cloud
- 🏗️ Obsessed with turning manual runbooks into automated pipelines
- 📦 Currently leveling up on **Kubernetes** and **Terraform** at scale
- 🔍 Strong believer in: *if it's not in code, it doesn't exist*

---

## 🛠️ Tech Stack & Tools

### ☁️ Cloud & Infrastructure
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=FF9900)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)

### 🐧 OS & Scripting
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### 📦 Containers & Orchestration
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

### ⚙️ CI/CD & Automation
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)

### 📊 Monitoring & Observability
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

---

## 🏗️ Architecture & Mindset

Coming from SysAdmin roots, I approach cloud infrastructure with a few core principles:

```
Reliability   >   Speed of delivery
Automation    >   Manual intervention
Observability >   Assumptions
Least Privilege >  Convenience
```

**My typical workflow on any new system:**

1. Understand the failure modes before anything else
2. Write the infra as code (Terraform), not as clicks
3. Add monitoring before going live — not after the first incident
4. Automate the runbook into a pipeline
5. Document what *actually* happened, not what was supposed to happen

---

## 📁 What You'll Find in My Repos

| Type | Description |
|------|-------------|
| 🏗️ **IaC templates** | Reusable Terraform modules for AWS (VPC, EKS, IAM, etc.) |
| 🔧 **Bash scripts** | SysAdmin automation — user management, log rotation, health checks |
| 🚀 **CI/CD pipelines** | GitLab CI templates for build → test → deploy workflows |
| 📊 **Observability configs** | Prometheus rules, Grafana dashboards, alerting setups |
| 🐳 **Docker/K8s manifests** | Compose files, Helm values, and K8s YAML examples |

---

## 🤝 Contributing

Found something useful? Have a fix or improvement?

1. **Fork** the repo you want to contribute to
2. Create a branch: `git checkout -b fix/your-fix-name`
3. Make your changes — keep commits atomic and descriptive
4. Open a **Merge Request** with context on *why*, not just *what*
5. I review MRs with a SysAdmin lens: *will this break at 2 AM?*

> ⚠️ For infra-related changes, always include a `terraform plan` output or a dry-run result in the MR description.

---

## 🐛 Troubleshooting & FAQs

**Q: Why are your Terraform modules structured this way?**
> SysAdmin habit — I separate environments (dev/staging/prod) at the folder level, not just via variables. Blast radius control.

**Q: Why Ansible *and* Terraform? Isn't that overlap?**
> Terraform owns the *what* (infra provisioning). Ansible owns the *how* (config management on existing machines). Different jobs, different tools.

**Q: Your GitLab CI pipelines have a lot of manual gates — why?**
> Because I've seen automated pipelines push bad code to prod at midnight. Manual approval on prod deploys is a feature, not a limitation.

**Q: Something in your repo broke on my setup — what do I do?**
> Open an issue with: your OS, tool versions, the exact command you ran, and the full error output. The more context, the faster the fix.

---

<div align="center">

*Built with a SysAdmin mindset — because clouds are just someone else's Linux servers.*

</div>
