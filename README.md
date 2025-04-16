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
3. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/pdf-qa-chatbot.git
   cd pdf-qa-chatbot
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
5. Run the app:
   ```bash
   streamlit run app.py

📌 Notes
- Ensure the chat-with-pdf/pdfs/ directory exists or is created by the script.
- The chatbot can handle complex questions and provide reasoning-based answers from the PDF context.



