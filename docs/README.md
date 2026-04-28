# 🧠 NeuroLearn AI

NeuroLearn AI is an intelligent learning assistant that uses AI, NLP, and RAG to provide personalized educational support through a Flask-based web application.

---

## 👥 Team Roles

* Alya – System Architect / Lead
* Aneeb – Backend Developer
* Sajid – Frontend Developer
* Tehreem – AI/ML Engineer

---

## ⚙️ Tech Stack

* Flask (Backend APIs)
* NLP (Text Processing)
* SentenceTransformers (Embeddings)
* ChromaDB (Vector Database)
* RAG (Retrieval-Augmented Generation)

---

## 🧠 System Architecture Rule

* AI logic is handled inside `ai_engine/`
* Backend (Flask) only handles API requests and responses
* Frontend handles UI only
* ChromaDB is the **only active vector database used in Phase 2**

---

## 📌 Development Rules

* ❌ No FAISS usage in final system
* ❌ No duplicate AI pipelines
* ❌ Backend must not perform embedding or chunking
* ✔ AI engine handles RAG pipeline completely
* ✔ One unified data flow only

---

## 🔄 Data Flow

User Query → Flask Backend → AI Engine (RAG + ChromaDB) → Response → Frontend Display

---

If you want next step, say **“Step 2”** and I’ll guide you exactly what to do next.
