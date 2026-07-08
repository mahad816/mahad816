
# Hi, I'm Mahad Ali 👋

**Final-Year CS @ GIKI · AI Applications · Backend · Agentic RAG**

I build **production-style AI systems** — not notebook demos. My focus is **Retrieval-Augmented Generation (RAG)**, **LangGraph agent workflows**, and **scalable FastAPI backends** with real data pipelines, tests, and documentation.

Currently targeting roles in **AI Engineering**, **ML Engineering**, and **Backend (AI platform)**.

---

## What I build

| Focus | How I demonstrate it |
|-------|---------------------|
| **Agentic RAG** | LangGraph orchestration, query routing, evidence grading, rewrite loops |
| **Hybrid retrieval** | Metadata + keyword (PostgreSQL FTS) + vector (Qdrant) with fusion reranking |
| **Grounded LLM apps** | Citations, source verification, no “chatbot without sources” |
| **Backend systems** | FastAPI, async PostgreSQL, background jobs, OAuth, 480+ pytest tests |
| **Full-stack delivery** | Next.js UI, Docker infra, incremental indexing pipelines |

---

## 🛠 Tech Stack

**Languages:** Python · JavaScript/TypeScript · C++

**AI / LLM:** LangGraph · LangChain · RAG · Prompt Engineering · OpenAI API · Google Gemini · Ollama · NLP

**Backend:** FastAPI · Django · REST APIs · PostgreSQL · SQLite · JWT · Alembic

**Frontend:** Next.js · React · Tailwind CSS

**Data / Search:** Qdrant · Vector embeddings · Full-text search · Hybrid retrieval

**DevOps:** Docker · AWS EC2 · Linux · Git

**Automation:** n8n · Google Workspace APIs · Gemini Vision workflows

---

## 🚀 Featured Projects

### 🧠 [DriveMind AI](https://github.com/mahad0ali/INFO_VAULT) — Agentic RAG for Google Drive

**Personal knowledge assistant** that indexes Google Drive and answers questions with **grounded citations** — built as a portfolio-grade agentic RAG system.

**Why it's not a simple PDF chatbot:**
- **Query routing** — CHITCHAT, file inventory, named-file lookup, and hybrid RAG paths
- **Hybrid retrieval** — metadata + PostgreSQL keyword + Qdrant vector search with RRF merge and reranking
- **LangGraph agent** — intent planning, selective retrievers, evidence grading, query rewrite loop, citation verification
- **Incremental indexing** — sync → ingest → chunk → embed pipeline; only changed files re-processed
- **Multi-format ingestion** — Google Docs, PDF, DOCX, TXT, image OCR (Tesseract)
- **Full stack** — FastAPI backend, Next.js chat UI, source viewer, OAuth, 480+ backend tests

```text
Drive → Sync/Ingest/Chunk/Build → PostgreSQL + Qdrant
User question → classify_query → retrieve → grounded answer + sources
```

**Tech:** LangGraph · LangChain · FastAPI · Next.js · PostgreSQL · Qdrant · Docker · OpenAI · Google Drive API

🔗 [Repository](https://github.com/mahad816/DriveMind_AI) · [Architecture docs](https://github.com/mahad816/DriveMind_AI/blob/main/docs/ARCHITECTURE.md)

---

### 🏥 CoreChain — Privacy-Preserving Federated Learning Platform

Distributed medical AI platform for collaborative model training **without sharing raw patient data**.

- Federated Learning (Flower) · Homomorphic encryption · Hyperledger Fabric contribution tracking
- Dockerized on AWS · **97.9%** accuracy in deployed demonstration

🏆 **2nd Place — Data Science, GIKI Industrial Open House 2026**

---

### 📊 PTCL Group Review Intelligence Platform

On-premise AI platform (internship — PTCL Group Data & AI) for collecting, classifying, and visualizing Google Play Store reviews via a **local LLM pipeline**.

**Tech:** Python · FastAPI · Next.js · SQLite · Ollama · Chart.js

---

### ⚙️ AI Workflow Automation Platform

End-to-end automation with **n8n + Gemini Vision**: process job screenshots → extract structured data → classify opportunities → notify high-fit matches.

**Tech:** n8n · Gemini Vision · Google Drive · Google Sheets · Gmail

---

## 🌱 Currently exploring

- AI evaluation & retrieval metrics (RAGAS-style benchmarking)
- Advanced agent patterns with LangGraph
- Backend system design & cloud-native deployment
- Distributed systems

---

## 📂 About this GitHub

Projects here focus on **AI applications**, **LLM systems**, **backend engineering**, and **workflow automation** — with emphasis on:

- Clean architecture & modular services
- Tested, documented, deployable code
- Real-world constraints (OAuth, incremental sync, citation grounding)

---

## 📫 Connect

🌐 **Portfolio:** [mahadali.vercel.app](https://mahadali.vercel.app)

💼 **LinkedIn:** [linkedin.com/in/mahad0ali](https://linkedin.com/in/mahad0ali)

📧 **Email:** mahad.official02@gmail.com

<!-- ============ COPY TO HERE ============ -->
