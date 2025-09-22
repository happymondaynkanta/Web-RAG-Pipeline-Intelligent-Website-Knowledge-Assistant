# Web-RAG-Pipeline-Intelligent-Website-Knowledge-Assistant
An end-to-end Retrieval-Augmented Generation (RAG) pipeline that crawls websites, cleans and extracts text, splits documents into chunks, generates semantic embeddings with HuggingFace, stores them in ChromaDB.  Built with LangChain, HuggingFace Sentence-Transformers, and Chroma.


## 🔄 RAG Pipeline Flow

![RAG Pipeline Flowchart](rag_pipeline_flowchart.svg)


---

# Web RAG Pipeline: Intelligent Website Knowledge Assistant

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![LangChain](https://img.shields.io/badge/LangChain-Framework-orange.svg)
![ChromaDB](https://img.shields.io/badge/Chroma-VectorDB-green.svg)
![HuggingFace](https://img.shields.io/badge/Embeddings-HuggingFace-yellow.svg)

## 📖 Overview

This repository demonstrates how to build a **Retrieval-Augmented Generation (RAG) system** that transforms static website content into an **interactive AI-powered knowledge assistant**.

The pipeline:

1. **Crawls a target website** recursively.
2. **Cleans and extracts meaningful text** using HTML parsing.
3. **Splits documents into manageable chunks** for downstream tasks.
4. **Generates embeddings** with HuggingFace’s Sentence-Transformers.
5. **Stores embeddings in ChromaDB** for semantic similarity search.
6. **Retrieves context-aware documents** in response to user queries.
7. **Generates grounded answers** using a large language model, with sources cited.

This project highlights practical experience in **LangChain, ChromaDB, HuggingFace embeddings, and RAG architectures**, making it directly relevant for AI/ML engineering and applied NLP roles.

---

## ✨ Features

* 🌐 **Recursive Website Crawler** with domain and depth control
* 🧹 **HTML Cleaner & Extractor** to remove irrelevant tags
* ✂️ **Document Chunking** with overlap for context preservation
* 🧠 **Embeddings via HuggingFace** (`all-MiniLM-L6-v2`)
* 📦 **ChromaDB Integration** for efficient semantic retrieval
* 🔍 **Retriever Interface** for top-k relevant results
* 🤖 **RAG Answering Function** with context-grounded LLM outputs
* 📑 **Source Transparency** — every answer includes references

---


## 🎯 Applications

* **Education** → Course catalog assistants for universities
* **Corporate Knowledge Bases** → Internal semantic search tools
* **Research Portals** → Summarization and Q\&A over academic repositories
* **Customer Support** → AI assistants with verifiable, grounded responses



## 🧑‍💻 Author

Developed by Happy Nkanta Monday — AI/ML Engineer specializing in Retrieval-Augmented Generation, Large Language Model, Deep Learning, and Applied Machine Learning.

If you find this project useful, feel free to ⭐ star the repo and ![Read the brief](Technical Report with code.pdf).
```





