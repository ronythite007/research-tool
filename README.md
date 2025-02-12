# 📰Research Tool

## 🔍 Overview
The **Research Tool** is an AI-powered research assistant that allows users to **upload multiple URLs, analyze content, and ask questions** to extract relevant insights. It uses **Large Language Models (LLMs), LangChain, FAISS, and Groq API** to provide **multi-source answer synthesis, credibility analysis, and topic-based summaries**.

## 🚀 Features
✅ **Multi-Source Answer Synthesis** – Aggregates and summarizes key points from multiple URLs.  
✅ **Interactive Q&A** – Users can ask questions based on uploaded content.  
✅ **Context-Aware Follow-Up Queries** – Enables refining queries for more precise answers.  
✅ **Credibility & Bias Detection** – Identifies trustworthiness of sources.  
✅ **Source Citation & Transparency** – Provides in-text citations and references.  
✅ **Visual Analysis** – Generates keyword clouds, trend graphs, and sentiment insights.  
✅ **Multi-Format Support** – Works with news articles, PDFs, and YouTube transcripts.  

## 🛠️ Tech Stack
- **LLM Model** (Groq API) – Powers question-answering and summarization.  
- **LangChain** – Enables chaining of multiple AI components for retrieval-based analysis.  
- **FAISS** – Fast and efficient similarity search for document embeddings.  
- **Python** – Backend implementation.

## 📌 Installation
```bash
# Clone the repository
git clone https://github.com/your-username/research-tool.git
cd research-tool

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # For MacOS/Linux
venv\Scripts\activate    # For Windows

# Install dependencies
pip install -r requirements.txt
```

## ⚡ Usage
```python
steamlit run main.py  # Start the application
```

1. **Upload URLs** – Enter multiple article links.
2. **Ask Questions** – Query about any topic present in the articles.
3. **Get Insights** – Receive AI-generated answers, summaries.

## 🏗️ Future Enhancements
- **Real-Time News Scraping** – Fetch latest articles automatically.
- **Bias Analysis Dashboard** – Detect and visualize political bias in news.
- **Multi-Language Support** – Translate and analyze news in different languages.
- **Export Reports** – Generate AI-powered research summaries in PDF format.

## 🤝 Contribution
Feel free to contribute! Fork the repo, create a new branch, and submit a pull request. 

---
### 🌟 Star the Repo if You Like It! ⭐
