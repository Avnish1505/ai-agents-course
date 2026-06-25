# Lesson 01: What is an AI Agent? 🤖

## 🎯 Learning Objectives
By the end of this lesson, you will understand:
- What makes something an "AI Agent" vs a simple chatbot
- The Perception → Reasoning → Action loop
- Types of agents (reflex, goal-based, learning)
- Why agents are the future of AI applications

## 🧠 Core Concept

An **AI Agent** is a system that:
1. **Perceives** its environment (text, voice, data, APIs)
2. **Reasons** using an LLM to decide what to do
3. **Acts** by calling tools, writing code, or responding
4. **Learns** from feedback to improve over time

```
┌─────────────────────────────────────────┐
│           AI AGENT LOOP                 │
│                                         │
│  Environment → [Perceive] → [Reason]    │
│                                ↓        │
│  Environment ← [Act]    ← [Plan]        │
└─────────────────────────────────────────┘
```

## 🆚 Chatbot vs Agent

| Feature | Chatbot | AI Agent |
|---------|---------|----------|
| Memory | ❌ Stateless | ✅ Has memory |
| Tools | ❌ Text only | ✅ Calls APIs, runs code |
| Planning | ❌ Single response | ✅ Multi-step reasoning |
| Goals | ❌ Answer question | ✅ Achieve objective |

## 📚 Key Terms
- **LLM**: Large Language Model (the "brain")
- **Tool**: External function the agent can call
- **ReAct**: Reasoning + Acting pattern
- **Orchestrator**: Controls multiple agents

## ⏭️ Next Lesson
Lesson 02: LLM Fundamentals — how the brain actually works
