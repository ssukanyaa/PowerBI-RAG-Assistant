# PowerBI-RAG-Assistant
Retrieval-Augmented Generation (RAG) assistant for Power BI — powered by GPT-4o-mini and ChromaDB. Enables analysts to ask natural language questions and get concise, grounded answers directly from Power BI documentation.

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
| **Database Ops** | CRUD — Focus on **Read** |

## ✨ Features
- 🔁 **RAG Pipeline** → ChromaDB retrieval + GPT-4o-mini generation  
- 📚 **Two READ modes** in vector DBs:
  1. Inspect individual records *(ids / metadata / embeddings)*  
  2. Retrieve relevant chunks based on user query  
- 💾 **Persistent Storage** with ChromaDB  
- 🧩 Context-aware answers, grounded strictly in official docs 

## 💡 Example Use Case
Ask Power BI questions like:
> “How to share a Power BI dashboard with a group?”  
> “Is Data Refresh the same as Live Connection in Power BI?”

…and get concise, grounded answers directly from documentation!
