#  RAG Chatbot – AI-Powered PDF Q&A System

A Retrieval-Augmented Generation (RAG) chatbot that lets you upload PDF documents and ask natural language questions, powered by **LangChain**, **OpenAI**, **Google Generative AI**, and **Hugging Face** models.

##  Features

-  **PDF Parsing** – Extracts and chunks text from PDF files
-  **Vector Embeddings** – Uses Hugging Face embeddings for document representation
-  **FAISS** – Vector store for fast semantic retrieval
-  **LLM-Backed Q&A** – Uses LLMs (OpenAI, Gemma, LLaMA, or Gemini) for response generation
-  **LangChain** – Handles RAG pipeline and document retrieval
-  **Streamlit Interface** – Intuitive UI to upload files and ask questions

##  Tech Stack

 UI            Streamlit 
 LLMs          OpenAI GPT, Google Gemini (Generative AI), LLaMA, Gemma 
 Embeddings    Hugging Face (e.g., BGE, E5, MiniLM) 
 Vector Store  FAISS 
 RAG Pipeline  LangChain 
 PDF Parsing   PyMuPDF (fitz) 

## Installation

Clone the repository:

```bash
git clone https://github.com/software-dev0309/ai-rag-chatbot.git
cd rag-chatbot

```

## Run the setup

python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
streamlit run app.py
