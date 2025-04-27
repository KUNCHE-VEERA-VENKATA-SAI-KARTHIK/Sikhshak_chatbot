# Sikhshak_chatbot

# 📚 Chat with Multiple PDFs using Google Gemini 🚀

This project demonstrates an end-to-end application to **chat with multiple PDF documents** using **Google Gemini** and **LangChain**.  
It allows users to upload multiple research papers or PDFs, and ask questions about their content with intelligent, context-aware responses.

---

## 📖 Introduction

This application leverages:
- **Google Gemini Pro** for advanced document understanding.
- **LangChain** for managing conversational memory and interactions.
- **Vector Embeddings** (using a Facebook-developed technique) to handle document queries efficiently.

Users can upload multiple PDF files, and the system converts them into embeddings for real-time querying.

---

## 🛠️ Tech Stack

- **Python 3.10**
- **Streamlit** (for building the web interface)
- **Google Generative AI**
- **LangChain**
- **PyPDF2 / PDF Readers**
- **Vector Databases (local setup or cloud storage)**

---

## 🚀 Features

- Upload and interact with **multiple PDFs** simultaneously.
- **Vectorize** PDF content for fast and intelligent querying.
- Ask **detailed questions** based on uploaded documents.
- Handle **large PDFs** (up to 200MB per file).
- Store and **reuse** vector embeddings locally.
- **Conversational chain** setup for context-aware answers.

---

## 📦 Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/pdf-chat-gemini.git
cd pdf-chat-gemini
```

2. Create a new Python environment:

```bash
conda create -n Venv python=3.10
conda activate Venv
```

3. Install the required libraries:

```bash
pip install -r requirements.txt
```

4. Set your **Google API Key** as an environment variable:

```bash
export GOOGLE_API_KEY='your-api-key-here'
```

---

## 🧠 How It Works

- **PDF Upload** ➔ Extracts text and chunks it.
- **Vector Embedding** ➔ Converts text chunks to embeddings using Google Gemini.
- **Vector Storage** ➔ Saves embeddings for future queries.
- **Conversational Retrieval** ➔ Retrieves accurate answers based on user queries.
- **Streamlit Interface** ➔ Provides a smooth, interactive frontend.

---

## 🖥️ How to Run

```bash
streamlit run app.py
```

Then, open your browser at `http://localhost:8501/` and start uploading and chatting with your PDFs!

---

## 📸 Demonstration

- Upload research papers like "Attention is All You Need" and "YOLO".
- Ask questions such as: *"Explain the scaled dot-product attention?"* or *"Describe YOLO's architecture?"*.
- Receive detailed, document-based answers.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

- Thanks to **Krishn** for the project idea and walkthrough.
- Powered by **Google Gemini** and **LangChain** technologies.

---
