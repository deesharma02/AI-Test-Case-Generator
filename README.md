# 🤖 AI Test Case Generator (RAG-Based)

## 🚀 Overview

This project is an **AI-powered Test Case Generator** that uses **Retrieval-Augmented Generation (RAG)** to generate structured and meaningful test cases from requirement documents.

It combines **vector search + LLM reasoning** to ensure accurate and context-aware outputs while reducing unnecessary LLM calls.

---

## 🧠 How It Works

1. Upload a requirement document (.docx)
2. Text is split into chunks
3. Chunks are converted into embeddings
4. Stored in a vector database (ChromaDB)
5. Relevant chunks are retrieved using a retriever
6. LLM generates structured test cases using retrieved context

---

## 🛠️ Tech Stack

* **Python**
* **Streamlit** (UI)
* **LangChain**
* **ChromaDB** (Vector Store)
* **Gemini Embeddings Models / Gemini LLM Models**
* **python-docx**

---

## 📂 Project Structure

```
project/
│── main.py
│── requirements.txt
│── README.md
│── .gitignore
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone <repo-url>
cd your-project
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Set up environment variables 🔐

This project requires API keys to run.

Create a `.env` file in the root directory and add the following:

```env
GOOGLE_API_KEY=your_google_api_key

### 3️⃣ Run the app

```bash
streamlit run app.py
```



---

## 📌 Features

✅ Upload requirement documents
✅ Generate structured test cases
✅ Uses RAG for better accuracy
✅ Reduces unnecessary LLM calls
✅ Metadata filtering support
✅ Clean UI with Streamlit

---

## 🧪 Example Output Format

* Test Case ID
* Test Scenario
* Preconditions
* Steps
* Expected Result

---

## 🚀 Future Enhancements

* 📥 Download test cases (Excel / Word)
* 💬 Convert into chatbot interface
* 🔍 Multi-query retriever optimization
* 📊 Table view (DataFrame display)
* 🧠 Smarter query generation using LLM
* 📁 Multi-document support

---

## ⚡ Improvements Implemented

* Optimized retriever to reduce LLM calls
* Used chunking strategy for better context
* Added metadata filtering for precision

---

## 🤝 Contribution

Feel free to fork this repo and improve it further!

---

## 📄 License

This project is for learning and demonstration purposes.

---

## 👨‍💻 Author

Deepak Sharma
