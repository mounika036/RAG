# Multimodal RAG

A multimodal Retrieval-Augmented Generation (RAG) project that processes text and images from PDF documents and uses them to provide context-aware answers.

## Features

* Extracts text and images from PDF documents using Docling.
* Generates summaries for document content.
* Creates semantic descriptions for images.
* Generates embeddings for efficient semantic search.
* Stores embeddings in ChromaDB.
* Uses MMR retrieval to improve document diversity.
* Uses a BGE cross-encoder for reranking retrieved results.
* Generates answers using retrieved context and an LLM.

## Tech Stack

* Python
* LangChain
* Docling
* ChromaDB
* Hugging Face
* Sentence Transformers
* Gemini
* LLMs

## Workflow

PDF → Text & Image Extraction → Summarization → Embeddings → ChromaDB → MMR Retrieval → Reranking → LLM → Answer

## How It Works

1. A PDF document is processed using Docling.
2. Text and images are extracted from the document.
3. Text content is summarized and images are converted into semantic descriptions.
4. The processed content is converted into vector embeddings.
5. Embeddings are stored in ChromaDB.
6. Relevant documents are retrieved using MMR.
7. A BGE cross-encoder reranks the retrieved results.
8. The most relevant context is provided to the LLM.
9. The LLM generates a context-grounded response.

## Purpose

This project demonstrates how RAG can be extended to handle both text and visual information from documents, while improving retrieval quality through MMR and cross-encoder reranking.
