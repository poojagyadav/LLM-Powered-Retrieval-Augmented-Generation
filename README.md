# LLM-Powered RAG System

An educational project exploring **Retrieval-Augmented Generation (RAG)** by combining Large Language Models (LLMs) with semantic search to retrieve relevant information and generate context-aware responses.

## Overview

This project was developed as a hands-on learning experience to understand the fundamentals of Retrieval-Augmented Generation (RAG) and explore how LLMs can use external knowledge to generate more relevant responses.

It demonstrates how input data is processed, divided into smaller chunks, converted into semantic embeddings, and stored in a vector database. User queries are matched with relevant content using cosine similarity, and the retrieved context is passed to an LLM to generate context-aware responses.

## Features

- Data loading and processing
- Text chunking using Recursive Character Text Splitter
- Embedding generation using Sentence Transformers
- Persistent vector storage with ChromaDB
- Semantic search and retrieval using cosine similarity
- LLM-powered context-aware response generation

## Tech Stack

- Python
- LangChain
- Sentence Transformers
- ChromaDB
- Large Language Models (LLMs)

## Dependencies

Install the required Python libraries using:

```bash
pip install langchain langchain-community langchain-text-splitters sentence-transformers chromadb notebook
```

## RAG Workflow

1. Load and process input data.
2. Split content into smaller chunks.
3. Generate semantic embeddings.
4. Store embeddings in ChromaDB.
5. Convert user queries into embeddings.
6. Retrieve relevant chunks using cosine similarity.
7. Pass retrieved context to the LLM.
8. Generate a context-aware response.

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/poojagyadav/LLM-Powered-Retrieval-Augmented-Generation.git
   ```

2. Navigate to the project directory:

   ```bash
   cd LLM-Powered-Retrieval-Augmented-Generation
   ```

3. Install the dependencies:

   ```bash
   pip install langchain langchain-community langchain-text-splitters sentence-transformers chromadb notebook
   ```

4. Open the notebook:

   ```bash
   jupyter notebook RAG_pipeline.ipynb
   ```

5. Execute the notebook cells sequentially.

## Conclusion

This project was developed for educational purposes as a hands-on learning experience to explore the fundamentals of Retrieval-Augmented Generation (RAG). While building it, I gained practical experience with text chunking, embeddings, vector databases, semantic search, cosine similarity, and integrating LLMs to generate context-aware responses. It helped me strengthen my understanding of how RAG pipelines work and how external knowledge can enhance LLM-generated responses.
