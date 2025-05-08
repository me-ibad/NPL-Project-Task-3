# 🔍 Local Document Retriever with FAISS & SentenceTransformers

A lightweight semantic search tool that lets you query your own documents using natural language. It uses SentenceTransformers to embed text chunks and FAISS for fast similarity search.

Built for use in Google Colab or local Python environments.

---

## 🚀 Features

- 🧠 Semantic document search with natural language queries
- 📄 Supports .txt, .md, and .pdf file formats
- ⚡ Fast FAISS indexing for similarity search
- 🧩 Automatic chunking with overlap
- 💾 Save & load index for reuse
- ✅ Tested with real-world documents
- 🔧 Easy to customize and extend

---

## 🛠 Installation

Run this in your Colab or local environment:

```bash
pip install sentence-transformers faiss-cpu PyPDF2
