# 📘 Automative Teaching Using RAG

This repository showcases our capstone project: a Retrieval-Augmented Generation (RAG)-based academic question-answering system that evaluates how different LLMs perform on course-specific queries. The project is implemented using FAISS, Sentence-Transformers, and Hugging Face models.

🔗 [Colab Notebook (RAG Matrix Evaluation)](https://colab.research.google.com/drive/1cllFgi0dszfPW1dU2tq8VZfhqFfSQgfC?pli=1)

---

## 📌 Features

- Embedding generation using `all-MiniLM-L6-v2`
- Semantic retrieval using FAISS
- Answer generation using:
  - `google/flan-t5-base`
  - `facebook/bart-large`
- Model comparison using:
  - BLEU
  - ROUGE (1, 2, L)
  - METEOR
  - F1 Score
  - Cosine Similarity
  - CIDEr

---

## 📂 Folder Structure

- `data/`: Sample cleaned dataset with course transcripts
- `src/`: Modular scripts (retrieval, generation, evaluation)
- `results/`: Output evaluation matrix (CSV)
- `RAG_Evaluation_Colab.ipynb`: Main notebook demonstrating model performance

---

## 🛠 Requirements

Install the required packages:

```bash
pip install -r requirements.txt

