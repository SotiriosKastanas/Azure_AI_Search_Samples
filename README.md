# Azure AI Search with OpenAI Embeddings & Access Control

This repo shows how to build a secure, semantic search system using Azure AI Search and Azure OpenAI.

## 📘 Notebooks

1. **Create Index**  
   - Defines the index schema (`id`, `title`, `content`, `security_groups`)  
   - Uploads dummy documents with group-based access

2. **Create an index with embeddings**  
   - Uses Azure OpenAI (ADA-3) to create embeddings
   - Creates an index with embeddings  

3. **Search with Access Control**  
   - Performs semantic search with vector similarity  
   - Filters results by group

## ⚙️ Setup

- Add a `.env` with:
  ```env
  AZURE_OPENAI_API_KEY=...
  AZURE_OPENAI_ENDPOINT=...
  AZURE_OPENAI_API_VERSION=...
  AZURE_ADA3_DEPLOYMENT_NAME=...
  AI_SEARCH_ENDPOINT=...
  AI_SEARCH_KEY=...
