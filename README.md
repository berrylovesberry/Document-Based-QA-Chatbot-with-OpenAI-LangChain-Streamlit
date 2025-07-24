# 📄 PDF Q\&A Chatbot with OpenAI, LangChain & Streamlit

This project is an interactive chatbot that allows users to upload PDF documents and ask context-specific questions. Built with **Streamlit**, **LangChain**, and **OpenAI GPT-3.5**, the app performs document parsing, semantic search, and generates intelligent responses using **retrieval-augmented generation (RAG)**.

---

## 🚀 Features

* 📤 Upload any PDF document
* 🔍 Extract and chunk text using `PyPDF2` and LangChain
* 🧠 Generate semantic embeddings with OpenAI
* 📚 Store and search document chunks with FAISS
* 💬 Ask questions and receive accurate, context-aware answers using GPT-3.5 Turbo
* 🖥️ User-friendly interface built with Streamlit

---

## 🛠️ Tech Stack

* **Python 3.10+**
* **Streamlit** – UI and interactivity
* **PyPDF2** – PDF text extraction
* **LangChain** – Chaining components and RAG
* **FAISS** – Vector storage and similarity search
* **OpenAI GPT-3.5** – Generative model for answers
* **Google Cloud Platform (optional)** – For hosting/deployment

---

## 📦 Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/pdf-chatbot.git
   cd pdf-chatbot
   ```

2. **Create and activate a virtual environment**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Set your OpenAI API Key**
   Replace `OPENAI_API_KEY` in the code with your OpenAI key or set it as an environment variable.

---

## ▶️ Usage

Run the Streamlit app:

```bash
streamlit run app.py
```

1. Upload a PDF using the sidebar
2. Ask any question about its content
3. Get a response powered by GPT-3.5 and LangChain!

---

## 📁 Project Structure

```
├── app.py                  # Main Streamlit app
├── requirements.txt        # Dependencies
└── README.md               # Project overview
```

---

## 📚 Example Use Cases

* Analyzing legal documents
* Reviewing research papers
* Summarizing business reports
* Searching policy documents

---

## ⚠️ Disclaimer

This app uses OpenAI's GPT model and may generate incorrect or misleading answers. Always verify important information manually.
---
