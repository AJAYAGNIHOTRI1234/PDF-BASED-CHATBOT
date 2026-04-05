# 🚀 AI-Powered PDF Chatbot (RAG + Streamlit + Mistral)

> 📄 Turn your PDFs into an intelligent chatbot that understands and answers questions using AI.

---

## 🌟 Features

✨ Upload any PDF and ask questions in natural language
🤖 AI-powered responses using Mistral LLM
🔍 Semantic search with FAISS vector database
✂️ Dynamic text chunking based on document size
🎯 Token-aware response generation (optimized output length)
🔗 LangGraph-based pipeline for structured processing
⚡ Fast and interactive UI with Streamlit

---

## 🧠 How It Works (RAG Pipeline)

1. 📄 Upload a PDF file
2. ✂️ Extract and split text into dynamic chunks
3. 🔢 Convert chunks into embeddings (HuggingFace)
4. 🗂️ Store embeddings in FAISS vector database
5. ❓ User submits a query
6. 🔍 Retrieve top relevant chunks (k=6)
7. 🤖 Mistral LLM generates context-aware response
8. 🎯 Response is optimized based on token requirements

---

## 🏗️ Project Structure

```
pdf-chatbot/
│── app.py                # Main Streamlit application
│── requirements.txt     # Dependencies
│── .gitignore           # Ignored files
└── myenv/               # Virtual environment (ignored)
```

---

## 🛠️ Tech Stack

* **Frontend:** Streamlit
* **Backend:** Python
* **LLM:** Mistral AI
* **Embeddings:** HuggingFace
* **Vector DB:** FAISS
* **Frameworks:** LangChain, LangGraph
* **PDF Processing:** PyPDF2

---

## ⚙️ Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/pdf-chatbot.git
cd pdf-chatbot
```

### 2️⃣ Create virtual environment

```bash
python -m venv myenv
source myenv/bin/activate   # Linux/Mac
myenv\Scripts\activate      # Windows
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Setup API Key

⚠️ **Do NOT hardcode your API key**

Use environment variables:

```bash
export MISTRAL_API_KEY=your_api_key   # Linux/Mac
set MISTRAL_API_KEY=your_api_key      # Windows
```

Then update your code:

```python
import os
mistral_api_key = os.getenv("MISTRAL_API_KEY")
```

---

## ▶️ Run the App

```bash
streamlit run app.py
```

---

## 📸 Demo

Upload a PDF → Ask Questions → Get Context-Aware Answers Instantly 🚀

---

## 🔒 Security Note

* ❌ Never commit API keys to GitHub
* ✅ Use `.env` or environment variables
* ✅ Add `.env` to `.gitignore`

---

## 📈 Future Improvements

* 📄 Multi-document support
* 💬 Chat history & memory
* 🌐 Deployment (Streamlit Cloud / AWS / Render)
* 🎨 Enhanced UI/UX
* 🔊 Voice-based interaction

---

## 🤝 Contributing

Contributions are welcome! 🎉

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Ajay Agnihotri**

---

## ⭐ Support

If you like this project:

🌟 Star the repo
🍴 Fork it
📢 Share it
