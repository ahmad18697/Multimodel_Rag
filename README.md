# 🚀 Google’s Gemini Bot — Multi-Modal AI Assistant ✅

> ✅ A powerful AI assistant built using **Google’s Gemini models**, featuring a  
> **Django REST backend** and an **interactive Streamlit frontend**.

Gemini Bot enables:
✅ Natural conversations  
✅ Image understanding  
✅ PDF-based question answering using **RAG (Retrieval-Augmented Generation)**  

---

## ✨ Key Highlights ✅

✅ Powered by Google Gemini LLMs  
✅ Multi-modal support (Text + Image + PDF)  
✅ Clean backend–frontend architecture  
✅ Real-world AI deployment example  
✅ Scalable and extensible design  

---

## 🧠 Features Overview ✅

### 🤖 Conversational Chatbot
✅ Chat naturally with Gemini  
✅ Custom system prompts to define behavior  
✅ Suitable for assistants, tutors, and domain bots  

---

### 🖼️ Image Analysis Bot
✅ Upload images (JPG, PNG, WEBP)  
✅ Ask questions about image content  
✅ Uses `gemini-2.5-flash` vision model  

---

### 📄 Chat with PDF (RAG)
✅ Upload PDF documents  
✅ Automatic text extraction  
✅ Embeddings via `text-embedding-004`  
✅ Semantic search using **FAISS**  
✅ Accurate, context-aware answers  

---

## 🏗️ Project Architecture ✅

```text
Gemini-Bot/
│
├── Gemini-Bot-backend/     # Django REST API
│   ├── Text Chat APIs
│   ├── Image Analysis APIs
│   ├── PDF RAG Pipeline
│
├── Gemini-Bot-main/        # Streamlit Frontend
│   ├── Chat Interface
│   ├── Image Upload UI
│   ├── PDF Chat Interface
⚙️ Setup Instructions ✅
🔹 Prerequisites

✅ Python 3.10+ (Tested with Python 3.13)
✅ Google Gemini API Key
👉 https://aistudio.google.com/
🔧 Backend Setup ✅
cd Gemini-Bot-backend

1️⃣ Create & Activate Virtual Environment
python3 -m venv .venv
source .venv/bin/activate
# Windows: .venv\Scripts\activate

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Configure Environment Variables

Create a .env file in backend directory:

GEMINI_API_KEY=your_actual_api_key_here


(Optional – defaults already set)

GEMINI_TEXT_MODEL=models/gemini-2.5-flash
GEMINI_VISION_MODEL=models/gemini-2.5-flash

4️⃣ Run Backend Server
python manage.py migrate
python manage.py runserver 8001


✅ Backend runs at:
http://localhost:8001

🎨 Frontend Setup ✅
cd Gemini-Bot-main

1️⃣ Create & Activate Virtual Environment
python3 -m venv .venv
source .venv/bin/activate
# Windows: .venv\Scripts\activate

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run Streamlit App
streamlit run app.py


✅ Frontend runs at:
http://localhost:8501

🧪 How to Use the App ✅

✅ Chatbot Mode

Start general conversation

Set system prompt (e.g., You are a coding mentor)

✅ Image Bot

Upload an image

Ask questions about objects or text

✅ Chat with PDF

Upload PDF

Ask document-specific questions

🛠️ Troubleshooting ✅

❗ Quota / Rate Limit Exceeded

Happens mainly during PDF embeddings

Wait a short time and retry

❗ Model Not Found Error

Ensure these models are enabled:

gemini-2.5-flash

text-embedding-004

🧰 Tech Stack ✅

✅ Python
✅ Django & Django REST Framework
✅ Streamlit
✅ Google Gemini API
✅ LangChain
✅ FAISS (Vector Store)
✅ PDFPlumber

🌟 Future Enhancements ✅

☑️ Authentication & user history
☑️ Multi-PDF chat support
☑️ Streaming responses
☑️ UI enhancements
☑️ Cloud deployment (AWS / GCP)

🙌 Final Note ✅

This project demonstrates production-ready AI engineering by combining:
✅ Large Language Models
✅ RAG pipelines
✅ REST APIs
✅ Modern UI frameworks

Perfect for learning, interview showcases, and real-world AI applications 🚀
