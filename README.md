# customer-support-medical-chatbot-system
About the Project

The Customer Support Medical Chatbot System is an AI-powered chatbot designed to provide users with relevant and informative responses to medical-related queries. The system uses a Retrieval-Augmented Generation (RAG) approach to retrieve relevant information from a structured medical knowledge base and generate context-aware responses.

The medical dataset contains information related to diseases, symptoms, medicines, consultations, and treatment-related information. The data is converted into vector embeddings and stored in ChromaDB, enabling the system to perform semantic similarity-based retrieval when a user submits a query.

The chatbot processes the user's question, searches the vector database for relevant medical information, and uses the retrieved context to provide an appropriate response. This approach helps the chatbot provide responses based on the available knowledge base rather than relying solely on predefined responses.

Key Features
🤖 AI-powered medical support chatbot
🔎 Semantic search using vector embeddings
📚 Medical knowledge-base retrieval
🗄️ ChromaDB vector database
🔄 Retrieval-Augmented Generation (RAG)
💬 Natural-language query processing
🏥 Disease and symptom-related information retrieval
⚕️ Medicine and consultation-related information
Technology Stack
Python
Flask
RAG
Sentence Transformers
ChromaDB
Pandas
HTML/CSS/JavaScript (if used in your frontend)
How It Works
User Query
    ↓
Query Processing
    ↓
Generate Query Embedding
    ↓
Search ChromaDB
    ↓
Retrieve Relevant Medical Information
    ↓
RAG Pipeline
    ↓
Generate Response
    ↓
Display Response to User
Project Objective

The main objective of this project is to develop an intelligent medical support chatbot that can efficiently retrieve relevant information from a medical knowledge base and provide users with useful, context-aware responses through a conversational interface.
