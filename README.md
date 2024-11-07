# Customized-chatbot-with-Azure-OpenAI-and-RAG
The goal of this project is to create a ChatGPT-like over private organization documents using RAG (Retrieval Augmented Generation). From user's query, chunks of document containing information related to the question is retrieved and feed to the LLM model to help it narrow down the context and provide factual responses.

The indexing pipeline and backend is written in Python. It uses Azure OpenAI Service to access a GPT model (gpt-35-turbo), and Azure AI Search for data indexing and retrieval.

The repo won't include the custom data as it is not intended for public access, although there will be reference to other repos that contain sample data. The indexing pipeline is designed around PDFs documents written in Vietnamese.

# Features
- Chat (multi-turn) and Q&A (single turn) interfaces
- Renders citations and thought process for each answer
- Integrates Azure AI Search for indexing and retrieval of documents
- Optimized for low operation cost

## Architecture
![Query (2)](https://github.com/user-attachments/assets/1aeaee8f-349c-48e4-aac0-56db2b520905)

# Azure Services Used
- Azure subscription 
- Azure AI Search Services
- Azure OpenAI Serviecs
- Azure App Services

:shipit:
