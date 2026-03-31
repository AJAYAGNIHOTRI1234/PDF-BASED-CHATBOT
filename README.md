# 🚀 PDF Chatbot with AI (Streamlit + LangChain + Mistral)

> 📄 Turn your PDFs into an intelligent chatbot that can answer questions instantly using AI.

---

## 🌟 Features

✨ Upload any PDF and ask questions  
🤖 AI-powered responses using Mistral LLM  
🔍 Semantic search with vector embeddings (FAISS)  
⚡ Fast and interactive UI with Streamlit  
📚 Context-aware answers from your documents  

---

## 🧠 How It Works

1. 📄 Upload a PDF file  
2. ✂️ Text is extracted and split into chunks  
3. 🔢 Chunks are converted into embeddings  
4. 🗂️ Stored in a FAISS vector database  
5. ❓ User asks a question  
6. 🔍 Relevant chunks are retrieved  
7. 🤖 Mistral AI generates the final answer  

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

- **Frontend:** Streamlit  
- **Backend:** Python  
- **LLM:** Mistral AI  
- **Embeddings:** HuggingFace  
- **Vector DB:** FAISS  
- **Frameworks:** LangChain, LangGraph  

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

Replace the API key in `app.py`:

```python
mistral_api_key = "YOUR_API_KEY"
```

⚠️ **Important:** Never expose your API key publicly. Use environment variables instead.

---

## ▶️ Run the App

```bash
streamlit run app.py
```

---

## 📸 Demo

Upload a PDF → Ask Questions → Get Instant Answers

---

## 🔒 Security Note

- Do NOT commit API keys to GitHub  
- Use `.env` or environment variables for sensitive data  

---

## 📈 Future Improvements

- ✅ Multiple PDF support  
- 🧠 Chat history memory  
- 🌐 Deployment (Streamlit Cloud / AWS)  
- 🎨 Better UI/UX  
- 🔊 Voice input support  

---

## 🤝 Contributing

Contributions are welcome! 🎉

1. Fork the repo  
2. Create a new branch  
3. Make your changes  
4. Submit a Pull Request  

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 💡 Author

**Ajay Agnihotri**

---

## ⭐ Support

If you like this project:

🌟 Star the repo  
🍴 Fork it  
📢 Share it  
