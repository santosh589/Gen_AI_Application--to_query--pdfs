# 📚 Chat with PDF using AWS Bedrock and LangChain

This project enables interactive question-answering on PDF documents using **AWS Bedrock**, **Streamlit**, and **LangChain**. It uses **Titan Embeddings** for vectorization and supports **Claude** and **LLaMA2** language models for intelligent retrieval-based answers.

## 🚀 Features

- Upload and process PDFs for document search
- Generate vector embeddings using **Amazon Titan**
- Store vectors using **FAISS**
- Ask questions interactively via Streamlit UI
- Choose between **Claude (AI21)** and **LLaMA2 (Meta)** LLMs via AWS Bedrock
- Automatically retrieves the most relevant context for answers

## 🛠️ Requirements

- Python 3.8+
- AWS client credentials with Bedrock access enabled
- Streamlit
- Boto3
- LangChain


Install dependencies using:

```bash
pip install boto3 streamlit langchain awscli
