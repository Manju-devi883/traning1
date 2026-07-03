# Day 3 - APIs, MCP & Transformer Architecture

## Objective
The objective of this session was to understand how modern AI applications communicate with external services, how AI models connect with tools using MCP, and how Transformer Architecture powers Large Language Models (LLMs).

---

# 1. APIs (Application Programming Interface)

## What is an API?
An API is a communication bridge that allows two different applications to exchange data and services without knowing each other's internal implementation.

### Why APIs are Important?
- Connect applications
- Fetch real-time data
- Integrate AI models with applications
- Automate tasks

### API Workflow

User
↓
Application
↓
API Request
↓
Server
↓
API Response
↓
Application
↓
User

### Real-World Examples
- Weather API
- Gemini API
- OpenAI API
- Google Maps API

---

# 2. Model Context Protocol (MCP)

## What is MCP?
Model Context Protocol (MCP) is an open standard that enables AI models to securely communicate with external tools, databases, APIs, and file systems.

### Why MCP?
Without MCP:
- Every AI application needs custom integrations.

With MCP:
- One standard protocol works with multiple tools.

### MCP Architecture

User
↓
AI Client
↓
MCP Client
↓
MCP Server
↓
Tools / APIs / Database / Files

### Real-World Example
ChatGPT receives:
> "Read my PDF and summarize it."

Instead of reading files directly,

ChatGPT

↓

MCP Client

↓

MCP Server

↓

PDF Tool

↓

Summary Returned

---

# 3. Transformer Architecture

## What is a Transformer?
Transformer is the deep learning architecture behind modern Large Language Models like ChatGPT, Gemini, and Claude.

### Why Transformers?
Older models processed words one by one.

Transformers use **Self-Attention**, allowing them to understand relationships between all words in a sentence simultaneously.

### Main Components
- Input Embeddings
- Positional Encoding
- Self-Attention
- Feed Forward Network
- Encoder
- Decoder

### Transformer Workflow

Input Sentence

↓

Embedding

↓

Self-Attention

↓

Feed Forward Network

↓

Output

### Applications
- ChatGPT
- Gemini
- Claude
- Translation
- Text Summarization
- Code Generation

---

# Key Learnings

- APIs enable communication between applications.
- MCP standardizes communication between AI models and external tools.
- Transformer Architecture is the foundation of modern LLMs.
- Self-Attention helps models understand context efficiently.

---

# Summary

Day 3 focused on three core technologies of modern AI development. APIs enable communication between applications, MCP provides a standardized way for AI models to access external tools, and Transformer Architecture powers state-of-the-art Large Language Models. These concepts form the backbone of modern AI systems and are essential for building real-world AI applications.
