# DevOps Mastery Roadmap (Full Syllabus)

## ✪ Phase 1: Core Foundations (Weeks 1–4)

> “Be the engineer who understands the why behind every command.”

### 🔧 Linux Mastery

* File system hierarchy
* File permissions, ACLs
* Process management (`ps`, `top`, `htop`, `kill`)
* Networking tools: `netstat`, `ss`, `curl`, `telnet`, `traceroute`, `dig`
* `systemd`, services, cron jobs
* Disk usage, logs, system monitoring

### 🔧 Bash & Scripting

* Variables, loops, functions
* Conditionals and piping
* File handling
* Writing scripts for health checks, backup, automation

### 🔧 Git & GitHub/GitLab

* Init, clone, commit, push, pull, stash
* Branching strategies
* Rebasing, merging
* GitHub Actions basics
* Webhooks & PR workflows

### 🔧 Docker

* Docker architecture, engine, registries
* Build images, Dockerfiles (multi-stage)
* Volumes, networks, linking containers
* Docker Compose
* Docker Hub, private registries

### 🔧 Jenkins (CI/CD Basics)

* Install Jenkins via Docker
* Build freestyle + pipeline jobs
* Parameters, artifacts, environment variables
* Git integration
* Trigger builds (poll SCM, webhook)
* Post-build actions

---

## ✪ Phase 2: DevOps Practitioner (Weeks 5–10)

> “Automate it all. Scale with confidence.”

### ⚙️ Infrastructure as Code – Terraform

* Providers, resources, variables
* EC2, VPC, SG, S3, IAM basics
* Output, locals, modules
* Remote state
* Terraform Cloud or S3 + DynamoDB state locking

### ⚙️ Configuration Management – Ansible

* Playbooks, roles, tasks, inventories
* SSH key-based automation
* Loops, conditionals
* Ansible Vault
* Use cases: user provisioning, package install, app deploy

### ⚙️ Kubernetes Essentials

* K8s architecture: nodes, pods, services, etcd, kubelet
* kubectl basics: get, describe, logs, exec
* Deployments, ReplicaSets, Services
* ConfigMaps, Secrets, Volumes
* Ingress controllers

### ⚙️ CI/CD with Jenkins + Kubernetes

* Jenkinsfile pipelines with stages
* Docker build & push in Jenkins
* Deploy to Kubernetes via Jenkins
* Blue-green / rolling deployments

---

## ✪ Phase 3: Observability & Reliability (Weeks 11–14)

> “If you can’t measure it, you can’t trust it.”

### 📊 Monitoring

**Prometheus**:

* Install via Helm
* Node Exporter, kube-state-metrics

**Grafana**:

* Dashboards for CPU, memory, pod health
* Alerts and notifications

### 📊 Logging

**Loki** or **ELK Stack (Elasticsearch, Logstash, Kibana)**:

* Fluentd or Fluent Bit log shipping
* Centralized logs from containers and apps

### 📊 GitOps with ArgoCD

* Install ArgoCD in cluster
* Sync Git to K8s deployments
* Self-healing deployments
* Rollback, application sets

---

## ✪ Phase 4: Cloud Native & DevOps at Scale (Weeks 15–20)

> “Design platforms, not pipelines.”

### ☁️ AWS Deep Dive (for DevOps)

* IAM (roles, policies)
* EC2, VPC, NAT, IGW, ELB
* S3, EFS, CloudWatch
* RDS, Route53, Lambda (basics)
* CloudFormation vs Terraform

### ☁️ Helm (K8s App Packaging)

* Chart structure
* Values.yaml, templating
* Helm repos
* Using Helm in pipelines

### ☁️ Security in DevOps

* Docker and K8s hardening
* Secrets Management (Vault, Sealed Secrets)
* SSH key & credential handling
* SAST (SonarQube), DAST, SCA tools

### ☁️ Platform Engineering Concepts

* What is an Internal Developer Platform?
* Backstage (by Spotify)
* Developer self-service
* Golden paths, reusable pipelines

---

## ✪ Phase 5: Mastery & Certification Prep (Weeks 21–24)

> “Be interview- and promotion-ready.”

### 📘 Certification Paths (Optional)

* AWS Certified DevOps Engineer – Pro
* Kubernetes CKA / CKAD
* Terraform Associate
* GitLab/Jenkins Certification

### 📘 Portfolio Projects

* Jenkins + Docker + Kubernetes CI/CD
* Terraform AWS infra + ArgoCD
* Prometheus-Grafana observability
* Helm + secure secret management
* Add architecture diagrams, README, videos

### 📘 Mock Interviews + Resume Building

* System design for DevOps
* Resume with projects + GitHub + blog links
* LinkedIn profile polish
* Salary negotiation practice

---

## 📊 Weekly Tracker

* Can be created as: Notion board / Google Sheet / Markdown file

---

## 🧐 Optional Add-Ons

* AI + DevOps (ChatOps, AI tools for infra)
* FinOps (Cloud cost optimization)
* DevSecOps (Security baked into pipelines)
* Service Mesh (Istio, Linkerd)

---

> Ready to kick off **Week 1** with daily goals and links?
