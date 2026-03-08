# Hi 👋, I'm Shubham Bhayaje

### DevOps & Cloud Engineer | Linux & Unix Systems Engineer | AWS Certified | RHCE

I'm a passionate DevOps & Cloud Engineer from Thane, Maharashtra 🇮🇳, specializing in AWS infrastructure automation, CI/CD pipelines, containerization, and deep RHEL system administration. RHCE-certified with hands-on mastery of SELinux, firewalld, systemd, and multi-host Ansible automation. I also bring a GRC perspective — understanding security controls, audit requirements, and compliance frameworks that production systems must satisfy.

---

## 🔗 Connect with Me

[![Email](https://img.shields.io/badge/Email-shubhambhayaje911@gmail.com-red?style=flat&logo=gmail)](mailto:shubhambhayaje911@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-shubham--bhayaje-blue?style=flat&logo=linkedin)](https://linkedin.com/in/shubham-bhayaje)
[![Website](https://img.shields.io/badge/Website-shubhambhayaje.in-green?style=flat&logo=google-chrome)](https://shubhambhayaje.in)
[![GitHub](https://img.shields.io/badge/GitHub-Shubham--Bhayaje-black?style=flat&logo=github)](https://github.com/Shubham-Bhayaje)

---

## 🏅 Certifications

| Certification | Issuer | Valid |
|---|---|---|
| 🏆 AWS Certified Solutions Architect – Associate *(Score: 792/1000)* | Amazon Web Services | Feb 2026 – Feb 2029 |
| 🎖️ Red Hat Certified Engineer (RHCE – EX294) | Red Hat | Feb 2026 – Feb 2030 |
| 🧠 Deep Learning Specialization | Stanford / DeepLearning.AI (Andrew Ng) | 2024 |

---

## 🛠️ Technical Skills

### 🐧 Linux & Unix Systems
![RHEL](https://img.shields.io/badge/-RHEL_8/9-EE0000?style=flat&logo=redhat&logoColor=white)
![Ubuntu](https://img.shields.io/badge/-Ubuntu-E95420?style=flat&logo=ubuntu&logoColor=white)
![CentOS](https://img.shields.io/badge/-CentOS-262577?style=flat&logo=centos&logoColor=white)
![Debian](https://img.shields.io/badge/-Debian-A81D33?style=flat&logo=debian&logoColor=white)

- **System Administration:** Kernel tuning, process management, user/group management
- **OS Hardening:** SELinux (enforcing/permissive/targeted), firewalld, iptables, PAM, SSH hardening, auditd, fail2ban
- **Service Management:** systemd — unit files, service supervision, zero-downtime restarts, journald
- **Storage & DB:** LVM, filesystem management, PostgreSQL, MySQL, Redis

### ☁️ Cloud & AWS
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat&logo=amazon-aws)
![EC2](https://img.shields.io/badge/-EC2-FF9900?style=flat&logo=amazon-ec2&logoColor=white)
![S3](https://img.shields.io/badge/-S3-569A31?style=flat&logo=amazon-s3&logoColor=white)
![Lambda](https://img.shields.io/badge/-Lambda-FF9900?style=flat&logo=aws-lambda&logoColor=white)

`EC2` `RDS` `S3` `IAM` `Lambda` `API Gateway` `CloudWatch` `SES` `SQS` `EKS` `VPC` `LightSail` `CloudFront`

**Networking:** TCP/IP, DNS, DHCP, Nginx (reverse proxy, virtual hosts, SSL/TLS), routing

### ⚙️ DevOps & IaC
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/-Jenkins-D24939?style=flat&logo=jenkins&logoColor=white)
![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/-Ansible-EE0000?style=flat&logo=ansible&logoColor=white)
![Nginx](https://img.shields.io/badge/-Nginx-009639?style=flat&logo=nginx&logoColor=white)

### 📊 Automation, Scripting & Monitoring
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=flat&logo=grafana&logoColor=white)

- **Automation:** Ansible (playbooks, roles, Vault, inventories), Bash scripting, Python automation, Cron, systemd timers
- **Scripting:** Bash, Python, YAML, SQL
- **Monitoring:** Prometheus, Grafana, AWS CloudWatch — metrics, alerts, log analysis, dashboards

### 🔒 Security & GRC
`ITGC Audits` `IAM Roles` `Least Privilege` `Security Groups` `SAP Access Management`

---

## 🚀 Projects

### 🖥️ Linux Server Infrastructure — DropXCult Production Deployment
*AWS LightSail · RHEL/Ubuntu · Nginx · Redis · PostgreSQL · SSL/TLS · systemd · Bash · 2024*

- Provisioned and hardened multi-app Linux server: OS install, partition layout, user mgmt, firewalld/iptables, SSH key-only auth, and fail2ban for brute-force protection.
- Configured Nginx reverse proxy with SSL/TLS (Let's Encrypt), virtual host routing, and upstream load balancing; tuned worker processes for production load.
- Deployed Redis caching layer; automated deployments via Bash + systemd unit files; cron backups — achieved **96% reduction** in repeat-load asset delivery times via Service Worker caching.

---

### 🤖 Multi-Host Ansible Automation & Linux Hardening
*Ansible · RHEL · SELinux · firewalld · systemd · Bash · SSH · 2024*

- Built Ansible playbooks and roles for full Linux provisioning across RHEL/CentOS hosts: packages, user creation, SSH key distribution, sudoers, and SELinux targeted-mode enforcement.
- Automated firewalld zones/services/ports via idempotent Ansible tasks; used Vault for secrets; structured with roles, handlers, and Jinja2 templates for environment-aware automation.
- Configured systemd service units with dependency ordering, restart policies, and resource limits (CPUQuota, MemoryMax) for production application lifecycle management.

---

### 🔄 CI/CD Pipeline — Django App on AWS
*Jenkins · AWS EC2 · systemd · Gunicorn · Nginx · Git · 2024*

- Designed end-to-end Jenkins CI/CD pipeline automating build, test, and deploy to EC2 — **eliminated 100% of manual steps**, cutting release cycle time by ~70%.
- Managed app lifecycle with systemd + Gunicorn for zero-downtime restarts; Nginx reverse proxy with upstream load balancing and process supervision.

---

### ⚡ Event-Driven Notification System — Serverless on AWS
*AWS Lambda · API Gateway · SQS · SES · Terraform · 2024*

- Architected serverless pipeline: API Gateway → Lambda → SQS → SES with dead-letter queue; **100% Terraform IaC** — reproducible, version-controlled, zero manual clicks.
- Achieved auto-scaling with zero idle cost; Lambda cold-start optimized for sub-200ms; AWS Well-Architected principles applied throughout.

---

## 💼 Experience

**IT Risk & Compliance Analyst (GRC)** — *Avenue Supermarts Ltd (D-Mart)*
`Aug 2024 – Present` | Thane, Maharashtra | Full-time, On-site

- Performed ITGC audits across SAP and POS systems covering access management, change management, and operational controls for enterprise-scale Linux/Unix production environments.
- Reviewed and validated user access provisioning/de-provisioning workflows, enforcing least-privilege across **1,000+ accounts** — directly applicable to Linux PAM, sudoers, and IAM configuration.
- Coordinated with infrastructure teams to analyze system configs, audit logs, and control evidence — deepening expertise in auditd, syslog, and security-level log management.

---

## 🎓 Education

**B.Sc. in Computer Science** — K V Pendharkar College, Mumbai University
`Jun 2021 – Apr 2024` | Thane, Maharashtra

---

## 📈 GitHub Stats

![Shubham's GitHub stats](https://github-readme-stats.vercel.app/api?username=Shubham-Bhayaje&show_icons=true&theme=radical)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Shubham-Bhayaje&layout=compact&theme=radical)

---

> *"Build systems that scale, secure what matters, and automate everything in between."* 🚀
