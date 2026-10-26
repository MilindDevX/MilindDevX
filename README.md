<div align="center">

  <h1>Milind Bansal</h1>
  <h3>Machine Learning Engineer · Full-Stack Developer · Data Analyst</h3>

  <p>
    <a href="https://portfolio-milind.vercel.app/"><img src="https://img.shields.io/badge/🌐_Portfolio-Visit_Site-6366f1?style=for-the-badge" alt="Portfolio" /></a>
    <a href="https://www.linkedin.com/in/milind-bansal-177606244/"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="mailto:milindsk8r@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
    <a href="https://public.tableau.com/app/profile/milind.bansal5979/"><img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" alt="Tableau Public" /></a>
  </p>

  <img src="https://img.shields.io/badge/🟢_Open_to_Work-Full--Stack%20%7C%20MLE%20%7C%20Data%20Roles-22c55e?style=for-the-badge" alt="Open to Work" />

</div>

---

## 👨‍💻 About Me

- 🚀 I ship **production-grade AI + Full-Stack systems** — from an LLM feedback-triage SaaS in production to healthcare marketplaces with 58 automated tests and CDSCO regulatory compliance
- 🧪 I **measure LLM systems, not just build them** — I maintain [evalbar](https://github.com/MilindDevX/evalbar), an open-source eval and tracing harness on PyPI
- ⚙️ I care about **backend reliability** — [skipq](https://github.com/MilindDevX/skipq) is my Postgres-backed job queue in Go with leases, retries and race-tested workers
- 🤖 I integrate **LLMs into real products** — not demos — using Groq, OpenAI, and Hugging Face Transformers with background job queues, AES-256 encryption, and sub-1.5s latency
- 📊 I communicate with data — ETL pipelines, Tableau dashboards, and predictive models that inform real decisions

---

## 🛠️ Technical Arsenal

### 🤖 Machine Learning & AI
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logo=groq&logoColor=white)

### 💻 Frontend Development
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)

### ⚙️ Backend & Infrastructure
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

### 📊 Data & Analytics
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## 🚀 Flagship Projects

### 🧪 evalbar — LLM Eval & Tracing Harness (open source)
> Point it at any Python pipeline and a file of labelled cases; get a scored run with a trace per case — tokens, latency and cost — plus CI gates that fail when quality drops.

[![Repo](https://img.shields.io/badge/GitHub-View_Repo-181717?style=flat-square&logo=github)](https://github.com/MilindDevX/evalbar)
[![PyPI](https://img.shields.io/pypi/v/evalbar?style=flat-square&logo=pypi&logoColor=white)](https://pypi.org/project/evalbar/)
![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square)

- Scorers: exact/contains/regex, JSON-schema validity, retrieval recall@k, and LLM-as-judge with its own cost reported separately
- `evalbar diff --fail-on-drop` names regressed cases and blocks the merge in CI; self-contained HTML reports
- Real case study: measured a FeedbackOS prompt change on 50 labelled cases — mixed feedback kept its praise in 8/8 cases (was 0/8)
- **Stack:** `Python` · `LiteLLM` · `pytest` · `GitHub Actions` · `PyPI trusted publishing`

---

### ⚙️ skipq — Durable Job Queue for Go on Postgres
> Many workers claim jobs with `SELECT … FOR UPDATE SKIP LOCKED` without blocking each other; crashed workers' jobs come back when their lease runs out.

[![Repo](https://img.shields.io/badge/GitHub-View_Repo-181717?style=flat-square&logo=github)](https://github.com/MilindDevX/skipq)
![Go](https://img.shields.io/badge/Go-1.26-00ADD8?style=flat-square&logo=go&logoColor=white)

- At-least-once delivery with leases and fenced acks, retries with backoff + jitter, dead-letter table, idempotency keys, transactional enqueue
- Worker pool with heartbeats and graceful shutdown; HTTP API and Prometheus metrics
- Integration tests run under Go's race detector against real Postgres, including a no-double-run test with many workers
- **Stack:** `Go` · `PostgreSQL` · `Docker Compose` · `Prometheus`

---

### 🔍 TruthLens — Fake-News Classification & Interpretability Platform
> Fake-news classifier with fail-closed serving and token-level SHAP explanations of each prediction.

[![Repo](https://img.shields.io/badge/GitHub-View_Repo-181717?style=flat-square&logo=github)](https://github.com/MilindDevX/TruthLens)
![Inference](https://img.shields.io/badge/Inference-<300ms_CPU-orange?style=flat-square)

- TF-IDF + Logistic Regression baseline on ISOT news data; the API returns 503 instead of guessing when no validated model is loaded
- Drift monitoring (rolling KL divergence, confidence and class-balance alerts), JWT with refresh-token rotation, Google OAuth
- **Stack:** `scikit-learn` · `SHAP` · `FastAPI` · `React` · `PostgreSQL` · `Docker Compose`

---

### 🏥 MedMarket — Healthcare Marketplace Platform
> Production-grade medical marketplace with consumer, pharmacy, and admin portals under full CDSCO/DPCO regulatory compliance.

[![Repo](https://img.shields.io/badge/GitHub-View_Repo-181717?style=flat-square&logo=github)](https://github.com/MilindDevX/medmarket)
[![Live API](https://img.shields.io/badge/Live_API-Render-46E3B7?style=flat-square&logo=render)](https://medmarket-g08v.onrender.com/api/docs)
![Tests](https://img.shields.io/badge/Tests-58_Passing-brightgreen?style=flat-square)
![Routes](https://img.shields.io/badge/Protected_Routes-30+-blue?style=flat-square)

- JWT 15-min access + 7-day refresh rotation, BullMQ + Redis expiry queue, Cloudinary asset management
- 3 portals, 30+ protected routes, 38 backend + 20 frontend tests
- **Stack:** `TypeScript` · `Node.js 22` · `Express 5` · `React 19` · `Vite 8` · `Prisma 7` · `BullMQ 5` · `Redis` · `PostgreSQL (Neon)`

---

### 🤖 FeedbackOS — AI Feedback Triage SaaS
> Eliminates 5–10 hrs/week of manual PM tagging by auto-classifying user feedback by theme, sentiment, and product area using LLMs.

[![Repo](https://img.shields.io/badge/GitHub-View_Repo-181717?style=flat-square&logo=github)](https://github.com/MilindDevX/feedbackos)
[![Live Demo](https://img.shields.io/badge/Live_Demo-feedbackos.vercel.app-6366f1?style=flat-square)](https://feedbackos.vercel.app)
![Latency](https://img.shields.io/badge/Classification_Latency-~1.2s-orange?style=flat-square)
![Themes](https://img.shields.io/badge/Themes-7_Auto_Detected-blue?style=flat-square)

- Two-process architecture: Next.js frontend + isolated BullMQ worker with AES-256-GCM credential encryption
- Magic-link auth via NextAuth v5, 48 demo items across 4 sentiment classes
- **Stack:** `Next.js 16` · `Groq gpt-oss-120b` · `BullMQ 5` · `PostgreSQL (Neon)` · `Prisma 5` · `NextAuth v5` · `Recharts 3` · `Radix UI`

---

<details>
<summary><b>📂 More Projects (5)</b></summary>

<br>

| Project | Description | Stack |
|---------|-------------|-------|
| 🛣️ **[RouteLens](https://github.com/MilindDevX/routelens)** · [![Live](https://img.shields.io/badge/Live-routelens--xi.vercel.app-6366f1?style=flat-square)](https://routelens-xi.vercel.app/) | Zero-backend, 100% client-side OpenAPI parser & structural JSON diff tool for developers | `Next.js 14` · `TypeScript` · `Tailwind CSS` |
| 💰 **[BudgetFlow](https://github.com/MilindDevX/BudgetFlow)** | High-performance personal finance dashboard with SMA forecasting | `React` · `Vite` · `Tailwind CSS` · `Express` · `Prisma` |
| 📝 **[QuickNotes](https://github.com/MilindDevX/QuickNotes)** | Fast, responsive serverless note-taking app | `React` · `NeonDB` |
| 🌐 **[Portfolio](https://github.com/MilindDevX/portfolio)** | MDX-powered showcase using the Once UI design system | `Next.js 16` · `React 19` · `MDX` · `Sass` |
| 🌬️ **[Beijing PM2.5 Analysis](https://public.tableau.com/app/profile/milind.bansal5979/)** | ETL + ML analysis on 5 years of air quality data; 3-tier public health alert framework | `Python` · `Pandas` · `scikit-learn` · `Tableau` |

</details>

---

## 📈 GitHub Activity

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=MilindDevX&theme=radical&hide_border=true" alt="GitHub Streak" />
</div>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=MilindDevX&show_icons=true&theme=radical&hide_border=true&include_all_commits=true&count_private=true" alt="Milind's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MilindDevX&layout=compact&theme=radical&hide_border=true" alt="Top Languages" />
</div>

---

<div align="center">
  <sub>💬 Always happy to talk about AI systems, backend architecture, or data pipelines. Let's build something great.</sub>
</div>
