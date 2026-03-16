# RAG Document QA System

This project is a Retrieval Augmented Generation (RAG) based AI application that allows users to ask questions from documents.

The system processes documents, converts them into embeddings, and stores them in a FAISS vector database. When a user asks a question, the system retrieves relevant document chunks using cosine similarity and sends them to a Large Language Model to generate accurate answers.

Tech Stack:
Python
LangChain
OpenAI API
FAISS
FastAPI
