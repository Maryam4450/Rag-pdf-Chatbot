# 📚 RAG PDF Chatbot

A smart chatbot that leverages **Retrieval-Augmented Generation (RAG)** to answer user queries based on the contents of a provided PDF. This tool combines the power of document retrieval with large language models to provide accurate and context-aware responses from custom documents. It also provide the summary of PDF.

## 🚀 Live Demo

🔗 [Use the RAG PDF Chatbot on Hugging Face Spaces](https://huggingface.co/spaces/Maryam42/pdf_chatbot)

---

## 🤖 What It Does

- Upload your PDF document
- Ask questions related to the uploaded PDF
- Get responses that are grounded in the actual content of your document
- Works well for lecture notes, legal docs, policies, research papers, etc.

---

## 🧠 How It Works

1. **PDF Parsing**: Extracts text content from the uploaded PDF.
2. **Chunking**: Splits the extracted text into manageable pieces.
3. **Vectorization**: Embeds chunks using a sentence embedding model.
4. **Retrieval**: Matches user queries with the most relevant text chunks.
5. **Generation**: Passes context + question to an LLM to generate a response.

---

## 🛠️ Tech Stack

- [Python](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [Hugging Face Transformers](https://huggingface.co/transformers/)
- [Hugging Face Spaces](https://huggingface.co/spaces) (for deployment)

---
