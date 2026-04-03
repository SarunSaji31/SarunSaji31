# Hi, I'm Sarun Saji 👋

Backend Developer specializing in Python, Django, FastAPI, and Android Kotlin. Passionate about building AI-integrated mobile experiences and production-grade backend systems.

📍 Aalborg, Denmark | Open to Backend, Mobile AI, and AI Automation roles

---

## 🚀 Featured Project: Voxly AI Voice Keyboard

**Voxly** is an intelligent voice-powered AI keyboard for Android that lets you **speak naturally** and get real-time transcription + translation, powered by your **own cloned voice**.

### Key Features
- **Voice Typing with Translation**: Speak in any supported language → instant transcription + translation to English (or target language) directly into any app.
- **Personal Voice Cloning**: Clone your voice using ElevenLabs and hear your messages spoken back in **your own voice**.
- **Multilingual TTS**: Generate natural, casual spoken audio in 20+ languages (including colloquial Tamil, Hinglish-style Hindi, etc.).
- **Send Voice Messages**: Directly send the cloned voice audio into chats (WhatsApp, Telegram, etc.) or via share sheet.
- **Credit System**: Freemium model with Firebase Auth and usage-based credits.

### Tech Stack

**Mobile (Android)**
- Custom **InputMethodService (IME)** in Kotlin
- Real-time audio recording with MediaRecorder
- Firebase Authentication (ID Token)
- OkHttp + Coroutines for backend communication
- Rich content insertion (`InputContentInfoCompat`)

**Backend (FastAPI)**
- **Gemini (Google)** for speech-to-text and natural language translation
- **ElevenLabs** for high-quality voice cloning and turbo TTS (`eleven_turbo_v2_5`)
- Firebase Admin SDK + Firestore (user credits & profiles)
- Credit deduction system (1 credit for translation, 3 for voice generation)
- Voice profile management (upload samples → clone → reuse)

**Supported Languages** (Transcription + Natural TTS)
English, Chinese, Japanese, Korean, German, French, Russian, Spanish, Portuguese, Italian, Hindi, Arabic, Tamil, and many more.

**Live Backend**: `https://api.sarunsaji.com`

---

## 🧠 Featured Project: Personal RAG System

A fully self-hosted Retrieval-Augmented Generation (RAG) system running on a Hetzner VPS.

**Live at**: https://rag.sarunsaji.com

- Upload PDFs, text, and links into named collections
- Query via clean Streamlit UI or terminal
- Fully private local LLM (**Qwen 7B** via Ollama) + ChromaDB
- Nginx + Let's Encrypt SSL

### Architecture

Browser / Terminal
│
▼
rag.sarunsaji.com (Nginx + SSL)
│
▼
Streamlit Frontend
│
▼
FastAPI Backend
│
▼
ChromaDB Vector Store + Ollama (Qwen 7B)


### Stack
| Layer       | Technology                          |
|-------------|-------------------------------------|
| Frontend    | Streamlit                           |
| Backend     | FastAPI + LangChain                 |
| Vector DB   | ChromaDB                            |
| LLM         | Qwen 7B via Ollama                  |
| Proxy       | Nginx + Let's Encrypt               |
| Server      | Hetzner VPS (Ubuntu)                |

---

## About Me

I love building systems that bridge **mobile interfaces** with **powerful AI backends**. My focus is on creating delightful, intelligent user experiences powered by modern LLMs, voice AI, and clean architecture.

Core interests:
- AI-powered mobile tools (especially Android)
- Natural voice interfaces and voice cloning
- Self-hosted & private AI systems
- Clean, scalable backend architecture
- Workflow automation

---

## Technical Skills

### Mobile & AI
- **Kotlin** + Android SDK (Custom IME development)
- AI Integration: Gemini, ElevenLabs, real-time audio pipelines
- Firebase Authentication

### Backend & Languages
- **Python** — FastAPI, Django
- JavaScript (integrations)
- PostgreSQL, MySQL, Firestore

### AI & ML
- Google Gemini (multimodal)
- ElevenLabs Voice Cloning & TTS
- LangChain, ChromaDB, Ollama
- RAG pipelines, embeddings, local LLMs

### Automation & DevOps
- n8n (automation workflows)
- Docker, Linux, Nginx
- Deployment: Hetzner, AWS (EC2, S3), Gunicorn
- Git & GitHub

---

## Projects

- **Voxly AI Voice Keyboard** — Voice-to-text + personal voice cloning keyboard (Kotlin + FastAPI + Gemini + ElevenLabs)
- **Personal RAG System** — Fully self-hosted document Q&A with local LLM — [rag.sarunsaji.com](https://rag.sarunsaji.com)
- **Aalborg Wind/Price Data Pipeline** — Real-time data ingestion and automation
- **Driver & Fleet Management Systems** — Django-based operational dashboards
- **n8n Recovery & Backup Systems** — Automated infrastructure reliability protocols

---

## Career Focus

Actively seeking opportunities as:

- **Backend Developer** (Python / FastAPI / Django)
- **Mobile AI Developer** (Android / Kotlin + AI)
- **AI Systems Engineer** (Voice AI, RAG, LLM applications)
- **Automation & Operations Engineer**

---

## Contact

📧 Personal: sarunsaji31@gmail.com  
📧 Work: info@sarunsaji.com  
🌐 Portfolio: https://www.sarunsaji.com  
🔗 LinkedIn: https://www.linkedin.com/in/sarun-saji-523b54169
