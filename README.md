# ChatBot with Appointment Booking 🤖📅
Smart RAG Chatbot with integrated appointment booking system. Answers questions from any document (PDF, text, etc.) and provides conversational form for collecting user information and scheduling appointments. Features natural language date parsing, phone/email validation, and seamless integration with Pinecone vector database and Groq AI API.

## 🌟 Features

### Document Intelligence
- **Any Document Support**: Upload PDFs, text files, or paste content directly
- **Smart Q&A**: Ask questions about your documents and get accurate answers
- **Pinecone Vector Database**: Stores and retrieves document content efficiently

### Appointment Booking System
- **Conversational Form**: Natural conversation flow for collecting user information
- **Smart Validation**: Validates email, phone numbers, and dates automatically
- **Natural Language Understanding**: Understands dates like "next Monday" or "December 15th"
- **Automatic Detection**: Triggers appointment booking when user says "call me" or "book appointment"

### Advanced Integration
- **Groq AI API**: Powers the chatbot with fast, efficient language processing
- **Form Validation**: Real-time validation for phone numbers, emails, and dates
- **Multi-format Support**: Handles various phone number formats including Nepali numbers

## 🛠️ API Requirements

### 1. Pinecone API
**Why needed**: Stores your document content as vector embeddings for fast and accurate search
- **Usage**: Vector database for document storage and retrieval
- **Get it**: [https://www.pinecone.io/](https://www.pinecone.io/)

### 2. Groq API  
**Why needed**: Provides ultra-fast language processing for answering questions
- **Usage**: Powers the chatbot's intelligence and natural language understanding
- **Get it**: [https://console.groq.com/](https://console.groq.com/)

## 🚀 Quick Start

### Installation
```bash
!pip install -qU langchain-pinecone langchain-text-splitters langchain groq langchain-groq gradio pinecone-notebooks phonenumbers dateparser
