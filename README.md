# Hey, I'm Jahnreil Amarillento 👋

### `Backend Engineer` · `Platform / Infrastructure` · `AI Engineering`

> I build backend systems, deploy infrastructure, and automate things
> that I'd rather not do manually.

[![Portfolio](https://img.shields.io/badge/Portfolio-projects.mafunami.me-0f172a?style=for-the-badge&logo=googlechrome&logoColor=white)](https://projects.mafunami.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Jahnreil%20Amarillento-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jahnreilamarillento)
[![Email](https://img.shields.io/badge/Email-amarillentojahnreil%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:amarillentojahnreil@gmail.com)

---

## `$ whoami`

I'm an **Information Technology student at Mapúa University** focused on
backend engineering, platform infrastructure, AI systems, and automation.

I like working on problems where software goes beyond "making the app work":

- designing APIs and backend services
- building and deploying infrastructure
- running services on Linux
- automating repetitive workflows
- experimenting with AI systems
- breaking things in my homelab and figuring out why

---

## `> tech_stack`

### Backend

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)

### Infrastructure

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![OpenWrt](https://img.shields.io/badge/OpenWrt-00B5E2?style=flat-square&logo=openwrt&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=flat-square&logo=tailscale&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)

### Databases & Tools

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

### AI / ML

`LLMs` · `ReAct Agents` · `RAG` · `Computer Vision` · `YOLOv5` · `OCR`

---

## `// featured_projects`

### 🎮 2Phishy

**Gamified Cybersecurity Awareness Platform**

> My thesis project — an adaptive cybersecurity learning platform combining
> game mechanics with personalized assessments.

**Stack:** `React` `TypeScript` `Phaser 3` `FastAPI` `PostgreSQL`
`MongoDB` `Redis` `Docker`

- Adaptive learning algorithm based on learner performance
- Dynamic topic and question generation
- Interactive 2D gameplay and learning scenarios
- Role-based administration and analytics
- Containerized deployment

---

### 💰 NamiCash

**Self-Hosted Personal Finance Platform**

> A full-stack budgeting application built with self-hosting and
> production-oriented infrastructure in mind.

**Stack:** `React` `TypeScript` `FastAPI` `PostgreSQL` `Docker`

- Transaction tracking and customizable budgets
- Payday-based reporting and financial dashboards
- Multi-user and role-based administration
- Owner-scoped data isolation
- CSRF protection and rate limiting
- Argon2 password hashing
- Database migrations and backup/restore procedures

---

### 🏠 Homelab

**Self-Hosted Infrastructure & Automation**

> If I can host it myself, I probably will.

```text
                    ┌──────────────────────┐
                    │       INTERNET       │
                    └──────────┬───────────┘
                               │
                         ┌─────▼─────┐
                         │    VPS    │
                         │  Reverse  │
                         │   Proxy   │
                         └─────┬─────┘
                               │
                          Tailscale
                               │
                    ┌──────────▼──────────┐
                    │      HOMESERVER     │
                    │                      │
                    │  Docker / Services  │
                    │  Databases          │
                    │  Monitoring         │
                    │  DNS                │
                    └──────────┬──────────┘
                               │
                         ┌─────▼─────┐
                         │  OpenWrt  │
                         │ VLAN / DNS│
                         │ Firewall  │
                         └───────────┘
