# RAG_based_Policy_Chatbot
![Intro](images/chatbot.jpg)

A Retrieval-Augmented Generation (RAG) chatbot that answers user questions based on company subscription policies or internal documentation.
The system uses embeddings + vector search to retrieve relevant policy sections and feeds them into an LLM to produce accurate, grounded answers.

✨ Features

🔍 Document ingestion pipeline (PDF → text → chunking → embeddings)

🧠 Vector retrieval using FAISS/Chroma

💬 Chat interface powered by Streamlit

🔐 Context-grounded answers based strictly on the retrieved policy documents


🛠️ **Tech Stack**

Python

LangChain (or LlamaIndex)

ChromaDB (vector store)

Llama 3

Streamlit


