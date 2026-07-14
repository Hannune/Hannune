<div align="center">

# Hi there, I'm Hannune 👋

### AI Engineer, Document Automation Without Broken Formatting

[![GitHub followers](https://img.shields.io/github/followers/Hannune?style=social)](https://github.com/Hannune)
[![Profile Views](https://komarev.com/ghpvc/?username=Hannune&color=blue)](https://github.com/Hannune)

</div>

---

## 💡 What I Do

Most companies still move documents by hand. Translating a 90-page manual. Pulling numbers out of a stack of PDFs. Checking whether the totals actually add up.

The tools that exist do half the job. ChatGPT translates well and wrecks your layout. DeepL and Google break multi-column pages and complex tables. Document AI from the big clouds extracts fields but won't tell you when the line items don't reconcile with the summary on page 3.

I build the other half.

What I've built and run:
- A format-preserving docx translation pipeline with translation memory, terminology control, and do-not-translate protection
- A causal-chain research pipeline for trade and tariff documents (2asy.ai), around 2,400 articles a day
- A multilingual entity-resolution API
- Live demos: PDF Q&A and PDF-to-JSON extraction at demo.hannune.ai

Before Hannune: LG Energy Solution, Scenera (Netflix, Sony, GS Retail). MS, Seoul National University. Two patents.

<div align="center">

![Zero API Costs](https://img.shields.io/badge/💰-Zero_API_Costs-00C7B7?style=for-the-badge)
![Complete Privacy](https://img.shields.io/badge/🔒-Complete_Privacy-4285F4?style=for-the-badge)

![Production Ready](https://img.shields.io/badge/⚡-Production_Ready-FF6F00?style=for-the-badge)
![Battle Tested](https://img.shields.io/badge/🎯-Battle_Tested-76B900?style=for-the-badge)

</div>

---

## 🏗️ Featured Projects

### 🌐 [2asy - AI News Platform](https://github.com/Hannune/2asy)
**Automated AI-powered economic news platform with dual-language support**

<img src="https://img.shields.io/badge/Ghost%20CMS-000000?style=flat&logo=ghost&logoColor=white" /> <img src="https://img.shields.io/badge/LangGraph-00ADD8?style=flat&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" />

- 🌍 Live at [2asy.ai](https://2asy.ai) (English) & [2asy.net](https://2asy.net) (Korean)
- 📰 10 daily automated publications powered by local LLMs
- 💰 **Reduced costs to 1/10-1/20** compared to cloud APIs
- 🤖 Custom summarizer with structured output & content review nodes
- 🔄 Fully containerized pipeline with vLLM, llama.cpp & LiteLLM

---

### 🏭 [LLM Infrastructure](https://github.com/Hannune/LLM-Infrastructure)
**Production-grade infrastructure for running 70+ local LLM models**

> **Architecture**
>
> ```
> Your App
>    ↓
> LiteLLM Gateway  ← Load balancing, fallbacks, metrics
>    ↓
>    ├─────────┬─────────┐
>    │         │         │
> Ollama    Ollama    vLLM  ← 70+ models across servers
> ```

**Components:**
- 🚀 **Fleet Manager** - Manage 70+ models (Qwen, Llama, Granite, Mistral)
- 🌐 **LiteLLM Gateway** - OpenAI-compatible proxy with load balancing
- 🐳 **Production Docker** - Hardened Ollama deployment
- 📊 **Monitoring Dashboard** - Real-time GPU & model status
- ⚡ **GPTQ-Marlin Optimization** - 2-3x faster inference

---

### 🧩 [LLM Components](https://github.com/Hannune/LLM-Components)
**Reusable building blocks for local LLM applications**

<img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" /> <img src="https://img.shields.io/badge/Elasticsearch-005571?style=flat&logo=elasticsearch&logoColor=white" /> <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white" />

**Featured Components:**
- 🔍 **Elasticsearch RAG Manager** - Full-stack RAG with FastAPI + Streamlit
- 🎨 **Vision-Language Models** - Local VLM experiments (Granite, LLaVA)
- 🔧 **MCP Agent Services** - Code execution, research & web scraping microservices
- 📝 **Large Text Summarizer** - Map-reduce for documents exceeding context windows
- 📰 **GDELT Collector** - Real-time global news with advanced filtering
- 🔗 **Distributed Tools** - MCP + LangChain integration

---

### 🤖 [LLM Applications](https://github.com/Hannune/LLM-Applications)
**Complete, production-ready applications built with 100% local LLMs**

**Applications:**
- 🔬 **AI Research-Code Pipeline** - Multi-agent system (Researcher → Developer → Validator)
- 🏠 **Korean Real Estate AI** - Market analysis with government data
- 🤖 **Agent Integration Examples** - Router patterns, MCP tools & A2A workflows

> **Multi-Agent Architecture**
>
> ```
> User Query → Supervisor Agent
>                   ↓
>       ┌───────────┼───────────┐
>       │           │           │
>   Research    Developer   Analysis
>    Agent       Agent        Agent
>       │           │           │
>       └───────────┴───────────┘
>                   ↓
>          Final Result (100% Local)
> ```

---

### 🔬 [LangGraph Research Agent](https://github.com/Hannune/Langgraph-Research-Agent)
**Intelligent research agent with supervisor-driven architecture**

<img src="https://img.shields.io/badge/LangGraph-00ADD8?style=flat&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/GPT--Researcher-00C853?style=flat&logo=ai&logoColor=white" /> <img src="https://img.shields.io/badge/ChromaDB-FF6F00?style=flat&logo=database&logoColor=white" />

- 💬 Interactive chat with intelligent research triggers
- 🔬 Deep research via GPT-Researcher + local document RAG
- 📚 Multi-format document processing (PDF, DOCX, TXT, MD, JSON)
- 🗄️ Conversation management with SQLite persistence
- 🌐 Hybrid research: Web + Local documents

---

### 🛠️ [Beginner Projects](https://github.com/Hannune)

<details>
<summary><b>📦 Simple LLM Chatbot</b> - Cost-effective chatbot with pay-per-use APIs</summary>
<br>

- Streamlit frontend + FastAPI backend
- Multiple API provider support (OpenAI, Ollama, Anthropic)
- Modular architecture for easy customization
</details>

<details>
<summary><b>🔍 Simple RAG (No LangChain)</b> - Lightweight RAG implementation</summary>
<br>

- Pure Python RAG without frameworks
- Support for PDF, PPTX, DOCX uploads
- Semantic search with vector embeddings
</details>

<details>
<summary><b>🖥️ Local LLM Server Setup</b> - Comprehensive server setup guide</summary>
<br>

- Ubuntu 22.04 server configuration
- Docker containerization
- GPU support (NVIDIA & AMD)
- Vector database setup
</details>

---

## 🛠️ Tech Stack

### Infrastructure & Deployment
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![NVIDIA](https://img.shields.io/badge/NVIDIA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)

### LLM & AI Frameworks
![LangChain](https://img.shields.io/badge/LangChain-00ADD8?style=for-the-badge&logo=chainlink&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ai&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-FF6F00?style=for-the-badge&logo=ai&logoColor=white)
![LiteLLM](https://img.shields.io/badge/LiteLLM-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)

### Backend & APIs
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

### Databases & Search
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F00?style=for-the-badge&logo=database&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

### CMS & Frontend
![Ghost](https://img.shields.io/badge/Ghost-000000?style=for-the-badge&logo=ghost&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)

---

## 📊 Architecture Philosophy

### 🎯 Core Principles

![100% Local Execution](https://img.shields.io/badge/✅_100%25_Local_Execution-Zero_API_Dependencies-00C7B7?style=for-the-badge)

![Production Ready](https://img.shields.io/badge/✅_Production_Ready-Battle_tested_in_real_use-4285F4?style=for-the-badge)

![Privacy First](https://img.shields.io/badge/✅_Privacy_First-Your_data_stays_on_your_infra-9C27B0?style=for-the-badge)

![Cost Optimized](https://img.shields.io/badge/✅_Cost_Optimized-Save_90--95%25_vs_cloud_APIs-FF6F00?style=for-the-badge)

![Hardware Optimized](https://img.shields.io/badge/✅_Hardware_Optimized-Maximum_GPU_performance-76B900?style=for-the-badge)

![Modular Design](https://img.shields.io/badge/✅_Modular_Design-Reusable_components-E91E63?style=for-the-badge)

---

## 📈 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Hannune&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Hannune&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

## 🎬 Demo

[![Web Crawling → Structured Extraction → Knowledge Graph](https://img.youtube.com/vi/j5xz0k9i-LA/maxresdefault.jpg)](https://youtu.be/j5xz0k9i-LA)

*Raw web page → Markdown → Structured data extraction → Neo4j knowledge graph — 100% local LLMs*

### Here's additional demo you can try on my [website](https://demo.hannune.ai).

---

## 🎯 What Makes My Work Unique

### 💰 **Cost Efficiency**
From **$1000+/month** cloud bills → **~$50/month** electricity (95% savings)

### 🏭 **Production Grade**
Not just demos - real applications serving real users:
- [2asy.ai](https://2asy.ai) - 10 daily automated publications
- Multi-server deployments with 99.9% uptime
- Handling 50+ concurrent users

### 🔒 **Privacy First**
- Zero data sent to third parties
- Complete control over your infrastructure
- GDPR/compliance ready out of the box

### ⚡ **Performance Optimized**
- GPTQ-Marlin kernels: 2-3x faster inference
- Smart model routing across hardware
- Load balancing & automatic failover

---

## 🌟 Recent Highlights

- 🚀 Deployed production AI news platform serving 1000+ daily visitors
- 📊 Built monitoring infrastructure for 70+ LLM models
- 🔧 Created reusable MCP services for agent automation
- 🎨 Implemented local vision-language model experiments
- 📰 Developed real-time global news collection system with GDELT

---

## 📫 Connect With Me

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-Hannune-181717?style=for-the-badge&logo=github)](https://github.com/Hannune)
[![Website](https://img.shields.io/badge/Website-2asy.ai-00C7B7?style=for-the-badge&logo=google-chrome&logoColor=white)](https://2asy.ai)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hannune.tech@hotmail.com)

</div>

---

<div align="center">

### 💡 Interested in running your own AI infrastructure?

Check out my repositories for comprehensive guides, production-ready code, and real-world examples!

**⭐ Star my repos if you find them useful!**

---

*Building the future of local AI, one model at a time* 🚀

</div>
