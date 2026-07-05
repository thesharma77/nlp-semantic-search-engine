 NLP Semantic Search Engine

An NLP-powered semantic search engine that retrieves relevant Machine Learning research papers based on **meaning** instead of exact keyword matching. It uses **Sentence Transformers** to generate text embeddings and **FAISS** for fast vector similarity search.

---

##  Features

- Semantic search using sentence embeddings
- Natural language query support
- Fast vector similarity search with FAISS
- Relevant research paper recommendations
- Interactive web interface
- Real-time search results

---

##  Tech Stack

- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Sentence Transformers, Hugging Face Transformers, FAISS
- **Framework:** Streamlit
- **Tools:** Git, GitHub, Jupyter Notebook

---

##  Dataset

- **Dataset:** ML-ArXiv Papers
- **Samples Used:** ~15,000 research papers
- **Fields:** Title, Abstract

---

##  Workflow

```
Dataset
   ↓
Data Cleaning
   ↓
Text Preprocessing
   ↓
Sentence Embeddings
   ↓
FAISS Index
   ↓
Semantic Search
   ↓
Rank Results
   ↓
Web Interface
```

---

##  How It Works

1. Load and clean the dataset.
2. Generate embeddings using **all-MiniLM-L6-v2**.
3. Store embeddings in a **FAISS** index.
4. Convert user queries into embeddings.
5. Retrieve and rank the most semantically similar research papers.

---

##  Project Structure

```
nlp-semantic-search-engine/
│── CBSOT_Project.ipynb
│── README.md
│── datasets.md
```

---

##  Installation

```bash
git clone https://github.com/therohit77/nlp-semantic-search-engine.git

cd nlp-semantic-search-engine

pip install -r requirements.txt

streamlit run app.py
```

---

##  Future Improvements

- RAG integration
- LLM-powered answer generation
- Hybrid search
- Better ranking models
- Docker & Cloud deployment
- User authentication

---

##  Key Learnings

- Natural Language Processing (NLP)
- Sentence Embeddings
- Semantic Search
- Information Retrieval
- Vector Databases (FAISS)
- Transformer Models
- End-to-End NLP Application Development

---

##  Contact

**Rohit Sharma**

- GitHub: https://github.com/therohit77
- LinkedIn: https://linkedin.com/in/rohit-sharma-2aa438260/

---

⭐ If you found this project useful, consider giving it a **Star** on GitHub.
