# EmbeddingClusteringVectorizationWorkshop

## Word Embeddings, Clustering, and Vectorization Workshop  
**Course:** PROG8245 – Fall 2025  

---

## Team Members

| Team Member | Student ID |
|------------|------------|
| ROHIT IYER | 8993045 |
| CEMIL CAGLAR YAPICI | 9081058 |

---

## Dataset Description

### Reuters Corpus (NLTK)

This workshop uses the **Reuters-21578 dataset**, a widely used benchmark corpus available via the NLTK library.

#### Key Statistics  
- **Total Documents:** 10,788  
- **Total Categories:** 90  
- **Document Types:** News articles covering economics, trade, commodities, politics  
- **Language:** English  
- **Source:** Reuters newswire, 1987  
- **Access:** Distributed with NLTK (public research use)

---

## 🔗 Dataset Source

**Source:** Reuters-21578  
- **NLTK Corpus Info:** https://www.nltk.org/book/ch02.html  
- **Original Dataset:** UCI Machine Learning Repository  
- **License:** Research license (via NLTK)  
- **Citation:**  
David D. Lewis (1997). Reuters-21578 Text Categorization Test Collection.  
http://www.daviddlewis.com/resources/testcollections/reuters21578/

---

## Workshop Contents

### Notebook: `EmbeddingClusteringVectorizationWorkshop_Fall2025.ipynb`

#### Part 1: Tutorial Demonstrations
- Bag-of-Words (BoW) and TF-IDF  
- K-Means & Hierarchical Clustering  
- Training Word2Vec on Reuters  
- Using GloVe Pre-trained Embeddings  
- Nearest neighbors & semantic similarity  

---

## Part 2: Workshop Analysis & Talking Points
- Preprocessing effects (tokenization, stopwords)  
- Dimensionality and sparsity  
- Cluster evaluation (silhouette, inertia)  
- Reuters-trained Word2Vec vs. GloVe semantics  
- Topic grouping and trends  

---

## Key Findings

### Word2Vec vs GloVe Comparison

| Aspect | Word2Vec (Reuters) | GloVe (6B Pre-trained) |
|--------|---------------------|--------------------------|
| Training Style | Predictive NN | Matrix Factorization |
| Context | Local Reuters window | Global co-occurrence |
| Strengths | Domain‑specific | Strong general semantics |
| Vocabulary | Smaller | 400K words |

---

## License

- **Code:** MIT License  
- **Reuters Corpus:** Research License (NLTK)  
- **GloVe:** Public Domain Dedication and License (PDDL)  
