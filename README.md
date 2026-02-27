<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=32&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&width=600&lines=Badamasi+Aliu;Cloud+%26+DevOps+Engineer;I+build+infrastructure+that+ships." alt="Typing SVG" />
<br/>
Show Image
Show Image
Show Image
Show Image
</div>

What I actually do
I design and operate cloud infrastructure on AWS — the kind that handles real traffic, survives at 3am, and doesn't need a human to babysit it.
My current focus is building production-grade DevOps systems with Kubernetes, Terraform, and CI/CD pipelines that teams can trust. I hold a Certified Kubernetes Administrator (CKA) certification and have hands-on experience running EKS clusters, canary deployments, and multi-environment infrastructure from code.
I come from a background in electrical engineering + full-stack development, which means I think about systems end-to-end — not just the deployment layer.

The work (not just the list)
🏗️ KABAN — Production Microservices on AWS EKS

A full-stack Kanban board built as a vehicle to demonstrate every layer of a real DevOps pipeline.

This is not a tutorial project. It runs four separate Docker services — a FastAPI backend, Celery workers, a Next.js frontend, and a PostgreSQL database — deployed to AWS EKS with the following infrastructure:

Canary deployments with traffic splitting (40% canary / 60% stable) via Helm values
GitHub Actions CI/CD pipeline: build → push → Terraform apply → Helm deploy → DB migration → verification
CloudWatch log groups per service (/aws/eks/kaban-staging/backend, /celery, /frontend)
Terraform IaC for VPC, EKS cluster, RDS, Elasticache, S3 state backend, Secrets Manager
Zero-downtime migrations using Alembic with pre-deployment job hooks
Rollback strategy via helm rollback with revision history

📁 View Project →
Stack: Python/FastAPI · Next.js · PostgreSQL · Docker · Kubernetes · 
       Terraform · GitHub Actions · AWS EKS · CloudWatch · Helm · Celery

Infrastructure I'm comfortable with
yamlcloud:
  primary: AWS
  services: [EKS, EC2, RDS, S3, Lambda, VPC, IAM, CloudWatch, Secrets Manager, Elasticache]

containers:
  orchestration: Kubernetes (CKA Certified)
  runtime: Docker
  packaging: Helm

infrastructure_as_code:
  - Terraform
  - CloudFormation

ci_cd:
  - GitHub Actions
  - Docker Hub

languages:
  - Python (FastAPI, Boto3, Celery)
  - TypeScript / JavaScript (Next.js, Node.js)
  - Bash

databases:
  - PostgreSQL (RDS + Alembic migrations)
  - MongoDB
  - Firestore

monitoring:
  - CloudWatch (logs, alarms, dashboards)
  - Sentry

By the numbers
WhatResultCI/CD pipeline deployment timeReduced from hours → ~12 minutes automatedConcurrent users supported10,000+ (serverless backend, auto-scaling)Infrastructure setup time4 hours → 15 minutes with TerraformCanary traffic control40/60 split configurable per deployService uptime target99.9% across multi-AZ EKS setup

Certifications
CertificationIssuerYear✅ Certified Kubernetes Administrator (CKA)Linux Foundation2025✅ Cloud Developer NanodegreeUdacity2025🎓 B.Sc. Electrical & Electronics EngineeringObafemi Awolowo University2017

Background
I transitioned from electrical engineering into software, spent years building frontend and backend systems, then deliberately moved into cloud infrastructure because that's where I wanted to spend the next decade. That path means I can talk to developers, understand the application layer, and still own the infrastructure underneath it.
I'm currently open to remote DevOps / Cloud Engineering roles — contract or full-time — and I work well across time zones.
IELTS 7.5 — fluent written and spoken English.

Let's talk
If you're a recruiter, hiring manager, or engineer who wants to discuss infrastructure, cloud architecture, or an open role:
📧 Badamasi.link@gmail.com
💼 linkedin.com/in/badamasi-aliu

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=badex-ai&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D9FF&icon_color=00D9FF&text_color=FFFFFF" alt="GitHub Stats" />
<img src="https://github-readme-streak-stats.herokuapp.com?user=badex-ai&theme=tokyonight&hide_border=true&background=0D1117&ring=00D9FF&fire=00D9FF&currStreakLabel=00D9FF" alt="GitHub Streak" />
</div>
<div align="center">
<sub>Built real things. Broke real things. Fixed them. That's the job.</sub>
</div>
