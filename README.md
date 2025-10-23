# PowerBI-RAG-Assistant
A RAG assistant that answers questions about PowerBI

## 📘 Overview
Many analysts struggle with the vast and complex **Power BI documentation**, often spending hours searching for answers to simple questions.  
This project aims to solve that challenge by building a **Retrieval-Augmented Generation (RAG)** system that allows users to ask questions and get accurate, concise answers  directly from Power BI’s official docs.

## 🎯 Objective
To create an intelligent assistant that:
- Retrieves the **most relevant documentation chunks** for a given user query  
- Generates **clear, contextual explanations** using GPT-4o-mini  
- Helps analysts learn and use Power BI more efficiently  

## ⚙️ Tech Stack
| Component | Technology |
|------------|-------------|
| **LLM** | GPT-4o-mini |
| **Vector Store** | ChromaDB |
| **Embeddings** | `text-embedding-3-large` |
| **Backend** | Python |
| **Environment** | Google Colab / Local |
| **Database Ops** | CRUD — implemented**Read** |

## ✨ Features
- **RAG pipeline**: ChromaDB retrieval + GPT-4o-mini generation
- **Two READ modes** in vector DBs:
1) Inspect individual records (ids/metadata/embeddings)
2) Retrieve relevant chunks for a user query
- **Persistent storage** with ChromaDB
