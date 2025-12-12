# Ollama-RAG-chatbot-for-medium-CPU-devices

# PDF RAG Chatbot with Ollama and Flask

This project is a **PDF-based Retrieval-Augmented Generation (RAG) chatbot** using **Ollama** for LLM responses, **FAISS** for vector search, and **Flask** for a web interface. Users can upload PDFs, and the chatbot can answer questions using the content from these PDFs.

---

## Features

- PDF text extraction using `PyPDF2`
- Chunking large documents for better retrieval
- Sentence embeddings with `SentenceTransformers`
- Fast similarity search using `FAISS`
- Chat interface with **Ollama LLM** (`llama2` or `llama3.2`)
- Maintains chat history (`chat_history.json`)
- Health check endpoint for Ollama server

---

## Folder Structure

