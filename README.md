# 🧠 Corrective RAG Agent with LangGraph, Tavily, and Vectorstore
![corrective RAG image](https://github.com/user-attachments/assets/7394064f-2f5a-40c7-b6ed-a6f38799cf43)

This project implements a **Corrective Retrieval-Augmented Generation (RAG) pipeline** using [LangGraph](https://github.com/langchain-ai/langgraph), [Tavily Search](https://www.tavily.com/), and LangChain's built-in vectorstore system (Chroma). The agent intelligently routes questions through a Retriever or Web Crawler and generates final answers using LLMs.

---

## 🚀 Features

- ✅ Conditional execution using LangGraph
- 🔍 Dual RAG sources: **vector retriever** + **Tavily web search**
- 🧠 Structured grading logic to choose between query rewrite or generation
- ✂️ Chunking & embedding with `text-embedding-3-large`
- 🌐 Real-time info retrieval with Tavily
- 🧩 Modular OOP-friendly design (LLM, Router, Retriever, Generator)

---

## 🛠️ Requirements

Install dependencies using `pip`:

```bash
pip install langgraph langchain langchain-openai langchainhub langchain-community tavily


