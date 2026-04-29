# Hi, I'm Rishi 👋

**MSc AI & Automation · University West, Sweden**
Building production-grade LLM systems with evaluation-first engineering practices.

---

## 🔨 What I Build

I focus on the **engineering layer of AI** — not just prompting models, but building the retrieval pipelines, caching strategies, agent architectures, and evaluation harnesses that make AI systems actually work in production.

---

## 🚀 Featured Projects

### 🔬 [context-lens](https://github.com/Rishi-Bethi-007/context-lens)

**Open-source Python library** that diagnoses context degradation in LLM agents — finds where your agent's memory breaks, at what token count, and how to fix it.
`LangGraph` · `Python` · `NIAH probes` · `6 classifiers` · `HTML reports`
→ `pip install reguliq-diagnostics` · [209 tests passing]

> Research finding: LLMs don't degrade uniformly — they anchor to the beginning. Position 10–15% = 83% accuracy. Every other position ≤25%.

### 🇪🇺 [EU Regulatory Intelligence Agent](https://github.com/Rishi-Bethi-007/EU-Regulatory-Intelligence-Agent)
**Production multi-agent AI system** helping European SMEs navigate GDPR and EU AI Act compliance obligations.
`LangGraph` · `FastAPI` · `React/Vite` · `Supabase pgvector` · `AWS ECS Fargate` · `Claude Sonnet` · `GPT-4o`
→ **[Live Demo](https://reguliq.eu)** · API: `api.reguliq.eu/health`

> 6-agent pipeline: Risk Classifier → Planner → Researcher (RAG+MCP) → Analyst → Critic (GPT-4o) → Synthesizer
> Multilingual EN/SV/DE · XAI decision traces · PDF export · GDPR Art. 15/17 endpoints · SHA-256 audit chain

### 🎥 [YouTube RAG Chatbot](https://github.com/Rishi-Bethi-007/YouTube-RAG-Chatbot)
Production RAG system for querying YouTube videos and playlists via natural language.
`Pinecone` · `PostgreSQL` · `Redis` · `OpenAI` · `RAGAS` · `Streamlit`
→ [Live Demo](https://youtube-multi-video-playlist-rag-be5foxpo9w7rvcffelo3dk.streamlit.app/)

### 🏎️ [FIA Regulations RAG System](https://github.com/Rishi-Bethi-007/FIA-Regulations-Production-Grade-RAG-System)
Metadata-aware RAG over FIA motorsport regulations (F1/F2/F3, 2018–2026) with cross-encoder reranking, Redis caching, and a faithfulness evaluation harness.
`Pinecone` · `SQLite` · `Redis` · `cross-encoder` · `OpenAI`

### ✍️ [Blog Writing Agent](https://github.com/Rishi-Bethi-007/Blog-Writing-Agent)
Multi-step AI agent that researches, outlines, writes, and refines full blog posts.
`LangGraph` · `OpenAI` · `Streamlit`
→ [Live Demo](https://blog-writing-agent.streamlit.app/)

---

## 🛠️ Core Stack

```
LLMs & Agents    │ Claude Sonnet, GPT-4o, LangChain, LangGraph
Vector Storage   │ Supabase pgvector, Pinecone
Databases        │ PostgreSQL, SQLite, Redis
Evaluation       │ Custom RAGAS-equivalent, LLM-as-judge, latency profiling
Infrastructure   │ AWS ECS Fargate, Docker, Vercel, Streamlit Cloud
Languages        │ Python, TypeScript
```

---

## 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/rishi-bethi)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:rishibethi2001@gmail.com)
[![Live Project](https://img.shields.io/badge/Live%20Project-reguliq.eu-blue?style=flat)](https://reguliq.eu)
