<div align="center">

<img src="https://raw.githubusercontent.com/NFahmid/NFahmid/main/banner.svg" alt="Nuren Fahmid — software engineer, full-stack &amp; applied AI" width="100%" />

<br/>

<a href="https://nurenfahmid.vercel.app"><img src="https://img.shields.io/badge/Portfolio-1B4332?style=flat-square&logo=vercel&logoColor=E8F6EE" alt="Portfolio" /></a>
<a href="https://www.linkedin.com/in/nuren-fahmid"><img src="https://img.shields.io/badge/LinkedIn-1B4332?style=flat-square&logo=linkedin&logoColor=E8F6EE" alt="LinkedIn" /></a>
<a href="mailto:nurenfahmid@iut-dhaka.edu"><img src="https://img.shields.io/badge/Email-1B4332?style=flat-square&logo=gmail&logoColor=E8F6EE" alt="Email" /></a>

</div>

---

I build full-stack platforms and wire real AI into them — RAG pipelines, LLM-driven recommendations, and real-time systems — mostly for **campus-scale products** (social, learning, career tooling) and **healthcare workflows**.

- B.Sc. in Computer Science at **Islamic University of Technology** 
- Comfortable across the Java/OOP world, the MERN stack, and Django/FastAPI + Next.js hybrid architectures

---

## Stack

| | |
|---|---|
| **Languages** | ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![Java](https://img.shields.io/badge/Java-E76F00?style=flat-square&logo=openjdk&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) |
| **Frontend** | ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white) ![Tailwind](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) |
| **Backend** | ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) |
| **Data** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white) |
| **AI / ML** | ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) ![pgvector](https://img.shields.io/badge/pgvector%20%2F%20RAG-6E56CF?style=flat-square&logo=postgresql&logoColor=white) |
| **Tools / Infra** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white) |

---

## Selected Work

### ◆ IUTVerse - university social media app
*Team project · [Code](https://github.com/A-Piyas-04/IUTverse)*

A social + utility platform serving the whole university community — posts, messaging, and a job board in one place.

- Social post system with threaded comments, multi-type reactions, anonymous posting, and a personalized content feed
- Real-time messaging module: conversation management, paginated history, read-status tracking over WebSockets
- Job board with application tracking and threaded discussion on listings
- Tech: React.js, Django, Django REST Framework, Supabase

### ◆ EduVision — AI-powered learning platform
*Team project · [Code](https://github.com/FaiyazAwsaf/EduVision) · [Live Demo](https://edu-vision-frontend.vercel.app)*

Unifies classroom operations — automated grading, live tutoring, and AI content generation — for students, teachers, and admins.

- Led frontend development (Next.js, React, TypeScript) — dashboards, Recharts analytics, interactive UI
- Real-time tutoring module: LiveKit WebRTC + Django Channels, multi-student batch video sessions
- AI content generation (study guides, worked examples, practice problems) via Gemini, processed asynchronously with Celery
- Tech: Django, React, Next.js, LiveKit, Celery, Docker

### ◆ CareerPilot — agentic career co-pilot
*Team project · [Code](https://github.com/A-Piyas-04/CareerPilot)*

An AI platform that parses your CV, understands it, and actively hunts and scores jobs for you.

- CV intelligence pipeline: parses PDF/DOCX/manual resumes into semantic chunks, supports active-resume switching
- Evidence-grounded RAG Q&A over resume content with retrieval fallbacks
- Live Job Hunter workflow with hybrid fit scoring (skill overlap + semantic similarity) against real job postings
- Tech: Next.js, TypeScript, FastAPI, Supabase, pgvector, Gemini, JSearch, Docker

### ◆ Multi-Provider Agent Liquidity & Coordination Platform
*Team project · Codex Community Hackathon — SUST CSE Carnival 2026 · Finalist*

A fintech prototype helping mobile-financial-service agents monitor shared cash liquidity across providers (bKash, Nagad, Rocket) without blending balances.

- Four independent unusual-activity detectors: near-identical amounts, velocity spikes, balance inconsistency, provider-scoped behavioral k-NN
- Transparent, confidence-scored liquidity projections with quality-aware suppression on bad input
- Alert explanations generated in English, Bangla, and Banglish
- Full case lifecycle: acknowledgement, escalation, review, resolution, immutable audit trail

[Code](https://github.com/A-Piyas-04/SUST-hackathon-onsite)

<details>
<summary><b>More projects</b></summary>

**Cafeteria Crisis System** (DevOps project) — 5-service microservices architecture with isolated PostgreSQL schemas per service, dependency-ordered Docker Compose startup gated on health checks, and a GitHub Actions CI pipeline running parallel per-service tests before a full integration build.
Tech: Docker, GitHub Actions, FastAPI, PostgreSQL, Redis, RabbitMQ, Nginx  [Code](https://github.com/mksadman/DevSprint)

**SkillSync** — Admin-curated skills and learning platform with role-based dashboards, a skill taxonomy (prerequisites, difficulty, market demand), AI job-fit recommendations with skill-gap analysis, and SDG-8-aligned local opportunity matching in English/Bangla/Banglish.
Tech: React, FastAPI, SQLAlchemy, PostgreSQL, Gemini, JWT, Docker  [Code](https://github.com/adibqt/IiucProject)

**MediX** — End-to-end hospital workflow connecting patient appointment requests, receptionist vitals collection, doctor prescriptions, and pharmacist fulfillment, plus a digital prescription system and an automated pharmacy billing module.
Tech: Next.js, TypeScript, Java, Spring Boot, MySQL [Code](https://github.com/RidwanRK/MediX)

</details>

---

## Competitions & Hackathons

| Result | Event | Date |
|---|---|---|
| **1st Place** | IUT Codesprint | Jan 2026 |
| **Finalist** | SUST CSE Carnival (Codex Community Hackathon, presented by bKash) | Jul 2026 |
| **Finalist** | CloudCamp Infinity AI Buildfest | Jun 2026 |
| Top 10 | IUT DevSprint (DevOps Hackathon) | Apr 2026 |
| Top 15 | AUST Mindsparks Project Showcase | Jun 2026 |
| 15th place | IIUC Tech Fest | Nov 2025 |
| Top 30 | CUET SciBlitz AI Hackathon | Jul 2026 |

---

<div align="center">

<img src="https://streak-stats.demolab.com?user=NFahmid&hide_border=true&background=0D3327&ring=7CFFB2&fire=7CFFB2&currStreakLabel=7CFFB2&currStreakNum=D9F2E4&sideNums=D9F2E4&sideLabels=D9F2E4&dates=8FE3B5&border=2D6A4F&stroke=2D6A4F" alt="GitHub Streak" height="165"/>

<br/><br/>

<a href="https://nurenfahmid.vercel.app">Portfolio</a> · <a href="mailto:nurenfahmid@iut-dhaka.edu">Email</a> · <a href="https://www.linkedin.com/in/nuren-fahmid">LinkedIn</a>

</div>
