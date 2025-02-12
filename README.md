RAG-Based Conversational AI with Memory using Streamlit & LangChain
📌 Overview
This project implements a Retrieval-Augmented Generation (RAG) Conversational AI system using LangChain, Streamlit, and Groq API (LLM). It enhances chatbot capabilities by retrieving relevant documents and maintaining contextual memory across interactions.

🔹 Features
✅ Conversational Memory – Tracks user history using RunnableWithMessageHistory.
✅ RAG-based Retrieval – Uses VectorStoreRetriever to fetch relevant documents.
✅ History-Aware Querying – Enhances retrieval via create_history_aware_retriever().
✅ Streamlit UI – Interactive chatbot interface with session-based memory.
✅ Groq API for LLM – Utilizes Groq’s API to generate responses.

🛠 Tech Stack
Backend: Python, LangChain, Groq API
Frontend: Streamlit
Vector Store: FAISS / ChromaDB (for document retrieval)
Memory Management: BaseChatMessageHistory
