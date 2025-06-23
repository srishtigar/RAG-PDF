# RAG-Q&A-Conversation

A powerful Retrieval-Augmented Generation (RAG) application that enables conversational question-answering with uploaded PDF documents while maintaining chat history. Built with Streamlit, LangChain, and Groq API for seamless document interaction and intelligent responses.

# Features
- PDF Upload & Processing: Upload multiple PDF files simultaneously for analysis

- Conversational RAG: Ask questions about your documents with context-aware responses

- Chat History Management: Maintains conversation history across sessions with session IDs

- History-Aware Retrieval: References previous conversation context for better responses

- Real-time Processing: Instant document processing and embedding generation

- Multiple Document Support: Handle multiple PDFs in a single session

- Secure API Integration: Protected API key input for Groq services

 # Technologies Used
 
 | Component              | Technology                        |
|------------------------|-----------------------------------|
| **Frontend**           | Streamlit                         |
| **LLM Framework**      | LangChain                         |
| **Language Model**     | Groq API (Gemma2-9b-It)           |
| **Embeddings**         | HuggingFace (all-MiniLM-L6-v2)    |
| **Vector Database**    | Chroma                            |
| **Document Processing**| PyPDF, RecursiveCharacterTextSplitter |
| **Chat History**       | LangChain ChatMessageHistory       |


# Prerequisites

### OpenAI
OPENAI_API_KEY

### LangChain
LANGCHAIN_API_KEY
LANGCHAIN_PROJECT

### HuggingFace
HF_TOKEN
HUGGINGFACEHUB_API_TOKEN

### Groq
GROQ_API_KEY







