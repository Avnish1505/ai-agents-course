<div align="center">
  <h1>🤖 AI Agents Course: Zero to Production 🚀</h1>
  <p>
    <strong>From Fundamentals to a Production-Ready Interview Preparation Copilot</strong>
  </p>
  <p>
    <a href="./LICENSE.md"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License"></a>
    <a href="https://www.python.org/downloads/release/python-3110/"><img src="https://img.shields.io/badge/Python-3.11+-yellow.svg" alt="Python Version"></a>
    <a href="https://microsoft.github.io/autogen/"><img src="https://img.shields.io/badge/Built%20with-AutoGen-purple.svg" alt="AutoGen"></a>
    <a href="./CONTRIBUTING.md"><img src="https://img.shields.io/badge/PRs-Welcome-brightgreen.svg" alt="PRs Welcome"></a>
  </p>
</div>

> **Built with:** Microsoft AutoGen v0.4+ | Azure OpenAI GPT-4o | Python 3.11+
> **Author:** Avnish Singh | **Pen Name:**  Avnish

---

## 🌟 About This Course

This course is a complete guide to designing, building, and deploying autonomous AI agents. We start from the absolute basics and progressively build up to a portfolio-worthy capstone project. By the end, you won't just understand agents—you'll be ready to build production-grade AI systems.

---

## 🏆 Capstone Project: The Interview Copilot

A production-ready DSA (Data Structures & Algorithms) practice agent that helps you prepare for technical interviews.

| Feature | Description |
|---|---|
| 🎤 **Voice/Text Input** | Practice hands-free using the Whisper API. |
| 💡 **Adaptive Hints** | Get smart, tiered hints that don't spoil the solution. |
| 🐍 **Live Code Sandbox** | Write and execute your Python solutions in a secure environment. |
| 🧠 **Persistent Memory** | The agent remembers your weak spots across sessions using ChromaDB. |
| 📈 **Performance Dashboard** | A Streamlit dashboard to visualize your progress. |
| 🔥 **Difficulty Scaling** | Problems get harder as your skills improve. |

---

## 🛠️ Tech Stack

- **Agent Framework:** `Microsoft AutoGen`
- **LLM:** `Azure OpenAI GPT-4o` & `Whisper`
- **Memory:** `ChromaDB` (Vector Database)
- **Production API:** `FastAPI`
- **Deployment:** `Docker` & `Azure Container Apps`
- **Frontend:** `Streamlit`

---

## 🚀 Getting Started

Follow these steps to set up the project locally.

```bash
# 1. Clone the repository
git clone https://github.com/Avnish1505/ai-agents-course.git
cd ai-agents-course

# 2. Create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Set up environment variables
cp .env.example .env
# Fill in your Azure OpenAI keys in .env
```

## 🔑 Environment Variables
```env
AZURE_OPENAI_API_KEY=your_key_here
AZURE_OPENAI_ENDPOINT=https://your-resource.openai.azure.com/
AZURE_OPENAI_DEPLOYMENT=gpt-4o
AZURE_OPENAI_API_VERSION=2024-02-15-preview
AZURE_WHISPER_DEPLOYMENT=whisper
```
