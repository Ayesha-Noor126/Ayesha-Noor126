<div align="center">

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                        HERO SECTION                           -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Ayesha%20Noor&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=AI%20Engineer%20%E2%80%A2%20Generative%20AI%20%E2%80%A2%20RAG%20%E2%80%A2%20AI%20Agents&descAlignY=58&descSize=18&descFontColor=a78bfa" alt="Ayesha Noor — AI Engineer · Generative AI · RAG · AI Agents" width="100%"/>

</div>

<div align="center">

**Building intelligent systems that retrieve, reason, and act.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ayesha-noor-a4b305343/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ayesha-Noor126)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:noorayesha0123456@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-6D28D9?style=for-the-badge&logo=vercel&logoColor=white)](https://YOUR_PORTFOLIO_URL)

</div>

---

## 👩‍💻 About Me

I'm a Computer Science graduate from **COMSATS University Islamabad, Lahore Campus**, focused on the intersection of AI engineering, retrieval systems, and agentic AI.

My work centers on building practical, backend-heavy AI systems — from **RAG pipelines** and **knowledge graphs** to **LLM-powered agents** capable of multi-step reasoning and tool use. I care about the full picture: retrieval quality, observability, evaluation, and real-world reliability.

```
Current Focus:   AI/ML Engineering · Generative AI · RAG Systems · AI Agents
Learning:        LangGraph · Advanced Retrieval · Agentic Workflows · Voice AI
Interested in:   Roles in AI/ML Engineering, Generative AI, Intelligent Systems
```

---

## 🧠 What I Build

*A system is only as good as what it can retrieve, reason over, and act upon.*

<div align="center">

```
┌─────────────────────────────────────────────────────────────────┐
│                    AI ENGINEERING PIPELINE                       │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│   Documents / Data                                               │
│        │                                                         │
│        ▼                                                         │
│   [ Ingestion & Chunking ]  ──  Embeddings · Parsing            │
│        │                                                         │
│        ▼                                                         │
│   [ Retrieval Layer ]  ──────  Dense · Sparse · Graph · Hybrid  │
│        │                                                         │
│        ▼                                                         │
│   [ Reasoning / LLM ]  ──────  Prompt Engineering · Reranking   │
│        │                                                         │
│        ▼                                                         │
│   [ Agent Orchestration ]  ──  LangGraph · Tool Use · Memory    │
│        │                                                         │
│        ▼                                                         │
│   [ Response / Action ]  ────  APIs · Voice · External Services │
│        │                                                         │
│        ▼                                                         │
│   [ Observability & Eval ]  ─  Langfuse · DeepEval · Metrics    │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

</div>

---

## 🔬 AI Engineering Focus

<div align="center">

| Domain | Technologies | Purpose |
|:---|:---|:---|
| **RAG Systems** | ChromaDB · FAISS · BM25 · RRF · LightRAG | Retrieval quality & hybrid search |
| **Graph RAG** | Neo4j · LightRAG | Relationship-centric multi-hop reasoning |
| **LLM Integration** | OpenAI · Gemini · Groq · Hugging Face | Generation & structured outputs |
| **AI Agents** | LangChain · LangGraph · Playwright | Agentic workflows & tool orchestration |
| **Voice AI** | WebSockets · TTS · Gemini | Real-time voice interaction |
| **Observability** | Langfuse · DeepEval | LLM evaluation & tracing |
| **Backend** | FastAPI · PostgreSQL · Redis · Docker | Production-ready AI system backends |

</div>

---

## 🚀 Featured Projects

### 🌐 LightRAG Explorer — *Simple RAG vs Graph RAG Comparison Platform*

> *"Most RAG systems treat documents as isolated chunks. LightRAG Explorer reveals the relationships between them."*

<table>
<tr>
<td width="60%">

**What it solves:** Standard vector RAG loses relational context between documents. This platform lets you directly compare flat retrieval against graph-based retrieval to see when and why Graph RAG wins.

**Architecture highlights:**
- **Simple RAG** pipeline using ChromaDB vector store
- **LightRAG** graph-based retrieval with Neo4j knowledge graph
- Five retrieval modes: `Naive` · `Local` · `Global` · `Hybrid` · `Mix`
- Cross-document queries & multi-hop reasoning
- Relationship-centric query support
- Full **Langfuse** observability integration
- Experiment snapshots for comparing retrieval runs
- Interactive Neo4j graph visualization

</td>
<td width="40%" align="center">

```
  Documents
      │
  ┌───┴────────┐
  │            │
  ▼            ▼
ChromaDB    Neo4j KG
(Simple RAG) (LightRAG)
  │            │
  └─────┬──────┘
        │
   Comparison
   Interface
        │
   Langfuse 📊
```

</td>
</tr>
</table>

**Stack:** `Python` `FastAPI` `React` `Vite` `Neo4j` `ChromaDB` `LightRAG` `Docker` `Langfuse`

[![View Project](https://img.shields.io/badge/View%20on%20GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ayesha-Noor126/LightRAG-Explorer)

---

### 💹 Financial RAG System — *Production-Style Financial Document QA*

> *"Financial documents are dense, technical, and unforgiving of retrieval errors. This system is built to handle them."*

<table>
<tr>
<td width="60%">

**What it solves:** Financial document question-answering demands precision. Generic RAG setups miss crucial figures and context. This system combines multiple retrieval strategies with reranking to maximize answer quality.

**Architecture highlights:**
- **Hybrid retrieval** — Dense (BGE embeddings + FAISS) + Sparse (BM25)
- **Reciprocal Rank Fusion (RRF)** for score normalization
- **ColBERT reranking** for final result precision
- Groq-powered LLM generation
- Tavily web search integration
- Langfuse tracing & DeepEval evaluation
- FastAPI production backend

</td>
<td width="40%" align="center">

```
  Financial Docs
        │
  ┌─────┴──────┐
  │            │
  ▼            ▼
FAISS (Dense)  BM25 (Sparse)
  │            │
  └─────┬──────┘
        │ RRF Fusion
        ▼
   ColBERT Rerank
        │
      Groq LLM
        │
     Answer ✓
```

</td>
</tr>
</table>

**Stack:** `Python` `FastAPI` `FAISS` `BM25` `BGE Embeddings` `ColBERT` `RRF` `Groq` `Tavily` `Langfuse` `DeepEval`

---

### 🎙️ Voice AI Agent — *Conversational AI with Agentic Tool Use*

> *"Not just a chatbot — an agent that listens, reasons, uses tools, and takes action."*

<table>
<tr>
<td width="60%">

**What it solves:** Most voice assistants follow rigid scripts. This agent uses LangGraph to orchestrate multi-step workflows, integrate with external services, and handle complex user goals through voice interaction.

**Architecture highlights:**
- LangGraph-powered agentic orchestration
- Real-time communication via **WebSockets**
- Gemini LLM for reasoning and response
- Playwright for browser-based external service integration
- **TTS** for voice output
- JWT authentication & session management
- PostgreSQL + SQLAlchemy + Redis for persistence & caching
- React frontend with FastAPI backend

</td>
<td width="40%" align="center">

```
  Voice Input
      │
  WebSocket 🔗
      │
  LangGraph Agent
  ┌───┴───────┐
  │   Tools   │
  ▼           ▼
Playwright  External APIs
  │           │
  └─────┬─────┘
        │
      Gemini
        │
   TTS Response
      🎙️
```

</td>
</tr>
</table>

**Stack:** `FastAPI` `React` `PostgreSQL` `SQLAlchemy` `Redis` `JWT` `WebSockets` `Gemini` `LangGraph` `LangChain` `Playwright` `TTS`

---

## 🛠️ Tech Stack

<div align="center">

### AI / Machine Learning

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Google%20Gemini-4285F4?style=flat-square&logo=google&logoColor=white)

### Generative AI & Retrieval

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LightRAG](https://img.shields.io/badge/LightRAG-6D28D9?style=flat-square&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B6B?style=flat-square&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0052CC?style=flat-square&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse-000000?style=flat-square&logoColor=white)

### Backend & Infrastructure

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=flat-square&logo=neo4j&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-CC0000?style=flat-square&logo=sqlalchemy&logoColor=white)

### Frontend & Tools

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

</div>

---

## 📊 GitHub Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Ayesha-Noor126&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=a78bfa&text_color=c9d1d9&rank_icon=github" alt="Ayesha's GitHub Stats" height="165"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ayesha-Noor126&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&text_color=c9d1d9&langs_count=8" alt="Most Used Languages" height="165"/>

</div>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Ayesha-Noor126&theme=tokyo-night&bg_color=0d1117&color=a78bfa&line=6d28d9&point=a78bfa&hide_border=true" alt="GitHub Contribution Graph" width="100%"/>

</div>

---

## 📬 Let's Connect

<div align="center">

I'm actively looking for opportunities in **AI/ML Engineering**, **Generative AI**, and **Intelligent Systems** — at product companies, AI-focused startups, and international clients.

If you're working on something interesting at the intersection of **retrieval, reasoning, and agents**, I'd love to talk.

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ayesha-noor-a4b305343/)
[![Email](https://img.shields.io/badge/Send%20an%20Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:noorayesha0123456@gmail.com)
[![Portfolio](https://img.shields.io/badge/View%20Portfolio-6D28D9?style=for-the-badge&logo=vercel&logoColor=white)](https://YOUR_PORTFOLIO_URL)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=100&section=footer" alt="footer wave" width="100%"/>

</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--              HOW TO CUSTOMIZE THIS README                     -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<details>
<summary>🔧 How to Customize This README</summary>

## Placeholders to Replace

| Placeholder | What to replace it with | Where |
|---|---|---|
| `YOUR_LINKEDIN_URL` | ✅ Already set to your LinkedIn | Hero badges & Connect section |
| `YOUR_EMAIL` | ✅ Already set to your email | Hero badges & Connect section |
| `YOUR_PORTFOLIO_URL` | Your portfolio website URL (if you have one) | Hero badges & Connect section |
| `Ayesha-Noor126` | Confirm this is your exact GitHub username | All `github-readme-stats` and graph URLs |

## Optional Customizations

**Add a profile photo** to the hero section — paste this inside the first `<div align="center">` block, right below the wave banner image:

```html
<img src="YOUR_IMAGE_URL" width="110" style="border-radius:50%; margin-top:-20px; border:3px solid #a78bfa;" alt="Ayesha Noor"/>
```

**Add more projects** — copy any project `<table>` block, fill in the new project details, and paste it after the last `---` divider in the Featured Projects section.

**Update Tech Stack badges** — badge format:
```
![Name](https://img.shields.io/badge/Name-COLOR?style=flat-square&logo=LOGO_ID&logoColor=white)
```
Find logo IDs at [simpleicons.org](https://simpleicons.org/).

**Change stats theme** — replace `theme=tokyonight` in the GitHub Stats URLs with: `dark`, `radical`, `merko`, `gruvbox`, `onedark`, `cobalt`, `synthwave`, `dracula`.

**Change header/footer gradient** — edit the `color=0:HEX,50:HEX,100:HEX` value in the two `capsule-render` URLs.

</details>
