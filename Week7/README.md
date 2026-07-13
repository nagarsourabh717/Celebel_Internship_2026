# 📄 Document Question Answering using RAG

## 📌 Overview

This project implements a Retrieval-Augmented Generation (RAG) system that answers questions from custom PDF documents.

The system extracts text from PDFs, splits it into chunks, generates embeddings, stores them in a FAISS vector database, retrieves the most relevant chunks, and finally uses Google Gemini to generate context-aware answers.

---

## 🚀 Features

- Upload any PDF
- Automatic text extraction
- Recursive text chunking
- Semantic embeddings using Sentence Transformers
- Vector similarity search with FAISS
- Google Gemini answer generation
- Streamlit web interface

---

## 🛠️ Technologies

- Python
- Streamlit
- FAISS
- Sentence Transformers
- Google Gemini API
- LangChain Text Splitter
- PyMuPDF

---

## 📂 Folder Structure

```
Document-QA-RAG/
│
├── app.py
├── requirements.txt
├── README.md
├── .env.example
│
├── data/
├── utils/
├── vector_db/
└── test files
```

---

## ▶️ Installation

```bash
pip install -r requirements.txt
```

---

## ▶️ Run

```bash
streamlit run app.py
```

---

## 📊 Architecture

```
PDF
 │
 ▼
Extract Text
 │
 ▼
Chunking
 │
 ▼
Embeddings
 │
 ▼
FAISS
 │
 ▼
Retrieve Chunks
 │
 ▼
Gemini
 │
 ▼
Answer
```

---

## 📚 Future Improvements

- Multiple PDF support
- Conversation memory
- OCR support
- Hybrid Search
- Better UI

---

## 👨‍💻 Author

sourabh
