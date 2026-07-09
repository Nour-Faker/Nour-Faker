<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:ff9de2,30:c084fc,60:818cf8,100:38bdf8&height=220&section=header&text=Nour%20Faker&fontSize=62&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20Engineer%20in%20Progress%20·%20ENICarthage%20·%20Tunisia%20🌸&descAlignY=60&descSize=17&descColor=e9d5ff" />

</div>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=13&duration=2500&pause=900&color=C084FC&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=50&lines=🔧+Building+a+GitHub+PR+AI+reviewer+at+Smartovate+Ltd.;🌸+FastAPI+·+Docker+·+LLMs+·+Webhooks+·+PostgreSQL+·+RAG)](https://git.io/typing-svg)

</div>

---

<div align="center">

```
╔══════════════════════════════════════════════════════════════╗
║  profile = {                                                 ║
║    name      : "Nour Faker",                                 ║
║    role      : "CS Engineering @ ENICarthage — Year 1",      ║
║    internship: "AI Engineer @ Smartovate Ltd. (Cloud)",      ║
║    shipping  : "Production AI systems. Not tutorials.",       ║
║    stack     : ["FastAPI", "Docker", "LLMs", "PostgreSQL"],  ║
║    open_to   : "Internships & AI engineering roles 🌸",      ║
║  }                                                           ║
╚══════════════════════════════════════════════════════════════╝
```

</div>

---

## 🔧 Currently Building — AI Code Review Agent *(Smartovate Ltd. Internship)*

> A production-grade GitHub Pull Request reviewer powered by an LLM — designed for a real cloud consulting firm.

This isn't a tutorial project. It's a multi-sprint engineering effort with real design decisions:

- **Sprint 1 — Webhook Infrastructure:** FastAPI receiver with HMAC-SHA256 signature verification, bot-check logic, and payload routing. Deployed live on Railway.
- **Sprint 2 — LLM Integration:** Calling an LLM backend to analyze PR diffs and post structured review comments back to GitHub via the API.
- **Architecture decisions I own:** GitHub App auth vs. PAT strategy · raw diff vs. structured `/files` endpoint · file filtering to avoid noise.

```
Stack  : FastAPI · Python · GitHub Webhooks · HMAC-SHA256 · Docker · Railway · LLM backend
Status : Sprint 2 in progress — LLM integration & GitHub API output
Repo   : github.com/Nour-Faker/github-review-agent
```

---

## 🌷 Projects — Built from Scratch, Not Copied

> Everything below was built during Year 1 while taking full-time engineering courses at ENICarthage.

---

### 📒 Notes API — Production-Grade REST API

A notes management API engineered to production standards — not a CRUD demo.

What makes it real: JWT authentication with bcrypt password hashing, PostgreSQL + SQLAlchemy ORM with Alembic database migrations, Docker + docker-compose with healthchecks, and a 9-test pytest suite. Every layer is tested and containerized.

```
Stack   : FastAPI · PostgreSQL · SQLAlchemy · Alembic · JWT · Docker · pytest
What I  : Designed the schema, wrote migrations, set up auth middleware, containerized the stack
built     and wrote the full test suite. No tutorial. No starter code.
Repo    : github.com/Nour-Faker/notes-api
```

---

### 🎓 Wejheti — ML Orientation Predictor

Predicts optimal university specialization for Tunisian students using XGBoost — trained on real BAC data.

The interesting engineering: I used a **temporal train/test split** on 2025 holdout data to prevent leakage, engineered a `score_delta` feature to capture grade trends, and built a region/field category filtering system. The model significantly outperforms a naive baseline on unseen data.

```
Stack   : Python · XGBoost · FastAPI · Streamlit · Pandas · scikit-learn
What I  : Designed the ML pipeline, feature engineering, leakage prevention, and deployed
built     a Streamlit UI + FastAPI inference endpoint
Repo    : github.com/Nour-Faker/Wejheti
```

---

### 📄 RAG PDF Q&A API

Ask any PDF questions in natural language. Runs 100% locally — zero cloud cost.

Upload → chunk → embed with `nomic-embed-text` → store in ChromaDB → retrieve context → answer with Ollama. Full async FastAPI pipeline with proper chunking strategy and vector search.

```
Stack   : FastAPI · ChromaDB · Ollama · nomic-embed-text · pypdf · Pydantic
What I  : Built the full RAG pipeline from scratch: chunking, embedding, retrieval, generation.
built     Learned the tradeoffs between chunk size, overlap, and retrieval quality.
Repo    : github.com/Nour-Faker/rag-api
```

---

### 🤖 StyleAI — AI Personal Stylist

The most architecturally complex thing I've built: a full-stack AI application with a real multi-model inference pipeline.

Upload wardrobe → FashionCLIP encodes clothing into vectors → stored in Qdrant → Claude API generates outfit recommendations → Weather API adapts output to today's forecast. Four services. One cohesive product.

```
Stack   : FastAPI · FashionCLIP · Claude API · Next.js · SQLAlchemy · Qdrant
What I  : Designed the multi-model pipeline, integrated 4 external services, built the
built     frontend in Next.js, and handled vector search + LLM chaining.
Repo    : github.com/Nour-Faker/StyleAI
```

---

### 🚑 SmartEMS Tunisia — Emergency Dispatch System

Intelligent ambulance dispatch for Tunis using A* pathfinding on a real street graph.

Finds the optimal route between available units and emergency sites in real time, with priority dispatching logic. This was a systems design problem, not an ML one — and I treated it that way.

```
Stack   : Python · A* Algorithm · Graph Theory · Routing Logic
What I  : Implemented A* from scratch on a weighted graph, designed the dispatch priority
built     logic, and handled edge cases (no available unit, blocked routes).
Repo    : github.com/Nour-Faker/SmartEMS-Tunisia
```

---

### 🍅 AI Pomodoro Forecaster

Built a Pomodoro timer, collected my own focus data, then trained **Google's TimesFM** on it to predict my optimal study schedule. The AI answers natural language questions about your own productivity patterns.

```
Stack   : Python · Tkinter · Google TimesFM · SQLite · Custom AI module
Repo    : github.com/Nour-Faker/AI-Pomodoro-Forecaster
```

---

## 🌱 My Engineering Arc

```
Year 1 — Semester 1 · Foundations
  ├── C / C++          → Pointers, memory, OOP, templates
  ├── Algorithms        → Sorting, complexity, backtracking, CSPs
  ├── Data Structures   → Trees, graphs, linked lists
  └── Discrete Math     → Probability, Markov chains

Year 1 — Semester 2 · Real Systems
  ├── Python            → Scripts → APIs → ML pipelines
  ├── Backend APIs      → FastAPI · SQLAlchemy · PostgreSQL · JWT
  ├── ML Engineering    → XGBoost · feature engineering · leakage prevention
  ├── RAG Systems       → ChromaDB · embeddings · local LLMs
  ├── Computer Vision   → OpenCV · MediaPipe · real-time pipelines
  └── Full-Stack        → FastAPI + Next.js + Qdrant + external APIs

Now — Production Engineering (Internship)
  ├── Webhooks + HMAC   ✅ deployed live
  ├── Docker            ✅ all projects containerized
  ├── LLM integration   🔄 Sprint 2 in progress
  ├── GitHub Actions CI 🔜 next
  └── Agentic systems   🔜 LangGraph + memory
```

---

## 💜 Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-818cf8?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-a855f7?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-c084fc?style=for-the-badge&logo=c&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-f9a8d4?style=for-the-badge&logo=javascript&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-7dd3fc?style=for-the-badge&logo=typescript&logoColor=white)

**Backend & Databases**

![FastAPI](https://img.shields.io/badge/FastAPI-c084fc?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-a855f7?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-818cf8?style=for-the-badge)
![Pydantic](https://img.shields.io/badge/Pydantic-7dd3fc?style=for-the-badge)
![Alembic](https://img.shields.io/badge/Alembic-f9a8d4?style=for-the-badge)

**AI & ML**

![Claude API](https://img.shields.io/badge/Claude_API-c084fc?style=for-the-badge)
![XGBoost](https://img.shields.io/badge/XGBoost-a855f7?style=for-the-badge)
![ChromaDB](https://img.shields.io/badge/ChromaDB-818cf8?style=for-the-badge)
![Ollama](https://img.shields.io/badge/Ollama-7dd3fc?style=for-the-badge)
![FashionCLIP](https://img.shields.io/badge/FashionCLIP-f9a8d4?style=for-the-badge)
![OpenCV](https://img.shields.io/badge/OpenCV-c084fc?style=for-the-badge&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-a855f7?style=for-the-badge)
![scikit-learn](https://img.shields.io/badge/scikit--learn-818cf8?style=for-the-badge&logo=scikitlearn&logoColor=white)

**DevOps & Deployment**

![Docker](https://img.shields.io/badge/Docker-c084fc?style=for-the-badge&logo=docker&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-a855f7?style=for-the-badge&logo=railway&logoColor=white)
![Git](https://img.shields.io/badge/Git-f9a8d4?style=for-the-badge&logo=git&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-818cf8?style=for-the-badge&logo=pytest&logoColor=white)

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-c084fc?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-a855f7?style=for-the-badge&logo=react&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-818cf8?style=for-the-badge&logo=tailwindcss&logoColor=white)

</div>

---

## 🌸 GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=Nour-Faker&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=c084fc&icon_color=a855f7&text_color=f9a8d4" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nour-Faker&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=c084fc&text_color=f9a8d4&langs_count=6" />

<br/>

[![GitHub Streak](https://streak-stats.demolab.com?user=Nour-Faker&theme=tokyonight&hide_border=true&background=0d1117&ring=c084fc&fire=a855f7&currStreakLabel=c084fc&sideLabels=f9a8d4&dates=6b7280)](https://git.io/streak-stats)

</div>

---

## 💌 Let's Connect

<div align="center">

[![Portfolio](https://img.shields.io/badge/🌸_Portfolio-nourfaker--portfolio.netlify.app-c084fc?style=for-the-badge)](https://nourfaker-portfolio.netlify.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Nour_Faker-818cf8?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nour-faker-82b691386/)
[![GitHub](https://img.shields.io/badge/GitHub-Nour--Faker-f9a8d4?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Nour-Faker)
[![Email](https://img.shields.io/badge/Email-nour.faker@enicar.ucar.tn-a855f7?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nour.faker@enicar.ucar.tn)

<br/>

> *I'm open to AI engineering internships and collaborations. I build things that work in production, not just in notebooks.*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:38bdf8,30:818cf8,60:c084fc,100:ff9de2&height=120&section=footer&text=Year+1.+Real+internship.+Production+systems.+🌸&fontSize=15&fontColor=ffffff&fontAlignY=65"/>

</div>
