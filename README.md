# 🔍 Hybrid Search RAG with Vector Database (Pinecone) & LangChain

This project demonstrates how to implement a **Hybrid Retrieval-Augmented Generation (RAG)** system using both **dense** and **sparse** retrieval techniques with **Pinecone** as the vector database and **LangChain** for LLM orchestration.

---

## 💡 What is Hybrid Search RAG?

**Hybrid Search** combines:
- 🔎 **Dense retrieval**: Semantic search using vector embeddings (via OpenAI, HuggingFace, etc.)
- 📄 **Sparse retrieval**: Traditional keyword-based methods like BM25 or TF-IDF

Using both together improves result **accuracy**, **relevance**, and **robustness** in RAG pipelines.

---

## 🗂️ Project Structure

```
Hybrid-Search-RAG/
├── Hybrid_Search_RAG.ipynb     # End-to-end hybrid search pipeline with LangChain + Pinecone
├── requirements.txt            # Required packages
└── README.md                   # You're here!
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Aparna-k246/Hybrid-Search-RAG.git
cd Hybrid-Search-RAG
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Configure Environment

Make sure to set your Pinecone and OpenAI API keys in your environment:

```bash
export PINECONE_API_KEY=your_pinecone_key
export OPENAI_API_KEY=your_openai_key
```

Or use `.env` file with `python-dotenv`.

---

## 🚀 Run the Pipeline

Launch and step through the notebook:

```bash
jupyter notebook Hybrid_Search_RAG.ipynb
```

---

## 🔗 Key Components

- 📌 **LangChain** for RAG orchestration and chain building
- 📌 **Pinecone** for scalable vector search
- 📌 **BM25/TF-IDF** via `scikit-learn` or `Elasticsearch` for sparse search
- 🔀 **Fusion strategy** to combine both retrieval results
- 🧠 **LLM (OpenAI/Gemini)** for final answer generation

---

## 📈 What You'll Learn

✅ How to build a hybrid retriever  
✅ How to connect Pinecone with LangChain  
✅ How to combine sparse and dense results using re-ranking or weighted fusion  
✅ How to integrate the hybrid retriever into a RAG chain

---

## 🧠 Skills Highlight for Resume/LinkedIn

- ✅ Hybrid RAG pipeline using Pinecone & LangChain
- ✅ Dense + Sparse retrieval fusion implementation
- ✅ Retrieval tuning and evaluation
- ✅ Vector DB + LLM orchestration with real-world use case

---

## 🛠️ Tech Stack

- `LangChain`
- `Pinecone`
- `OpenAI / Gemini`
- `TF-IDF / BM25`
- `Python`, `Jupyter Notebook`

---

## 📄 License

MIT License

---

## 👤 Author

**Aparna K**  
🔗 [LinkedIn](https://www.linkedin.com/in/aparna-k-628005167/)  
📁 [GitHub Profile](https://github.com/Aparna-k246)

---

> ⭐ Don’t forget to star the repo if you found it useful!
