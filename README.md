# Hi, I'm Hannune

> Building production-grade AI infrastructure that runs 100% locally - zero API costs, complete privacy

Based in Seoul, I create open-source tools and applications for running powerful LLM systems on your own hardware. From multi-agent research pipelines to real-time news platforms - everything powered by local models.

## What I Build

**Infrastructure** → Deploy and manage local LLMs at scale
**Components** → Reusable building blocks for AI applications
**Applications** → Complete, production-ready AI systems

All projects share a common philosophy:
- **Privacy First** - Your data never leaves your infrastructure
- **Zero API Costs** - Run unlimited inference locally
- **Production Ready** - Battle-tested, not just demos
- **Docker-First** - Easy deployment and scaling

## Featured Projects

### [LLM Infrastructure](https://github.com/Hannune/LLM-Infrastructure)
Production-grade infrastructure for running 70+ local LLM models

Manage Qwen, Llama, Granite, Mistral and more across multiple servers with unified APIs, load balancing, and real-time monitoring.

**Key Components:**
- Ollama Fleet Manager - Route requests across multiple servers
- LiteLLM Gateway - OpenAI-compatible proxy with fallbacks
- Multi-Server Monitoring - Real-time dashboard for GPU/model status
- vLLM Optimizations - 2-3x faster inference with GPTQ-Marlin

---

### [LLM Components](https://github.com/Hannune/LLM-Components)
Reusable, plug-and-play components for building AI applications

Production-tested building blocks: RAG systems, vision models, distributed tools, and more.

**Includes:**
- **Elasticsearch RAG Manager** - Full-stack document search with FastAPI + Streamlit
- **Vision Model Experiments** - Local VLM integration (Granite Vision, Ollama VLMs)
- **MCP Distributed Tools** - LangChain + MCP integration for agent tool use
- **Agent Services** - Open Interpreter, GPT Researcher, Crawl4AI microservices
- **Large Text Summarizer** - Handle 100K+ token documents with map-reduce
- **GDELT News Collector** - Real-time global news data with advanced filtering

---

### [LLM Applications](https://github.com/Hannune/LLM-Applications)
Complete, production-ready applications built with 100% local LLMs

End-to-end applications demonstrating real-world use cases.

**Applications:**
- **AI Research-Code Pipeline** - Multi-agent system: research → code → validation
- **Korean Real Estate Analyzer** - LLM analysis of government transaction data
- **Agent Integration Examples** - Routers, MCP tools, agent-to-agent coordination

---

### [2asy](https://github.com/Hannune/2asy) - Live AI News Platform
Automated economic news websites powered entirely by local LLMs

Two production sites publishing AI-summarized news daily:
- [2asy.ai](https://2asy.ai) - English content, 10x daily
- [2asy.net](https://2asy.net) - Korean content, optimized for commute hours

**Tech:** Ghost CMS + LangGraph + vLLM/llama.cpp + Docker schedulers
**Cost Savings:** 1/10th to 1/20th of cloud LLM costs (just electricity!)

---

### [Langgraph Research Agent](https://github.com/Hannune/Langgraph-Research-Agent)
Intelligent research agent with supervisor-driven architecture

Streamlit chat interface with automated deep research capabilities. The supervisor agent decides when to trigger comprehensive research using GPT-Researcher + local document RAG.

**Features:** Interactive chat, document processing (PDF/DOCX/TXT), ChromaDB vector search, conversation management

## Tech Stack

**Languages & Frameworks**
- Python (Primary)
- LangChain & LangGraph (Agent orchestration)
- FastAPI (Backend APIs)
- Streamlit (Dashboards & UIs)

**LLM Infrastructure**
- Ollama (Model serving)
- vLLM (High-performance inference)
- LiteLLM (API gateway)
- llama.cpp (Lightweight serving)

**Databases & Storage**
- Elasticsearch (Search & vectors)
- ChromaDB (Vector embeddings)
- SQLite (Application data)

**DevOps & Tools**
- Docker & Docker Compose
- MCP (Model Context Protocol)
- Ghost CMS
- n8n (Workflow automation)

## Repository Guide

My repositories are organized into three layers:

```
┌─────────────────────────────────────────┐
│         LLM Applications                │  ← Full apps using components
│  (Research agents, Real estate, 2asy)  │
└────────────────┬────────────────────────┘
                 │
┌────────────────▼────────────────────────┐
│         LLM Components                  │  ← Reusable building blocks
│  (RAG, Vision, Tools, Summarization)   │
└────────────────┬────────────────────────┘
                 │
┌────────────────▼────────────────────────┐
│       LLM Infrastructure                │  ← Foundation & deployment
│  (Ollama, vLLM, Monitoring, Gateway)   │
└─────────────────────────────────────────┘
```

**Start Here:**
- New to local LLMs? → [local-LLM-server-setup](https://github.com/Hannune/local-LLM-server-setup)
- Want quick examples? → [simple-LLM-chatbot](https://github.com/Hannune/simple-LLM-chatbot) or [simple-RAG-without-langchain](https://github.com/Hannune/simple-RAG-without-langchain)
- Building production systems? → Start with Infrastructure, use Components, reference Applications

## Current Focus

- Expanding MCP tool integrations for distributed agent systems
- Optimizing inference performance with quantization and kernel optimizations
- Building monitoring and observability tools for LLM infrastructure
- Exploring agent-to-agent (A2A) workflows with n8n

## GitHub Stats

[![GitHub Repo Card](https://github-readme-stats.vercel.app/api/pin/?username=Hannune&repo=Hannune)](https://github.com/Hannune/Hannune)

## Let's Connect

I'm passionate about making powerful AI accessible without cloud dependencies. If you're interested in:
- Running LLMs locally for production use
- Building cost-efficient AI applications
- Contributing to open-source AI infrastructure

Feel free to explore my repositories, open issues, or reach out!

---

**Building the future of AI infrastructure - one local model at a time**
