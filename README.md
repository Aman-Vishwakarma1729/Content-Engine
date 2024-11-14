<h1 align="center" style="font-size: 3em;">🌟 Content Engine</h1>

## 📖 Overview
The **Content Engine** is a powerful tool designed to analyze and compare multiple PDF documents, specifically Form 10-K filings from multinational companies. Leveraging **Retrieval Augmented Generation (RAG)** techniques, it retrieves, assesses, and generates insights from these documents. Users can query and compare critical content such as risk factors, revenue figures, and business differences.

---

## 🚀 Features
- **PDF Parsing**: Efficiently extracts and processes content from Form 10-K filings.
- **Embedding**: Utilizes local embedding models to generate document embeddings for quick and effective comparison.
- **Vector Search**: Implements a local vector database for storing and retrieving document content.
- **Local LLM**: Integrates a local instance of a Large Language Model (LLM) to provide contextual insights based on user queries.
- **Interactive Chatbot**: Engage with the system through a user-friendly chatbot interface powered by **Streamlit**.
- **Comparison**: Seamlessly compare business data, revenue, risk factors, and more between documents.

---

## 🎥 Demo Video
<video width="600" controls>
  <source src="Content-Engine/Content-Engine-Demo-Video.mp4
" type="video/mp4">
</video>

---

## 🛠️ Tech Stack
- **Backend Framework**: [LangChain](https://www.langchain.com/) or [LlamaIndex](https://gpt-index.readthedocs.io/en/latest/)
- **Frontend Framework**: [Streamlit](https://streamlit.io/)
- **Vector Store**: [FAISS](https://github.com/facebookresearch/faiss) (Other options: ChromaDB, Pinecone, Weaviate)
- **Embedding Model**: [Sentence-BERT](https://www.sbert.net/) for generating document embeddings.
- **Local LLM**: [meta/llama-2-70b-chat](https://huggingface.co/meta/llama-2-70b-chat) for contextual insights.

---

## 📄 Documents Analyzed
The system is designed to analyze and compare the following Form 10-K filings:
- **Alphabet Inc. Form 10-K**
- **Tesla, Inc. Form 10-K**
- **Uber Technologies, Inc. Form 10-K**

---

## ❓ Sample Queries
- **What are the risk factors associated with Google and Tesla?**
- **What is the total revenue for Google Search?**
- **What are the differences in the business of Tesla and Uber?**

---

## ⚙️ Prerequisites
Ensure you have the following installed:
- **Python 3.8 or later**: Download it from [here](https://www.python.org/downloads/).
- **Required Libraries**: Check the `requirements.txt` file for all necessary libraries and dependencies.
- **Add API**: Include the REPLICATE_API_TOKEN in your `.env` file, which can be generated from [Replicate](https://replicate.com/).

---

## 🛠️ Setup and Use

1. **Clone this repository** to your local machine:
    ```bash
    git clone https://github.com/Aman-Vishwakarma1729/Content-Engine
    cd Content-Engine
    ```

2. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the application using Streamlit**:
    ```bash
    streamlit run app.py
    ```

---
Happy analyzing