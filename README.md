<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:ff9de2,30:c084fc,60:818cf8,100:38bdf8&height=220&section=header&text=Nour%20Faker&fontSize=62&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20Engineer%20in%20Progress%20·%20ENICarthage%20·%20Tunisia%20🌸&descAlignY=60&descSize=17&descColor=e9d5ff" />

</div>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=13&duration=2500&pause=900&color=C084FC&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=50&lines=🔧+Building+a+GitHub+PR+AI+reviewer+at+Smartovate+Ltd.;🌸+FastAPI+·+Docker+·+LLMs+·+RAG+·+PostgreSQL+·+Agents)](https://git.io/typing-svg)

</div>

---

<div align="center">

```
╔══════════════════════════════════════════════════════════════╗
║  profile = {                                                 ║
║    name      : "Nour Faker",                                 ║
║    role      : "CS Engineering @ ENICarthage — Year 2",      ║
║    internship: "AI Engineer @ Smartovate Ltd. (ongoing)",    ║
║    building  : "Production AI systems. Not tutorials.",      ║
║    stack     : ["FastAPI", "Docker", "LLMs", "RAG"],        ║
║    open_to   : "AI engineering roles & collaborations 🌸",   ║
║  }                                                           ║
╚══════════════════════════════════════════════════════════════╝
```

</div>

---

## 🔧 Currently Building — AI Code Review Agent *(Smartovate Ltd.)*

> A production-grade GitHub PR reviewer powered by an LLM — built for a real cloud consulting firm.

- **Sprint 1** — FastAPI webhook receiver with HMAC-SHA256 verification, deployed live on Railway
- **Sprint 2** — LLM integration: analyzing PR diffs, posting structured review comments via GitHub API
- **Architecture decisions I own:** GitHub App auth vs PAT · raw diff vs `/files` endpoint · file filtering

```
Stack  : FastAPI · Python · GitHub Webhooks · HMAC-SHA256 · Docker · Railway · LLM
Status : Sprint 2 in progress
```

---

## 🌷 Things I've Built

---

### 📄 RAG PDF Q&A API
Upload any PDF. Ask questions. Get answers grounded in your document with source citations — no hallucination, no cloud cost.

Built the full pipeline from scratch: recursive chunking → nomic embeddings → ChromaDB cosine search → cross-encoder reranking → local LLM. Every design decision was deliberate — I debugged cosine vs L2 distance, tuned chunk overlap, and added reranking because vector similarity ≠ relevance.

```
Stack : FastAPI · ChromaDB · Ollama · nomic-embed-text · Cross-Encoder · Docker
Repo  : github.com/Nour-Faker/rag-api
```

---

### 📒 Notes API — Production-Grade REST API
Not a CRUD demo. JWT auth with bcrypt, PostgreSQL + SQLAlchemy + Alembic migrations, Docker with healthchecks, 9-test pytest suite.

```
Stack : FastAPI · PostgreSQL · SQLAlchemy · Alembic · JWT · Docker · pytest
Repo  : github.com/Nour-Faker/notes-api
```

---

### 🎓 Wejheti — ML University Orientation Predictor
XGBoost trained on real Tunisian BAC data. Temporal train/test split to prevent leakage. Engineered a `score_delta` feature to capture grade trends.

```
Stack : XGBoost · FastAPI · Streamlit · pandas · scikit-learn
Repo  : github.com/Nour-Faker/Wejheti
```

---

### 🤖 StyleAI — AI Personal Stylist
Four services. One pipeline: FashionCLIP encodes wardrobe → Qdrant stores vectors → Claude generates outfits → Weather API adapts recommendations to today's forecast.

```
Stack : FastAPI · FashionCLIP · Claude API · Next.js · Qdrant · SQLAlchemy
Repo  : github.com/Nour-Faker/StyleAI
```

---

### 🚑 SmartEMS Tunisia — Emergency Dispatch System
A* pathfinding on a real Tunis street graph. Priority dispatch logic. Handles edge cases: no available unit, blocked routes.

```
Stack : Python · A* Algorithm · Graph Theory
Repo  : github.com/Nour-Faker/SmartEMS-Tunisia
```

---

### 🖐️ HandGesture Control — CV Mouse
Control your cursor with hand gestures via webcam. Real-time pipeline using MediaPipe landmark detection + OpenCV.

```
Stack : Python · OpenCV · MediaPipe
Repo  : github.com/Nour-Faker/HandGesture-Control
```

---

## 🌱 My Arc So Far

```
Semester 1  →  C / C++ · Algorithms · Data Structures · Discrete Math
Semester 2  →  Python · FastAPI · PostgreSQL · ML · RAG · Computer Vision
Now         →  Internship · Docker · Agentic AI · Production systems
```

---

## 💜 Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-818cf8?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-c084fc?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-a855f7?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-7dd3fc?style=for-the-badge&logo=docker&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-818cf8?style=for-the-badge)
![Ollama](https://img.shields.io/badge/Ollama-c084fc?style=for-the-badge)
![Claude API](https://img.shields.io/badge/Claude_API-a855f7?style=for-the-badge)
![XGBoost](https://img.shields.io/badge/XGBoost-f9a8d4?style=for-the-badge)
![scikit-learn](https://img.shields.io/badge/scikit--learn-818cf8?style=for-the-badge&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-c084fc?style=for-the-badge&logo=opencv&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-a855f7?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-7dd3fc?style=for-the-badge&logo=railway&logoColor=white)

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
[![Email](https://img.shields.io/badge/Email-nour.feker2004@gmail.com-a855f7?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nour.feker2004@gmail.com)

<br/>

> *I build things that work in production, not just in notebooks.*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:38bdf8,30:818cf8,60:c084fc,100:ff9de2&height=120&section=footer&text=Year+2.+Real+internship.+Production+systems.+🌸&fontSize=15&fontColor=ffffff&fontAlignY=65"/>

</div>
