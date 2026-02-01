# Contract Advisor – Legal Q&A System (RAG)

This project implements a Legal Contract Question & Answer system using a
Retrieval-Augmented Generation (RAG) approach. The system allows users to
upload legal contract documents in PDF format and ask questions based on
their content.

---

## Project Overview

The goal of this project is to build a simple and effective document-based
Q&A system for legal contracts. Instead of relying only on a language model,
the system retrieves relevant sections from contract documents and uses them
as context to generate accurate answers.

---

## Key Features

- Legal contract Q&A using Retrieval-Augmented Generation (RAG)
- PDF document ingestion and text extraction
- Text chunking and vector-based semantic search
- Context-aware answer generation using GPT models
- Simple chat-based user interface
- Basic evaluation support for answer quality

---

## Tech Stack

- Python
- LangChain
- OpenAI API (GPT models + embeddings)
- Flask (backend API)
- PyPDF2 (PDF processing)
- RAGAS (evaluation – optional)
- React (frontend)

---

## How It Works

1. Legal contract PDFs are uploaded to the system
2. Text is extracted and split into smaller chunks
3. Chunks are converted into embeddings and stored in a vector database
4. User questions are matched with relevant contract sections
5. The retrieved context is passed to the language model to generate answers

---

## Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/your-username/contract-advisor-rag.git
