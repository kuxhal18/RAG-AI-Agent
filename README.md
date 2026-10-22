# RAG AI Agent 🤖

An AI-powered Retrieval-Augmented Generation (RAG) agent built using n8n, Google Gemini, Supabase Vector Store, and OpenAI embeddings.

## 📌 Project Overview

This project combines a Large Language Model (LLM) with document retrieval to provide context-aware responses based on information stored in a vector database.

## 🚀 Features

- AI-powered question answering
- Retrieval-Augmented Generation (RAG)
- Google Gemini integration
- Supabase Vector Store for document retrieval
- OpenAI embeddings for semantic search
- PostgreSQL-based conversation memory
- Google Drive integration for document ingestion

## 🛠️ Technologies Used

- n8n
- Google Gemini
- Supabase
- PostgreSQL
- OpenAI Embeddings
- Retrieval-Augmented Generation (RAG)

## ⚙️ Workflow

1. Upload or select a document in Google Drive.
2. Download the document through the n8n workflow.
3. Split the document into smaller text chunks.
4. Generate embeddings using OpenAI.
5. Store document embeddings in Supabase Vector Store.
6. Retrieve relevant information when a user asks a question.
7. Generate a response using the Google Gemini model.

## 🔧 Setup Requirements

- An n8n instance
- A Google Gemini API key
- An OpenAI API key for embeddings
- A Supabase project with the required vector database configuration
- Google Drive credentials

## 📥 Importing the Workflow

1. Open n8n.
2. Select the option to import a workflow from a file.
3. Choose `RAG Agent.json`.
4. Configure the required credentials in n8n.
5. Verify the Supabase tables and vector store settings.
6. Test the workflow with a sample document and question.

## 🔐 Security

API keys, passwords, and other secrets should be stored securely in n8n credentials and must not be committed to GitHub.

## 📚 Learning Outcomes

- Understanding RAG architecture
- Connecting LLMs with vector databases
- Working with embeddings and document chunking
- Building AI workflows using n8n
- Integrating external services

## 👨‍💻 Author

Kushal Kumar M.

---

⭐ If you find this project useful, consider giving the repository a star!