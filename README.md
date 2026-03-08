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

### 🧠 linux-ai-cmd — DevOps AI Troubleshooting Assistant
*Shell · Bash · OpenAI API · Linux · 2025* &nbsp; [![Repo](https://img.shields.io/badge/GitHub-linux--ai--cmd-black?style=flat&logo=github)](https://github.com/Shubham-Bhayaje/linux-ai-cmd)

- Built a terminal-native AI assistant for Linux/DevOps troubleshooting — ask questions, explain commands, fix errors, generate Bash commands, analyze logs, and diagnose system issues directly from the CLI.
- Integrates AI with real Linux system context, making it a practical daily tool for sysadmins and DevOps engineers.

---

### 📸 Event — Facial Recognition Photo Manager
*Python · Facial Recognition · QR Code · AWS · 2025* &nbsp; [![Repo](https://img.shields.io/badge/GitHub-Event-black?style=flat&logo=github)](https://github.com/Shubham-Bhayaje/Event)

- Built a web app for event admins to upload photos and auto-generate QR codes per event; attendees scan the QR code and the app uses **facial recognition** to surface only their own photos.
- End-to-end pipeline: photo upload → face detection → attendee matching → personalized download — no manual filtering needed.

---

### 🔍 CodeView — Python Code Visualizer
*Python · Educational Tool · 2025* &nbsp; [![Repo](https://img.shields.io/badge/GitHub-CodeView-black?style=flat&logo=github)](https://github.com/Shubham-Bhayaje/CodeView)

- Developed an educational tool that executes Python code **line by line**, visually showing variable states, output, and execution flow in real time.
- Designed to help beginners understand exactly how Python programs run — making abstract code behaviour concrete and interactive.

---

### 🎙️ VoxScript — Voice-to-Code Assistant
*Python · OpenAI GPT-4o · Speech Recognition · 2025* &nbsp; [![Repo](https://img.shields.io/badge/GitHub-VoxScript-black?style=flat&logo=github)](https://github.com/Shubham-Bhayaje/VoxScript)

- Built a voice-activated assistant that converts spoken natural language into executable Python code using OpenAI's GPT-4o.
- Speak your intent — VoxScript transcribes, interprets, generates, and runs functional Python programs in real time.

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

![Shubham's GitHub stats](https://github-readme-stats.vercel.app/api?username=Shubham-Bhayaje&show_icons=true&theme=radical&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Shubham-Bhayaje&layout=compact&theme=radical&hide_border=true&langs_count=8)

![GitHub Streak](https://streak-stats.demolab.com?user=Shubham-Bhayaje&theme=radical&hide_border=true)

---

> *"Build systems that scale, secure what matters, and automate everything in between."* 🚀
