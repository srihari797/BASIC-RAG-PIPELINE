# Book RAG

A Retrieval-Augmented Generation (RAG) system built using:

- LangChain
- Sentence Transformers
- CrossEncoder Reranking
- ChromaDB
- Phi-3 Mini
- Hugging Face Transformers

## Pipeline

PDF
→ Recursive Chunking
→ Embeddings
→ Qdrant DB
→ Retrieval
→ CrossEncoder Reranking
→ Phi-3 Mini
→ Answer Generation

## Features

- PDF-based knowledge base
- Semantic search
- CrossEncoder reranking
- Interactive question-answer loop
- Local LLM inference
