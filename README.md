# 🧠 Clinical Diagnosis RAG Chat

A **Retrieval-Augmented Generation (RAG)** chatbot designed to assist in clinical diagnosis. This system leverages advanced natural language processing techniques and medical knowledge sources to provide relevant, context-aware answers to diagnostic queries.

## 🚀 Overview

This application combines:
- **Bio_ClinicalBERT** for domain-specific embeddings
- **FAISS** for fast vector search
- **LLaMA-3.3-70b** (via Groq API) for response generation
- **LangChain** for orchestration
- **Streamlit** for an intuitive and interactive user interface

## 🩺 Features

- 🔍 **RAG-based Retrieval & Generation** for accurate medical response
- 📚 Uses real patient cases and diagnostic flowcharts
- ⚙️ **Evaluation module** to assess retrieval hit rate and response faithfulness
- 💬 Simple, interactive Streamlit frontend

## 🧰 Tech Stack

- **Frontend**: Streamlit  
- **Backend**: Python, LangChain  
- **LLM**: LLaMA-3.3-70b via Groq API  
- **Embeddings**: Bio_ClinicalBERT  
- **Vector Store**: FAISS  
