# 🧠 AI Cognitive Architecture Platform

> A brain-inspired AI system that simulates human cognition through interconnected modules — perception, attention, memory, reasoning, planning, emotion, and imagination.

![Status](https://img.shields.io/badge/status-in--development-yellow)
![Python](https://img.shields.io/badge/Python-3.10+-blue)
![React](https://img.shields.io/badge/React-18-61DAFB)
![FastAPI](https://img.shields.io/badge/FastAPI-0.100+-009688)
![Gemini](https://img.shields.io/badge/Gemini-API-4285F4)
![License](https://img.shields.io/badge/license-MIT-green)

---

## 📖 Overview

**AI Cognitive Architecture Platform** is not just another chatbot. It is a modular system designed to mimic how the human brain processes information. Every user input passes through a specialized pipeline of 8 cognitive modules, each contributing to a final, thought-out response. 

Unlike black-box LLMs, this platform aims to visualize **HOW** the AI thinks, step-by-step, in real-time.

---

## 🧩 The 8 Cognitive Modules

| # | Module | Function |
|---|--------|----------|
| 1 | **Perception** | Understands raw user input and extracts intent. |
| 2 | **Attention** | Identifies key focus areas and keywords. |
| 3 | **Memory** | Retrieves and stores context (short & long term). |
| 4 | **Emotion** | Detects and tags the emotional tone of the input. |
| 5 | **Reasoning** | Builds logical chains and deduces meaning. |
| 6 | **Planning** | Generates actionable steps to respond. |
| 7 | **Imagination** | Explores creative alternatives and ideas. |
| 8 | **Orchestrator** | Coordinates all modules into a final, coherent output. |

---

## 🏗️ Tech Stack

**Backend**
- Python 3.10+
- FastAPI (High-performance API)
- SQLAlchemy + SQLite (Database & ORM)
- Google Gemini API (Cognitive Engine)

**Frontend**
- React 18 + Vite (Fast build tool)
- TailwindCSS (Modern styling)
- Axios (API requests)
- Framer Motion (Smooth animations)

---

## ⚙️ How It Works

```text
User Input
    ↓
[ Perception ] ➔ Clean & Parse
    ↓
[ Attention  ] ➔ Extract Keywords
    ↓
[ Memory     ] ➔ Fetch Context
    ↓
[ Reasoning  ] ➔ Logical Chain
    ↓
[ Planning   ] ➔ Action Steps
    ↓
[ Imagination] ➔ Creative Ideas
    ↓
[ Emotion    ] ➔ Tone Tagging
    ↓
[ Orchestrator ] ➔ Final Response
    ↓
Frontend renders live pipeline



cd backend
python -m venv venv
# Windows: venv\Scripts\activate
# Mac/Linux: source venv/bin/activate
pip install -r requirements.txt
cp .env.example .env  # Add your GEMINI_API_KEY here
python run.py

cd frontend
npm install
npm run dev
