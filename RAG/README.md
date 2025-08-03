RAG Document Parsing with LangChain, OpenAI & FAISS
This project implements a Retrieval-Augmented Generation (RAG) pipeline using the LangChain framework, FAISS vector store, and OpenAI LLMs. It enables intelligent document parsing and question answering from various document formats including .pdf, .txt, .csv, and .docx.

Features
Supports multiple file types: .pdf, .txt, .csv, .docx

Semantic search using FAISS vector store

Chat-based Q&A using OpenAI GPT models

Retrieval-Augmented Generation pipeline via LangChain

Converts documents into chunks and indexes them

Simple interactive input for queries


Tech Stack
Tool	                Purpose
Python	        Main programming language
LangChain	      LLM orchestration & RAG logic
OpenAI	        LLM backend (ChatGPT models)
FAISS          	Vector similarity search engine
PyMuPDF	        PDF parsing
Pandas	        CSV reading
Docx2txt	      Word document parsing
dotenv	        Environment variable management


How It Works
Load documents from the specified directory.

Split documents into semantic chunks (max 1000 characters).

Embed chunks using OpenAI's text-embedding-ada-002 model.

Store vectors in a local FAISS index.

Query using LangChain with retriever + OpenAI LLM.

For questions or collaboration, feel free to reach out:

Author: Vikas Pathak
Email: vikaspatha0911@gmail.com
