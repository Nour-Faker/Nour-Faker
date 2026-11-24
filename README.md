<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:ff9de2,30:c084fc,60:818cf8,100:38bdf8&height=200&section=header&text=Nour%20Faker&fontSize=58&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20%26%20Backend%20Engineer%20·%20ENICarthage%20·%20Tunisia&descAlignY=60&descSize=17&descColor=ffffff" />

**I build LLM-powered backend systems: APIs, retrieval pipelines and the tooling around them to run reliably.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Nour_Faker-818cf8?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nour-faker-82b691386/)
[![Portfolio](https://img.shields.io/badge/Portfolio-nourfaker--portfolio-c084fc?style=for-the-badge&logo=netlify&logoColor=white)](https://nourfaker-portfolio.netlify.app)
[![Email](https://img.shields.io/badge/Email-nour.faker@enicar.ucar.tn-a855f7?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nour.faker@enicar.ucar.tn)

</div>

---

## 👋 About

Second-year computer engineering student at **ENICarthage** (Tunis). This summer I interned as an **AI Engineer at Smartovate Ltd.**, where I built and deployed a GitHub pull-request review service on Azure. I'm looking for **AI / backend engineering internships and junior roles**, and for teams to build with.

| | |
|---|---|
| 🎓 **Studying** | Computer Science Engineering, ENICarthage (2025 – present) |
| 💼 **Experience** | AI Engineer Intern, Smartovate Ltd. (Jul–Aug 2026) · Senior Member, Melkart Junior Enterprise |
| 🧰 **Core stack** | Python · FastAPI · PostgreSQL · Docker · Azure · RAG · LLM APIs |
| 🌱 **Learning now** | Evaluating RAG systems · reliable async backends · agentic AI · ML in production |

---

## 🔧 Featured Work

### 1 · GitHub PR Code Review Service — *Smartovate Ltd. internship*
An LLM-powered reviewer that comments on pull requests automatically.

- **Secure ingestion:** FastAPI webhook receiver with HMAC-SHA256 signature verification
- **Pipeline:** `DiffExtractor → LLMAnalyzer (Azure OpenAI gpt-5-mini) → RateLimiter → GitHubCommenter`, with severity tagging, bot-loop prevention and an @mention handler
- **Delivery:** Dockerized, deployed on Azure App Service, GitHub Actions CI with **37 tests (~30 s)**
- **Dashboard:** React app with live PR reviews, severity charts and an "Ask the Agent" chat
- **Decisions I owned:** GitHub App auth vs PAT · raw diff vs `/files` endpoint · file filtering

`FastAPI` `Azure OpenAI` `Docker` `Azure App Service` `GitHub Actions` `React`  ·  [**Code →**](https://github.com/Nour-Faker/github-review-agent)

### 2 · ClaimGuard AI — *CSTAM × Velodoc challenge, built with [Wassim](https://github.com/wassimkraiem243)*
A human-supervised copilot that pre-validates healthcare claims before submission.

- Ingests synthetic claims as **JSONL, CSV bundles or FHIR** and normalizes them to a single claim envelope
- **Rules-first validation:** a deterministic engine of 15 rules (R001–R015) returns explainable results, with an optional local LLM explaining the findings
- Monorepo: **FastAPI** API, **Next.js** dashboard, shared types, **PostgreSQL + pgvector**, Docker Compose

`FastAPI` `Next.js` `PostgreSQL` `pgvector` `Ollama` `Docker`  ·  [**Code →**](https://github.com/wassimkraiem243/ClaimGuardAI)

### 3 · RAG PDF Q&A API
Upload a PDF and ask questions. Answers come with source citations and run fully locally, at no cloud cost.

Pipeline: recursive chunking → nomic embeddings → ChromaDB cosine search → cross-encoder reranking → local LLM. Along the way I debugged cosine vs L2 distance, tuned chunk overlap, and added reranking because vector similarity ≠ relevance.

`FastAPI` `ChromaDB` `Ollama` `Cross-Encoder` `Docker`  ·  [**Code →**](https://github.com/Nour-Faker/rag-api)

---

## 🧪 More Projects

| Project | What it does | Stack |
|---|---|---|
| [**Smart Study Hub**](https://github.com/Nour-Faker/smart-study-api) | PDF study assistant: upload → embeddings → LLM answers, with JWT auth and migrations | FastAPI · PostgreSQL · ChromaDB · Ollama · Docker |
| **Notes API** | REST API with JWT + bcrypt, Alembic migrations, healthchecked Docker setup, 9-test pytest suite | FastAPI · PostgreSQL · Alembic · pytest |
| [**Wejheti**](https://github.com/Nour-Faker/Wejheti) | Predicts university orientation from real Tunisian BAC data; temporal train/test split to prevent leakage | XGBoost · scikit-learn · FastAPI · Streamlit |
| [**StyleAI**](https://github.com/Nour-Faker/StyleAI) | Four-service stylist: FashionCLIP embeddings → Qdrant → Claude outfit generation, adapted to the weather | FastAPI · Next.js · Qdrant · Claude API |
| [**SmartEMS-Tunisia**](https://github.com/Nour-Faker/SmartEMS-Tunisia) | Ambulance dispatch using A* on a real Tunis street graph, with priority logic and blocked-route handling | Python · A* |
| [**HandGesture-Control**](https://github.com/Nour-Faker/HandGesture-Control) | Webcam hand-tracking virtual mouse | OpenCV · MediaPipe |

---

## ⚙️ How I Build

- **Verify, don't trust:** signed webhooks, JWT with hashed passwords, per-user data isolation
- **Make it reproducible:** Docker with healthchecks, Alembic migrations, CI on every push
- **Test the pipeline:** pytest suites, isolated test databases
- **Prevent leakage and fakes:** temporal splits in ML, source citations in RAG

---

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-818cf8?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-c084fc?style=flat-square&logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-a855f7?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-7dd3fc?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-818cf8?style=flat-square&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-c084fc?style=flat-square&logo=microsoftazure&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-a855f7?style=flat-square&logo=githubactions&logoColor=white)
![React](https://img.shields.io/badge/React-7dd3fc?style=flat-square&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-818cf8?style=flat-square&logo=nextdotjs&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-c084fc?style=flat-square)
![Qdrant](https://img.shields.io/badge/Qdrant-a855f7?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-7dd3fc?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-818cf8?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-f9a8d4?style=flat-square)

</div>

---

## 📊 GitHub Activity

<div align="center">

<img height="150" src="https://github-readme-stats.vercel.app/api?username=Nour-Faker&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=c084fc&icon_color=a855f7&text_color=f9a8d4" />
<img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nour-Faker&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=c084fc&text_color=f9a8d4&langs_count=6" />

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:38bdf8,30:818cf8,60:c084fc,100:ff9de2&height=100&section=footer" />

</div>
