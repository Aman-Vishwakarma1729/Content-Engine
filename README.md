# Content Engine

## Overview
This Content Engine analyzes and compares multiple PDF documents, specifically Form 10-K filings from multinational companies. It utilizes **Retrieval Augmented Generation (RAG)** techniques to retrieve, assess, and generate insights from the documents. The engine allows for querying and comparing content from these PDFs, such as risk factors, revenue figures, and business differences.

## Features
- **PDF Parsing**: Extracts and processes content from Form 10-K filings.
- **Embedding**: Uses local embedding models to generate document embeddings for efficient comparison.
- **Vector Search**: Stores and retrieves document content using a local vector database.
- **Local LLM**: A local instance of a Large Language Model (LLM) provides contextual insights based on user queries.
- **Interactive Chatbot**: Users can interact with the system via a chatbot interface built with **Streamlit**.
- **Comparison**: Allows users to compare business data, revenue, risk factors, and more between the documents.

## Tech Stack
- **Backend Framework**: [LangChain](https://www.langchain.com/) or [LlamaIndex](https://gpt-index.readthedocs.io/en/latest/)
- **Frontend Framework**: [Streamlit](https://streamlit.io/)
- **Vector Store**: [FAISS](https://github.com/facebookresearch/faiss) (Other options: ChromaDB, Pinecone, Weaviate)
- **Embedding Model**: [Sentence-BERT](https://www.sbert.net/) for generating document embeddings
- **Local LLM**: [meta/llama-2-70b-chat](https://huggingface.co/meta/llama-2-70b-chat) for contextual insights

## Documents Analyzed
The system is built to analyze and compare the following Form 10-K filings:
- **Alphabet Inc. Form 10-K**
- **Tesla, Inc. Form 10-K**
- **Uber Technologies, Inc. Form 10-K**

## Sample Queries
- **What are the risk factors associated with Google and Tesla?**
- **What is the total revenue for Google Search?**
- **What are the differences in the business of Tesla and Uber?**

## Setup Instructions

### 1. Prerequisites
Make sure you have the following installed:
- Python 3.8 or later
- Required libraries (see `requirements.txt`)

### 2. Install Dependencies
```bash
pip install -r requirements.txt



