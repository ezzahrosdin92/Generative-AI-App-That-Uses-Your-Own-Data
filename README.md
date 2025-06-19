# Generative AI App That Uses Your Own Data

This repository is based on the Microsoft Learn Lab: [Use your own data in Azure AI Studio](https://microsoftlearning.github.io/mslearn-ai-studio/Instructions/04-Use-own-data.html). It walks through how to build a generative AI experience using your own files as a custom knowledge base in Azure AI Studio.

## 🔍 Overview

This app allows you to:
- Upload your own documents (PDF, DOCX, TXT, etc.)
- Ask questions related to your documents
- Get contextual answers using Azure OpenAI and RAG (Retrieval-Augmented Generation)

## 🚀 What You’ll Learn

- How to create a project in Azure AI Studio
- How to ingest your own documents and index them into a knowledge base
- How to create a chat experience using your data
- How to evaluate and improve the responses

## 🧰 Prerequisites

- Azure subscription
- Access to [Azure AI Studio](https://ai.azure.com/)
- Azure OpenAI resource
- Basic knowledge of Python and cloud concepts

## 🛠️ Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/generative-ai-app-that-uses-your-own-data.git
   cd generative-ai-app-that-uses-your-own-data
   ```

2. (Optional) Set up a Python environment and install dependencies:
   ```bash
   python -m venv env
   source env/bin/activate  # or `env\Scripts\activate` on Windows
   pip install -r requirements.txt
   ```

3. Upload your files in the `/data/sample-documents` folder.

4. Follow the steps in `deployment/azure-ai-studio-setup.md` to complete the lab in Azure AI Studio.
