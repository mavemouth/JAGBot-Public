# 🇮🇳 JAGBot (Public Version)

**JAGBot** is an AI-powered legal assistant designed for the **Indian Army**, capable of answering questions related to the **Army Act** and **Army Rules**. It uses advanced language models to process user queries and return relevant sections from legal documents, summaries, and structured reports.

This notebook version is designed for **local usage**, with a minimal user interface and ease of deployment using Gradio.

---

## 🚀 Features

- 📄 **Legal QA:** Ask questions related to the Indian Army Act & Rules and get relevant section-wise answers.
- 🧠 **Conversational Memory:** Maintains dialogue context to support follow-up queries.
- 🔍 **Section Lookup:** Enter a section number (e.g., `Section 45`) to retrieve its full text.
- 🖥️ **Web Interface:** User-friendly UI built using **Gradio**, accessible via browser.
- 📦 **Deployable:** Can be deployed locally or on platforms like **Hugging Face Spaces**.

---

## 🧰 Requirements

Install the following Python packages before running the notebook:

```bash
!pip install langchain langchain-community langchain-groq sentence-transformers chromadb PyPDF2 gradio pypdf
 
