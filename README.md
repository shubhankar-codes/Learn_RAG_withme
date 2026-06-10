# RAG Learning Journey

A hands-on learning repository documenting my journey of understanding and implementing Retrieval-Augmented Generation (RAG) systems from scratch using Python, Google Colab, Sentence Transformers, and Large Language Models.

## Overview

This repository contains my practical experiments, notes, code implementations, and learnings while exploring the complete RAG pipeline.

The objective is to understand how modern AI assistants retrieve information from external knowledge sources and generate context-aware responses.

## What I Learned

### 1. Document Processing

* Loading PDF documents
* Extracting text from PDFs
* Understanding document structure
* Preparing data for retrieval

### 2. Text Chunking

* Recursive Character Text Splitting
* Chunk size optimization
* Chunk overlap techniques
* Trade-offs between large and small chunks

### 3. Embeddings

* What embeddings are
* How text is converted into vectors
* Semantic similarity concepts
* Sentence Transformer models

### 4. Vector Representations

* Embedding dimensions
* Vector comparison
* Similarity scoring
* Understanding semantic search

### 5. Retrieval

* Cosine Similarity
* Top-K Retrieval
* Query Embeddings
* Relevant Context Extraction

### 6. RAG Pipeline

* User Query Processing
* Retrieval Stage
* Context Construction
* LLM Augmentation
* Response Generation

## RAG Architecture

```text
PDF Documents
      │
      ▼
Document Loader
      │
      ▼
Text Chunking
      │
      ▼
Embeddings Generation
      │
      ▼
Vector Store
      │
      ▼
User Query
      │
      ▼
Query Embedding
      │
      ▼
Similarity Search
      │
      ▼
Relevant Chunks
      │
      ▼
Large Language Model
      │
      ▼
Final Answer
```

## Technologies Used

* Python
* Google Colab
* LangChain
* PyPDF
* Sentence Transformers
* Scikit-Learn
* NumPy
* Gemini API

## Learning Project

For practical implementation, I used legal documents to understand:

* PDF ingestion
* Chunk generation
* Embedding creation
* Semantic search
* Retrieval-Augmented Generation

  Note: Repository structure will be share shortly

## Key Concepts Covered

* Retrieval-Augmented Generation (RAG)
* Semantic Search
* Embeddings
* Vector Databases
* Cosine Similarity
* Chunking Strategies
* Context Retrieval
* LLM Integration

## Future Improvements

* MongoDB Atlas Vector Search
* ChromaDB Integration
* Hybrid Search (BM25 + Vector Search)
* Re-ranking
* Agentic RAG
* FastAPI Backend
* React Frontend
* Production Deployment

## Who Can Benefit From This Repository?

This repository is intended for:

* Students learning Generative AI
* Developers starting with RAG
* AI/ML Enthusiasts
* Software Engineers exploring LLM applications
* Anyone interested in building AI-powered search systems
* and this is goto repostitory for me too 😊

## Learning Outcome

By following this repository, you will understand:

* How RAG works internally
* How embeddings are generated
* How semantic search retrieves information
* How LLMs use retrieved context
* How to build a basic RAG system from scratch

## Author

Shubhankar Mishra

B.Tech Student | Software Development & Generative AI Enthusiast

Currently learning:

* Retrieval-Augmented Generation (RAG)
* Agentic AI Systems
* FastAPI
* MongoDB
* Golang
* Open Source Contributions
