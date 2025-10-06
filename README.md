# 📚 KnowledgeScout

KnowledgeScout is an intelligent document-based **Question Answering (Q&A) System**.  
It allows users to upload documents, automatically extracts and embeds text into vector space, and then answers user questions by retrieving the most relevant chunks using **FAISS** and **Sentence Transformers**.

---

## 🚀 Features
- 📂 Upload PDF or text documents
- 🔎 Automatically chunk and index documents
- 🤖 Ask natural language questions
- 🎯 Get relevant answers from uploaded documents
- 🌐 Simple frontend for interaction
- ⚡ Powered by **Django**, **FAISS**, and **Sentence Transformers**

---

## 🛠️ Tech Stack
- **Backend**: Django, Django REST Framework  
- **NLP/AI**: Sentence Transformers (`all-MiniLM-L6-v2`), FAISS  
- **Frontend**: HTML, CSS, JavaScript (Vanilla)  
- **Database**: SQLite (default, can be extended)  
- **Deployment**: Easily deployable on Render / Railway / Heroku (backend) and Netlify / Vercel (frontend)

---

## 📂 Project Structure
knowledgescout/
│── backend/ # Django backend (API)
│ ├── qa/ # Q&A app
│ ├── core/ # Project settings
│ └── manage.py
│
│── frontend/ # Simple frontend
│ └── index.html
│
│── requirements.txt # Dependencies
│── README.md
