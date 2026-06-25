# Lesson 02: LLM Fundamentals 🧠

## 🎯 Learning Objectives
- Understand tokens, context windows, and temperature
- Master prompt engineering for agents
- Learn system prompts, few-shot examples, and chain-of-thought
- Understand why prompt quality directly affects agent quality

## 🧠 Key Concepts

### Tokens
- LLMs don't read words — they read **tokens** (word pieces)
- "Hello" = 1 token | "Avnish" = 2 tokens | Code is very token-heavy
- GPT-4o: 128k context window = ~100,000 words

### Temperature
- `0.0` = Deterministic (best for agents/code)
- `0.7` = Creative (good for writing)  
- `1.0+` = Very random (usually bad for agents)

### Prompt Patterns for Agents
1. **Zero-shot**: Just ask directly
2. **Few-shot**: Give examples first  
3. **Chain-of-Thought (CoT)**: "Think step by step"
4. **ReAct**: "Reason, then Act"

## ⏭️ Next
Lesson 03: AutoGen setup — let the framework handle the agent loop!
