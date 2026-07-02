# 🤖 AI Agent with RAG using Databricks

An end-to-end Retrieval-Augmented Generation (RAG) application built using Databricks. The project demonstrates how to create an AI-powered assistant capable of answering user queries by retrieving relevant information from a collection of PDF documents using vector search and Large Language Models (LLMs).

---

## 📌 Project Overview

This project implements a Retrieval-Augmented Generation (RAG) pipeline that combines document retrieval with LLM-based reasoning to generate context-aware responses.

The workflow includes:
- Loading and processing PDF documents
- Creating document embeddings
- Building a vector search index
- Retrieving relevant document chunks
- Generating responses using Databricks Foundation Models
- Interacting with the AI Agent through Databricks Playground

---

## 🚀 Features

- 📄 PDF document ingestion
- ✂️ Document chunking
- 🔍 Semantic search using vector embeddings
- 🤖 AI-powered question answering
- 📚 Retrieval-Augmented Generation (RAG)
- ☁️ Built entirely on Databricks

---

## 🛠️ Tech Stack

- Python
- Databricks
- Databricks Foundation Models
- GPT OSS / Claude Models
- Vector Search
- PyPDF2
- Pandas
- MLflow

---

## 📂 Project Structure

```text
AI-Agent-RAG-with-Databricks/
│
├── notebooks/
│   ├── 01_LLM_Interaction.ipynb
│   ├── 02_Document_Processing.ipynb
│   ├── 03_Vector_Search.ipynb
│   ├── 04_RAG_Pipeline.ipynb
│   └── 05_AI_Agent.ipynb
│
├── data/
│   ├── *.csv
│   └── product_docs/
│
├── screenshots/
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## ⚙️ Workflow

1. Upload PDF documents.
2. Extract text from documents.
3. Split documents into chunks.
4. Generate embeddings for each chunk.
5. Store embeddings in a Vector Search Index.
6. Retrieve the most relevant document chunks for a user query.
7. Send the retrieved context to a Large Language Model.
8. Generate an accurate and context-aware response.

---

## 📈 Future Enhancements

- Multi-document retrieval
- Conversation memory
- Web-based user interface using Streamlit
- Support for multiple LLM providers
- Deployment as a production AI assistant

