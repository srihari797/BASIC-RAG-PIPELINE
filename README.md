# 📚 Book RAG

A Retrieval-Augmented Generation (RAG) system that enables users to ask natural language questions about a PDF book. The project combines semantic search, CrossEncoder reranking, and a Large Language Model (LLM) to generate accurate, context-aware responses.

---

## 🚀 Features

- 📄 PDF text extraction
- ✂️ Recursive Character Text Splitting
- 🧠 Semantic embeddings using Sentence Transformers
- 🗄️ Vector storage with Qdrant
- 🔍 Semantic similarity search
- 🎯 CrossEncoder reranking for improved retrieval
- 🤖 Response generation using Microsoft Phi-3 Mini
- 💬 Interactive question-answer loop
- 📚 Context-aware answers with reduced hallucinations

---

## 🛠️ Tech Stack

- Python
- LangChain
- Sentence Transformers
- Hugging Face Transformers
- Qdrant Vector Database
- Microsoft Phi-3 Mini
- PyTorch

---

## 📖 RAG Pipeline

```text
PDF
   │
   ▼
Text Extraction
   │
   ▼
Recursive Character Chunking
   │
   ▼
Sentence Transformer Embeddings
   │
   ▼
Qdrant Vector Database
   │
   ▼
Semantic Retrieval
   │
   ▼
CrossEncoder Reranking
   │
   ▼
Phi-3 Mini (LLM)
   │
   ▼
Answer Generation
```

---

## 📂 Project Workflow

1. Load a PDF document.
2. Extract text from each page.
3. Split the text into overlapping chunks.
4. Generate embeddings for every chunk.
5. Store embeddings in Qdrant.
6. Embed the user's query.
7. Retrieve the most relevant chunks.
8. Rerank the retrieved chunks using a CrossEncoder.
9. Build a prompt using the reranked context.
10. Generate the final answer using Phi-3 Mini.

---

## 📦 Installation

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

1. Add your PDF document.
2. Run the notebook or Python script.
3. Ask questions about the document.
4. Type `exit` (or press **Ctrl + C**) to end the session.

---

## ⚠️ Note

This repository **does not include any PDF documents**. If you are using copyrighted books, please provide your own copy locally. Do not upload copyrighted PDFs or extracted text to the repository.

---

## 📜 License

This project is intended for educational and learning purposes.
