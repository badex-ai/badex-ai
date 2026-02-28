<div align="center">
Full Stack and Infrastructure Engineer
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/badamasi-aliu)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:badamasi.dev@gmail.com)
[![CKA](https://img.shields.io/badge/CKA_Certified-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)](https://www.credly.com/badges/07839cdc-5c80-4c9e-bb44-4e0772ee3d97)
[![Open to Work](https://img.shields.io/badge/Open_to_Work-Full_Time_/_Remote-00C853?style=for-the-badge)](mailto:badamasi.dev@gmail.com)
</div>

What I actually do
I build software end to end — UI interactions, the API layer behind them, and the infrastructure that keeps everything running. That full-stack-to-infrastructure range is where the interesting problems are, and it is what I have deliberately built my skills around.
My background spans frontend work in React and Next.js, backend services in Node.js and Python, and cloud infrastructure on AWS using Terraform and Kubernetes. I hold a Certified Kubernetes Administrator (CKA) certification and have shipped systems from the component level all the way to EKS cluster configuration, CI/CD pipelines, and production observability. I approach every project the same way: understand what it needs to do, build it properly, and write documentation that makes the work transferable.
I come from electrical engineering, which trained me to think about systems before writing a single line. That instinct has been useful at every level of the stack.

Selected Work
KABAN — Full Stack Microservices on AWS EKS

Next.js frontend. FastAPI backend. Celery workers. PostgreSQL. All of it running on Kubernetes, deployed through a real CI/CD pipeline.

This started as a Kanban board and became a full infrastructure exercise. The application itself is straightforward. What sits underneath it is not. Here is what is actually running:

Canary deployments with 40/60 traffic splitting between stable and canary frontend builds, configured via Helm values and switchable per deploy
GitHub Actions pipeline that runs build, Terraform apply, Helm deploy, database migration, and deployment verification in sequence — triggered by a single git push
Terraform IaC covering VPC, EKS cluster, RDS, Elasticache, S3 remote state backend, and Secrets Manager — infrastructure comes up from code, not clicks
CloudWatch observability with dedicated log groups per service: backend, Celery workers, and both frontend variants
Zero-downtime database migrations using Alembic, wired into the pipeline as a pre-deploy job so migrations run before traffic shifts
Helm rollback strategy with full revision history — one command to recover from a bad deploy

📁 View Project →
Stack: Next.js · TypeScript · Python/FastAPI · PostgreSQL · Celery · Docker
       Kubernetes · Helm · Terraform · GitHub Actions · AWS EKS · CloudWatch

BrightData MCP + LangChain — AI Data Pipeline

Integrated Bright Data's MCP server with LangChain to build an AI-driven data retrieval and processing pipeline.

This project connects a live data source via Bright Data's MCP protocol to a LangChain agent, enabling structured web data extraction driven by natural language. It is a practical integration of two tools that are becoming standard in production AI workflows.
📁 View on GitHub →
Stack: Python · LangChain · Bright Data MCP · LLM integration

Lendsqr — Fintech Dashboard (Frontend)

Responsive dashboard application for a lending platform, built to a real design specification with data tables, filtering, and user management.

This was a frontend technical assessment that I treated like a production deliverable. The focus was clean component architecture in TypeScript, pixel-accurate implementation from Figma, and a data layer that handles large user tables efficiently without a backend dependency.
📁 View on GitHub →
Stack: ReactJS · TypeScript · SCSS · React Router · Figma

ApartmentCheq — REST API

Backend API for an apartment review platform. Node.js, Express, and PostgreSQL with authentication, CRUD operations, and a rating system.

Built with proper indexing strategies and a Jest test suite — structured for maintainability, not just to ship.
📁 View on GitHub →
Stack: Node.js · Express · PostgreSQL · Jest

What I work with
yamlfrontend:
  - React, Next.js, TypeScript, JavaScript
  - Tailwind CSS, CSS3, HTML5
  - Redux, React Context

backend:
  - Node.js, Express, RESTful APIs
  - Python, FastAPI, Celery
  - WebRTC, Socket.io

infrastructure:
  - Terraform IaC: VPC, EKS cluster, RDS, Elasticache, S3 state backend, Secrets Manager
  - Kubernetes (CKA Certified): networking, workloads, Helm, cluster operations
  - Docker, Docker Compose, multi-environment compose configs
  - GitHub Actions CI/CD pipelines
  - AWS: EKS, EC2, RDS, S3, Lambda, IAM, CloudWatch, Secrets Manager, Elasticache

scripting:
  - Bash
  - Python Boto3 for AWS automation

databases:
  - PostgreSQL (RDS, Alembic migrations)
  - MongoDB, Firestore

monitoring:
  - CloudWatch: logs, alarms, dashboards
  - Sentry

ai_and_agents:
  - LangChain, MCP integrations, LLM-connected pipelines

operating_systems:
  - Linux (primary)

Certifications
CertificationIssuerCertified Kubernetes Administrator (CKA)Linux FoundationCloud Developer NanodegreeUdacityB.Sc. Electrical and Electronics EngineeringObafemi Awolowo University
English: fluent written and spoken. IELTS Academic band 7.5.

Availability
Open to full-time remote roles. Available between 08:00 and 22:00 UTC, which covers US Eastern through Pacific working hours comfortably.

Let's talk
📧 badamasi.dev@gmail.com
💼 linkedin.com/in/badamasi-aliu

<div align="center">
<sub>Built real things. Broke real things. Fixed them. That's the job.</sub>
</div>
