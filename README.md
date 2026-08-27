# 📄 Document Q&A with GPT-4o (RAG)

A Retrieval-Augmented Generation (RAG) system that allows users to ask questions about PDF documents and receive context-grounded answers using GPT-4o.

## 🚀 Project Overview

This project combines document retrieval with a Large Language Model to answer questions from a given PDF document.

### How it works

1. Loads the PDF document
2. Splits the document into smaller text chunks
3. Converts text chunks into vector embeddings
4. Stores embeddings in FAISS
5. Retrieves relevant information for a question
6. Uses GPT-4o to generate a context-grounded answer

## 🛠️ Technologies Used

- Python
- LangChain
- OpenAI GPT-4o
- HuggingFace Embeddings
- FAISS
- Sentence Transformers
- Unstructured
- Jupyter Notebook / Google Colab

## ⚙️ Architecture

PDF Document
↓
Document Loading
↓
Text Chunking
↓
HuggingFace Embeddings
↓
FAISS Vector Database
↓
Similarity Retrieval
↓
GPT-4o
↓
Context-Grounded Answer

## 💡 Example Questions

- What is this document about?
- What is the model architecture discussed in this paper?
- What are the applications of attention in the model?

## 🔐 API Key

An OpenAI API key is required to run the GPT-4o component.

**Never upload your real API key to GitHub.**

## ▶️ How to Run

Install the required dependencies:

```bash
pip install transformers sentence-transformers langchain langchain-community langchain-openai faiss-cpu unstructured
