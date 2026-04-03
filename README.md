# Hi, I'm Sarun Saji 👋
Backend Developer specializing in Python, Django, and Android Kotlin, with hands-on experience building AI-integrated applications, production backend systems, and automated workflows.

📍 Aalborg, Denmark | Open to Backend, Mobile, & AI Automation roles

---

## 🚀 Featured Project: Voxly AI
**Voxly** is a voice-powered AI keyboard for Android that provides real-time transcription and seamless text input.
- **Mobile Core**: Developed a custom Android Input Method Service (IME) using **Kotlin** and **Jetpack Compose**.
- **AI Integration**: Implemented a real-time audio pipeline that records voice data and processes it via a hosted AI backend on **Hugging Face Spaces**.
- **Cloud Infrastructure**: Integrated **Firebase Auth** and Google Identity Services for secure user personalization.

---

## 🧠 Featured Project: Personal RAG System
A fully self-hosted Retrieval-Augmented Generation (RAG) system running on a Hetzner VPS.

**Live at**: https://rag.sarunsaji.com

- **Document Intelligence**: Upload PDFs, text, and links into named collections and query them instantly via a clean Streamlit UI or terminal.
- **Local LLM Integration**: Combines ChromaDB vector search with a local **Qwen 7B** model via **Ollama** for fully private, offline-capable AI.
- **Production Infrastructure**: FastAPI backend + Streamlit frontend, secured with Nginx reverse proxy and Let's Encrypt SSL.
- **Terminal Access**: Query your knowledge base from anywhere via simple shell aliases.

### Architecture
```
Browser / Terminal
      │
      ▼
rag.sarunsaji.com (Nginx + SSL)
      │
      ▼
Streamlit Frontend (port 8085)
      │
      ▼
FastAPI RAG Backend (port 8002)
      │
      ▼
ChromaDB Vector Store (port 8003)
```

### Stack
| Layer | Tech |
|---|---|
| Frontend | Streamlit |
| Backend | FastAPI + LangChain |
| Vector DB | ChromaDB |
| LLM | Qwen 7B via Ollama |
| Proxy | Nginx + Let's Encrypt |
| Server | Hetzner VPS (Ubuntu) |

---

## About Me
I am a developer focused on bridging the gap between **mobile interfaces and powerful backend AI**. I design systems that handle complex operational workflows, from server-side logic to user-facing mobile tools.

My work focuses on:
- **AI-Driven Mobile Tools**: Creating specialized Android applications that leverage LLMs and transcription models.
- **Clean Backend Architecture**: Designing stable server-side systems using Python and Django.
- **Workflow Automation**: Building n8n pipelines to replace manual operational tasks.
- **Self-Hosted AI Systems**: Building private, production-grade RAG pipelines with local LLMs.

---

## Technical Skills

### Mobile & AI
- **Kotlin** & Android SDK
- **Jetpack Compose** (Modern UI)
- **AI Integration**: Hugging Face API, Real-time transcription

### Backend & Languages
- **Python** & **Django**, **FastAPI**
- **JavaScript** (integrations)
- **PostgreSQL**, MySQL, & Django ORM

### AI & ML
- **LangChain**, **ChromaDB**, **Ollama**
- **RAG pipelines**, vector search, local LLM deployment
- **sentence-transformers**, embeddings

### Automation & DevOps
- **n8n** (Automated reporting, backup systems, & recovery protocols)
- **Docker** & Linux
- **Deployment**: Nginx, Gunicorn, AWS (EC2, S3), & RunPod (GPU Fine-tuning)
- **Git & GitHub**

---

## Projects
- **Voxly Android AI Keyboard**: Real-time voice-to-text transcription engine.
- **Personal RAG System**: Self-hosted document intelligence with local LLM — https://rag.sarunsaji.com
- **Aalborg Wind/Price Data Pipeline**: n8n-driven real-time data ingestion to Hugging Face Spaces.
- **Driver & Fleet Management Systems**: Django-based operational dashboards.
- **n8n Recovery & Backup Systems**: Automated protocols for database and infrastructure reliability.

---

## Career Focus
I am actively seeking opportunities as a:
- **Backend Developer (Python / Django)**
- **Mobile AI Developer (Android / Kotlin)**
- **Automation & Operations Engineer**
- **AI Systems Developer (RAG, LLM, local AI)**

---

## Contact
📧 Personal: sarunsaji31@gmail.com
📧 Work: info@sarunsaji.com
🌐 Portfolio: https://www.sarunsaji.com
🔗 LinkedIn: https://www.linkedin.com/in/sarunsaji
