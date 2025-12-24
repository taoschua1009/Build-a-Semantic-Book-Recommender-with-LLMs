# 📚 Build a Semantic Book Recommender with LLMs

This project demonstrates how to build an end-to-end **semantic book recommendation system** using **Large Language Models (LLMs)**.  
The system enables users to search and discover books based on **meaning**, **emotion**, and **category**, rather than simple keyword matching.

---

## 🚀 Project Overview

The project consists of several stages, each implemented in a separate notebook or script:

### 1. Text Data Cleaning
**Notebook:** `data-exploration.ipynb`

- Clean and preprocess raw book description data
- Normalize text for downstream NLP tasks
- Prepare structured inputs for vector search and classification

---

### 2. Semantic (Vector) Search
**Notebook:** `vector-search.ipynb`

- Build a vector database from book descriptions
- Use embeddings to represent book content semantically
- Perform similarity search to retrieve books relevant to a natural language query  
  > Example query: *"a book about a person seeking revenge"*

---

### 3. Zero-Shot Text Classification
**Notebook:** `text-classification.ipynb`

- Apply zero-shot classification using LLMs
- Classify books into **fiction** or **non-fiction**
- Create an additional facet that users can filter recommendations by

---

### 4. Sentiment & Emotion Analysis
**Notebook:** `sentiment-analysis.ipynb`

- Perform sentiment and emotion extraction using LLMs
- Extract emotional signals such as:
  - Joy
  - Sadness
  - Fear / suspense
  - Surprise
  - Anger
- Enable emotion-based sorting of book recommendations

---

### 5. Web Application with Gradio
**Script:** `gradio-dashboard.py`

- Build an interactive web interface using **Gradio**
- Allow users to:
  - Enter natural language queries
  - Filter books by category
  - Sort recommendations by emotional tone
- Display book covers and concise descriptions

---

## 🧠 Technologies Used

- **Python**
- **LangChain**
- **OpenAI Embeddings**
- **Chroma Vector Database**
- **LLMs for zero-shot classification and sentiment analysis**
- **Gradio** for the web interface
- **Pandas / NumPy** for data processing

---

