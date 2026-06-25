# Lesson 13: Capstone — Interview Copilot Architecture 🏗️

## 🎯 What We're Building
A complete **Interview Preparation Copilot** — an AI agent that acts as your personal DSA coach.

## 🌟 Features
- 🎤 Voice OR text input (your choice)
- 🤖 Multi-agent system (Interviewer + Hint Giver + Evaluator)
- 💡 Adaptive hints — 3 levels (nudge → guide → explain)
- 🐍 Live code execution and feedback
- 📊 Performance tracking across sessions
- 🧠 Long-term memory (remembers your weak spots)

## 🏛️ Architecture
```
┌─────────────────────────────────────────────────┐
│              INTERVIEW COPILOT                  │
│                                                 │
│  Input Layer:  Voice (Whisper) | Text           │
│       ↓                                         │
│  Orchestrator Agent (decides flow)              │
│       ↓           ↓           ↓                 │
│  [Interviewer] [HintGiver] [Evaluator]          │
│       ↓                                         │
│  Code Sandbox (execute Python live)             │
│       ↓                                         │
│  Memory Layer (ChromaDB + session history)      │
│       ↓                                         │
│  Dashboard (Streamlit — scores, progress)       │
└─────────────────────────────────────────────────┘
```

## 📦 This Lesson Covers
- Project setup and folder structure
- Data models (Problem, Session, Attempt)
- Problem bank setup (50 DSA questions)
- Base agent configuration
