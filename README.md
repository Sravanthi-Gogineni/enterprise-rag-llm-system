Enterprise RAG LLM System 🚀

Production-grade Retrieval-Augmented Generation (RAG) system for enterprise document intelligence.

📌 Overview

This project enables intelligent question-answering over enterprise documents using LLMs and vector search.

🏗 Architecture

User → API → Retriever → Vector DB → LLM → Response

⚙️ Features

Document ingestion (PDF, DOCX)
Embeddings and vector search
Context-aware LLM responses
Prompt optimization
Logging and monitoring

🛠 Tech Stack

Python
FastAPI
OpenAI / Azure OpenAI
FAISS

▶️ Run Locally

pip install -r requirements.txt
uvicorn app.main:app --reload
