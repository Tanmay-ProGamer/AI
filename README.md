# 🚗 Cars24 RAG Chatbot

An AI-powered customer support chatbot for Cars24, built using 
Retrieval-Augmented Generation (RAG) with advanced Learning to Rank (LTR) reranking.

## 🔧 Tech Stack
- **LLM:** GPT-4.1-nano (OpenAI)
- **Framework:** LangChain
- **Vector DB:** ChromaDB
- **Embeddings:** HuggingFace all-MiniLM-L6-v2
- **Reranker:** CrossEncoder (LTR)
- **UI:** Gradio
- **Scraping:** BeautifulSoup

## 🚀 Features
- Live web scraping from cars24.com
- RAG pipeline with ChromaDB vector search
- LTR reranking using CrossEncoder (top 10 → best 3)
- Conversation memory across turns
- Gradio chat interface

## 📚 Course
Built as part of Ed Donner's LLM Engineering course - Week 5 RAG project.

## ▶️ How to Run
1. Clone the repo
2. Add your `OPENAI_API_KEY` to a `.env` file
3. Run `prac3.ipynb` in Jupyter