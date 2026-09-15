# RAG Chatbot with IBM watsonx.ai & Docker

An interactive Retrieval-Augmented Generation (RAG) web application built with Flask, LangChain, ChromaDB, and IBM watsonx.ai, fully containerized using Docker.

## 🚀 Features
- **Retrieval-Augmented Generation (RAG)**: Query private PDF documents and receive accurate, context-aware answers.
- **HuggingFace Embeddings**: Local document vectorization using `sentence-transformers/all-MiniLM-L6-v2`.
- **ChromaDB Vector Store**: Fast vector storage and similarity search.
- **watsonx.ai LLM**: Text generation powered by Meta Llama on IBM watsonx.ai.
- **Docker Containerization**: Fully isolated and reproducible environment for seamless deployment.

## 🛠️ Tech Stack
- **Backend**: Python 3.10, Flask
- **AI Framework**: LangChain
- **Language Model**: IBM watsonx.ai (`meta-llama/llama-4-maverick-17b-128e-instruct-fp8`)
- **Vector Database**: ChromaDB
- **Containerization**: Docker

## 📦 How to Run with Docker

### 1. Clone the repository
```bash
git clone [https://github.com/Yousrrr/rag-chatbot-docker.git](https://github.com/Yousrrr/rag-chatbot-docker.git)
cd rag-chatbot-docker