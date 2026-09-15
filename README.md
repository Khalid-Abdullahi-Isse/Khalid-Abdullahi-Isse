<div align="center">

<img src="./assets/hero-engineering.svg" width="100%" />

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=25&duration=2300&pause=700&color=38BDF8&center=true&vCenter=true&repeat=true&width=950&lines=Software+Engineer+%7C+Backend+Engineering;Designing+Scalable+Distributed+Systems;Go+%E2%80%A2+Microservices+%E2%80%A2+PostgreSQL+%E2%80%A2+Redis;Docker+%E2%80%A2+Kubernetes+%E2%80%A2+Helm+%E2%80%A2+ArgoCD;Architecture+%E2%86%92+Automation+%E2%86%92+Production" />

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=Khalid-Abdullahi-Isse&style=for-the-badge&color=0ea5e9&label=PROFILE+VIEWS" />

<img src="https://img.shields.io/github/followers/Khalid-Abdullahi-Isse?style=for-the-badge&logo=github&label=FOLLOWERS&color=111827" />

</div>

---

# ⚡ Software Engineer


I focus on designing and engineering **production-oriented systems** rather than simply building isolated features.

My work combines:

`Backend Engineering` • `System Architecture` • `Databases` • `Security` • `DevOps` • `Cloud` • `Automation`

---

<div align="center">

# 🛠️ Tech Stack

## 💻 Programming Languages

<p align="center">
  <img src="https://skillicons.dev/icons?i=go,ts,js,python,c&theme=dark" />
</p>

---

## 🖥️ Backend Engineering

<p align="center">
  <img src="https://skillicons.dev/icons?i=go,nestjs,nodejs&theme=dark" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Gin-008ECF?style=for-the-badge&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/REST_API-111827?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Odoo-714B67?style=for-the-badge&logo=odoo&logoColor=white" />
</p>

---

## 🌐 Frontend Development

<p align="center">
  <img src="https://skillicons.dev/icons?i=nextjs,react,tailwind,html,css&theme=dark" />
</p>

---

## 🗄️ Databases & Caching

<p align="center">
  <img src="https://skillicons.dev/icons?i=postgres,mongodb,redis&theme=dark" />
</p>

---

## ☁️ DevOps & Infrastructure

<p align="center">
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,linux,nginx,git,github,githubactions&theme=dark" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white" />
  <img src="https://img.shields.io/badge/Argo_CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white" />
</p>

---

## ⚙️ Core Engineering Skills

<p align="center">
  <img src="https://img.shields.io/badge/Microservices-111827?style=for-the-badge" />
  <img src="https://img.shields.io/badge/System_Design-111827?style=for-the-badge" />
  <img src="https://img.shields.io/badge/REST_APIs-111827?style=for-the-badge" />
  <img src="https://img.shields.io/badge/JWT_Authentication-111827?style=for-the-badge" />
  <img src="https://img.shields.io/badge/RBAC-111827?style=for-the-badge" />
  <img src="https://img.shields.io/badge/CI%2FCD-111827?style=for-the-badge" />
</p>

# 🧬 System Architecture

<img src="./assets/architecture-flow.svg" width="95%" />

</div>

```text
                         CLIENTS
                            │
                            ▼
                    ┌───────────────┐
                    │ API / Ingress │
                    └───────┬───────┘
                            │
             ┌──────────────┼───────────────┐
             │              │               │
             ▼              ▼               ▼
        Auth Service    Core Service    Event Service
             │              │               │
             └──────┬───────┴──────┬────────┘
                    │              │
                    ▼              ▼
               PostgreSQL        Redis
                    │
                    ▼
                Monitoring
                    │
                    ▼
        Docker → Kubernetes → Helm
                    │
                    ▼
                 Argo CD
                    │
                    ▼
                Production
```

---

<div align="center">

# 💎 Featured Engineering Systems

### Advanced production-oriented projects

<img src="./assets/project-divider.svg" width="90%" />

</div>

<br/>

<div align="center">

<img src="./assets/nexora-glow.svg" width="95%" />

</div>

## 🌐 Nexora — Distributed Social Platform

> **Go • Gin • PostgreSQL • Redis • Microservices • Docker • Kubernetes • Helm • Argo CD**

Nexora is a distributed backend system designed around independent services, production deployment, secure communication and scalable infrastructure.

### Architecture

```text
                         USERS
                           │
                           ▼
                    ┌──────────────┐
                    │   Ingress    │
                    └──────┬───────┘
                           │
          ┌────────────────┼─────────────────┐
          │                │                 │
          ▼                ▼                 ▼
    Auth Service      Post Service      Chat Service
          │                │                 │
          │                │          Notification
          │                │              Service
          │                │                 │
          └─────────┬──────┴───────┬─────────┘
                    │              │
                    ▼              ▼
                PostgreSQL       Redis
                    │              │
                    └──────┬───────┘
                           ▼
                        Docker
                           │
                           ▼
                     Kubernetes
                           │
                           ▼
                         Helm
                           │
                           ▼
                       Argo CD
                           │
                           ▼
                      Production
```

### Engineering

⚡ Microservice architecture
⚡ JWT access & refresh token architecture
⚡ Role-based authorization
⚡ Resource ownership validation
⚡ PostgreSQL persistence
⚡ Redis caching
⚡ Distributed rate limiting
⚡ Docker containerization
⚡ Kubernetes orchestration
⚡ Helm deployments
⚡ Argo CD GitOps
⚡ CI/CD automation
⚡ Secure service boundaries

<br/>

<div align="center">

<img src="./assets/pulse-line.svg" width="70%" />

</div>

---

<div align="center">

<img src="./assets/hotel-erp-glow.svg" width="95%" />

</div>

## 🏨 Enterprise Hotel ERP

A full operational ERP designed around the workflows of real hotels rather than simple CRUD operations.

### Core Systems

```text
Reservations
      │
      ├────► Room Availability
      │
      ├────► Front Desk
      │
      ├────► Housekeeping
      │
      ├────► Charges
      │
      ├────► Payments
      │
      └────► Accounting
                    │
                    ▼
              General Ledger
                    │
           ┌────────┼────────┐
           ▼        ▼        ▼
      Trial Balance P&L Balance Sheet
```

### Platform Capabilities

⚡ Reservation lifecycle
⚡ Room inventory
⚡ Front desk operations
⚡ Housekeeping workflows
⚡ Maintenance management
⚡ Expenses
⚡ Payments
⚡ Double-entry accounting
⚡ General ledger
⚡ Trial balance
⚡ Balance sheet
⚡ Financial reports
⚡ Audit logging
⚡ RBAC
⚡ PostgreSQL transactions
⚡ Redis caching
⚡ Rate limiting
⚡ Secure API architecture
⚡ Docker deployment
⚡ CI/CD pipelines

<br/>

<div align="center">

<img src="./assets/pulse-line.svg" width="70%" />

</div>

---

<div align="center">

<img src="./assets/medical-erp-glow.svg" width="95%" />

</div>

## 🏥 Medical Import & Distribution ERP

Enterprise workflow system designed for medical importing, wholesale and retail operations.

### Supply Chain

```text
PURCHASE ORDER
      │
      ▼
INTERNATIONAL SHIPMENT
      │
      ▼
   IN TRANSIT
      │
      ▼
CUSTOMS CLEARANCE
      │
      ▼
  QUARANTINE
      │
      ▼
QUALITY CONTROL
      │
      ▼
   RELEASE
      │
      ▼
  INVENTORY
      │
      ├───────────────┐
      ▼               ▼
  WHOLESALE         RETAIL
      │               │
      └───────┬───────┘
              ▼
          ACCOUNTING
              │
              ▼
           REPORTING
```

### Business Engineering

⚡ Procurement
⚡ Supplier management
⚡ International shipping
⚡ Customs workflow
⚡ Quarantine
⚡ Quality control
⚡ Inventory
⚡ Sales
⚡ Wholesale operations
⚡ Retail operations
⚡ Accounting
⚡ Reporting
⚡ Workflow automation

---

<div align="center">

# 🔐 Backend Engineering

<img src="./assets/security-motion.svg" width="90%" />

</div>

```text
Request
   │
   ▼
Rate Limiter
   │
   ▼
Authentication
   │
   ▼
JWT Validation
   │
   ▼
Role Authorization
   │
   ▼
Ownership Validation
   │
   ▼
DTO / Payload Validation
   │
   ▼
Business Logic
   │
   ▼
Database Transaction
   │
   ▼
Audit Logging
   │
   ▼
Response
```

### Core Areas

`Authentication`

`Authorization`

`JWT + Refresh Tokens`

`RBAC`

`Ownership Validation`

`Rate Limiting`

`Redis`

`Transactions`

`Audit Logs`

`Pagination`

`Caching`

`API Versioning`

`Validation`

`Error Handling`

`Observability`

---

<div align="center">

# 🚀 Delivery Pipeline

<img src="./assets/devops-pipeline.svg" width="95%" />

</div>

```text
Developer
    │
    ▼
   Git
    │
    ▼
 GitHub
    │
    ▼
GitHub Actions
    │
    ├──── Test
    ├──── Build
    ├──── Security
    └──── Docker
            │
            ▼
       Container Registry
            │
            ▼
           Helm
            │
            ▼
         Argo CD
            │
            ▼
       Kubernetes
            │
            ▼
        Production
```

---

# 📊 Engineering Activity

<div align="center">

<img height="185" src="https://github-readme-stats.vercel.app/api?username=Khalid-Abdullahi-Isse&show_icons=true&theme=transparent&hide_border=true&title_color=38BDF8&icon_color=22D3EE&text_color=C9D1D9" />

<img height="185" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Khalid-Abdullahi-Isse&layout=compact&theme=transparent&hide_border=true&title_color=38BDF8&text_color=C9D1D9" />

</div>

<br/>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Khalid-Abdullahi-Isse&theme=transparent&hide_border=true" />

</div>

---

# 📈 Contribution Flow

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Khalid-Abdullahi-Isse&bg_color=00000000&color=38BDF8&line=22D3EE&point=FFFFFF&area=true&hide_border=true" width="97%" />

</div>

---

# 🐍 Contribution Animation

<div align="center">

<img src="https://raw.githubusercontent.com/Khalid-Abdullahi-Isse/Khalid-Abdullahi-Isse/output/github-contribution-grid-snake-dark.svg" width="100%" />

</div>

---

<div align="center">

# 🧠 Engineering Direction

<img src="./assets/neural-divider.svg" width="75%" />

</div>

```yaml
backend:
  primary_language: Go

  architecture:
    - Distributed Systems
    - Microservices
    - Event Driven Architecture
    - API Architecture

systems:
  - Linux
  - RHCSA
  - RHCE

infrastructure:
  - Docker
  - Kubernetes
  - Helm
  - Argo CD

data:
  - PostgreSQL
  - Redis

cloud:
  - AWS
  - Cloud Architecture

engineering:
  - System Design
  - Performance
  - Reliability
  - Security
  - Observability
```

---

<div align="center">

# 🌐 Connect With Me

<a href="YOUR_LINKEDIN_URL">
<img src="https://img.shields.io/badge/LinkedIn-Khalid_Abdullahi_Isse-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

 

<a href="mailto:YOUR_EMAIL">
<img src="https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

 

<a href="https://github.com/Khalid-Abdullahi-Isse">
<img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

<br/><br/>

<img src="./assets/footer-motion.svg" width="100%" />

### `ARCHITECTURE → RELIABILITY → AUTOMATION → SCALE`

**Engineering systems built for real users and real businesses.**

</div>
