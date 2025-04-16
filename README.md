# 📄 PDF Q&A Chatbot with LangChain and Ollama

A simple RAG (Retrieval-Augmented Generation) system using Deepseek, LangChain, and Streamlit to chat with PDFs and answer complex questions about your local documents.

## 🚀 Features
- Upload any PDF document.
- Ask questions based on the content.
- Get concise, reasoning-based answers.
- Powered by LangChain, Ollama, and DeepSeek-R1.

## 🧠 Model
- **DeepSeek-R1** (14B) via Ollama.
- Embeddings generated using `OllamaEmbeddings`.

## 🛠️ Tech Stack
- Python
- [Streamlit](https://streamlit.io/)
- [LangChain](https://www.langchain.com/)
- [Ollama](https://ollama.com/)
- PDF parsing with `pdfplumber`


## ⚙️ Setup Instructions
1. **Install Ollama** (https://ollama.com/)
2. Pull the model:
   ```bash
   ollama pull deepseek-r1:14b

✨ Demo
- Coming soon

