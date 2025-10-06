# 💬 Azure AI Q&A Project

An intelligent Q&A chatbot built with **Azure OpenAI**, **Azure AI Search**, and **Streamlit**.  
This project demonstrates how to build a retrieval-based chatbot using your own dataset — stored in **Azure Table Storage** — to answer user questions with context.

---

## 🚀 Features

- 🔍 Retrieves answers using **Azure AI Search**
- 🧠 Uses **Azure OpenAI GPT-3.5 Turbo** for natural language responses
- 💾 Uploads CSV data to **Azure Table Storage**
- 💬 Interactive **Streamlit chat interface**
- ⚡ Easily deployable on Azure or Streamlit Cloud

---

## 🧩 Project Structure

Azure-AI-QA-Proj/
├── azurechatbotdemo.py # Streamlit chatbot app
├── datainsert.py # Uploads CSV data into Azure Table
├── azurelib2.csv # Dataset (Q&A pairs)
├── requirements.txt # Python dependencies
├── .gitignore # Ignored files and folders
└── README.md # Documentation

## Create a .env file in the root directory or set environment variables manually:

AZURE_AI_SEARCH_SERVICE_NAME=your-search-service-name
AZURE_AI_SEARCH_INDEX_NAME=your-index-name
AZURE_AI_SEARCH_API_KEY=your-search-api-key
AZURE_OPENAI_ENDPOINT=https://your-endpoint.openai.azure.com/
AZURE_OPENAI_API_KEY=your-openai-api-key
