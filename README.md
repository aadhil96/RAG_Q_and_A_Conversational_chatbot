# Conversational RAG Q&A with PDF Uploads and Chat History

This project is a **Conversational Retrieval-Augmented Generation (RAG)** web application built using **Streamlit**, **LangChain**, and **Groq's Gemma2-9b-It** model. The app allows users to upload PDFs, create embeddings of their content, and chat interactively with the uploaded documents. It also maintains a chat history for more context-aware and efficient interactions with the content.

## Features

- **Upload PDFs**: Users can upload multiple PDF files, and the content is processed into text for question-answering.
- **Chat History**: User conversations are stored and referenced to provide better contextual answers.
- **Conversational Q&A**: Users can ask questions related to the uploaded documents, and the system will respond with concise and accurate answers using retrieval-augmented generation.
- **Groq Integration**: Utilizes Groq's **Gemma2-9b-It** model for processing and answering user queries based on the PDF contents.
- **Embeddings & Vector Store**: The content from the PDFs is split and indexed using **OpenAIEmbeddings** and stored in **Chroma** for retrieval.
  
## Requirements

1. Python 3.8 or higher
2. Required Libraries:
   - Streamlit
   - LangChain
   - Groq API
   - Chroma
   - OpenAIEmbeddings
   - PyPDFLoader
   - dotenv (for managing API keys)
   - Other dependencies (listed in `requirements.txt`)
