# Rag_ChatBot
RAG-based PDF Chatbot built using Flask and Streamlit with document upload, text retrieval, similarity search, and source reference support.

## Stock Price Data Excel Project
<img width="1540" height="614" alt="Screenshot 2025-10-13 150707" src="https://github.com/user-attachments/assets/abfa5df7-f3d9-4057-b1ee-a99bcbf7b32b" />

# 🤖 RAG PDF Chatbot

A simple RAG (Retrieval-Augmented Generation) based PDF Chatbot built using Flask and Streamlit.

This chatbot allows users to:
- Upload PDF documents
- Process document content
- Ask questions from uploaded PDFs
- Retrieve relevant information using similarity search
- Display source references

---

# 🚀 Features

✅ PDF Upload  
✅ Text Extraction from PDF  
✅ Document Chunking  
✅ Similarity Search  
✅ RAG-based Retrieval  
✅ Source References  
✅ Flask Backend API  
✅ Streamlit Frontend  
✅ Fast and Lightweight  

---

# 🛠️ Tech Stack

## Frontend
- Streamlit

## Backend
- Flask
- Flask-CORS

## Document Processing
- PyPDF

## Retrieval System
- TF-IDF Vectorization
- Cosine Similarity

## Storage
- Pickle

## Machine Learning
- Scikit-learn

---

# 📂 Project Structure

```bash
rag-chatbot-project/
│
├── backend/
│   ├── app.py
│   ├── rag_pipeline.py
│   └── requirements.txt
│
├── frontend/
│   └── streamlit_app.py
│
├── uploads/
│
├── vector_db/
│
└── README.md
```

---

# ⚙️ Installation

## 1. Clone Repository

```bash
git clone YOUR_GITHUB_LINK
```

---

## 2. Open Project Folder

```bash
cd rag-chatbot-project
```

---

## 3. Create Virtual Environment

### Windows

```bash
python -m venv venv
```

Activate environment:

```bash
venv\Scripts\activate
```

---

# 📦 Install Dependencies

Go to backend folder:

```bash
cd backend
```

Install requirements:

```bash
pip install -r requirements.txt
```

---

# ▶️ Run Backend

Inside backend folder:

```bash
python app.py
```

Expected output:

```bash
Running on http://127.0.0.1:5000
```

---

# ▶️ Run Frontend

Open another terminal.

Go to frontend folder:

```bash
cd frontend
```

Run Streamlit app:

```bash
streamlit run streamlit_app.py
```

---

# 💬 How to Use

1. Upload a PDF document
2. Wait for processing
3. Ask questions related to the document
4. Chatbot retrieves relevant chunks
5. Source references are displayed

---

# 🔍 How RAG Works

1. PDF text extraction
2. Text chunking
3. Vectorization using TF-IDF
4. Similarity search using cosine similarity
5. Retrieval of relevant chunks
6. Response generation

---

# 📌 API Endpoints

## Upload PDF

```http
POST /upload
```

---

## Ask Question

```http
POST /chat
```

Request body:

```json
{
  "query": "What is this document about?"
}
```

---

# 📷 Screenshots

Add project screenshots here.

Example:
- PDF Upload
- Chat Interface
- Source References

---

# 📚 Libraries Used

- Flask
- Streamlit
- PyPDF
- NumPy
- Requests
- Scikit-learn

---

# 🎯 Assignment Requirements Covered

✅ Backend (Flask API)  
✅ Frontend (Streamlit)  
✅ Document Upload & Processing  
✅ Vector Database / Retrieval  
✅ Chat Functionality  
✅ Source References  

---

# 👨‍💻 Author

Your Name

---

# 📄 License

This project is for educational and assignment purposes.
