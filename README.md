RAG-Based Conversational AI with Memory using Streamlit & LangChain
<br>
📌 Overview
This project implements a Retrieval-Augmented Generation (RAG) Conversational AI system using LangChain, Streamlit, and Groq API (LLM). It enhances chatbot capabilities by retrieving relevant documents and maintaining contextual memory across interactions.

<br>

🔹 Features
<br>
✅ Conversational Memory – Tracks user history using RunnableWithMessageHistory.
<br>
✅ RAG-based Retrieval – Uses VectorStoreRetriever to fetch relevant documents.
<br>
✅ History-Aware Querying – Enhances retrieval via create_history_aware_retriever().
<br>
✅ Streamlit UI – Interactive chatbot interface with session-based memory.
<br>
✅ Groq API for LLM – Utilizes Groq’s API to generate responses.
<br>

🛠 Tech Stack
<br>
Backend: Python, LangChain, Groq API
<br>
Frontend: Streamlit
<br>
Vector Store: FAISS / ChromaDB (for document retrieval)
<br>
Memory Management: BaseChatMessageHistory
