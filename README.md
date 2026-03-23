# Predictive-Analytis-Lab-Exam-2
# 🧠 Word Embeddings & Similarity Analysis

## 📌 Overview

This project explores fundamental concepts of **Word Embeddings**, particularly **Word2Vec**, and similarity measures such as **cosine similarity**. It includes conceptual explanations and quiz-based insights to understand how machines interpret word relationships.

---

## 🎯 Objectives

* Understand how Word2Vec learns word representations
* Analyze cosine similarity and its behavior
* Explore limitations like ambiguity and dataset bias
* Study semantic relationships between words

---

## 🧩 Key Concepts

### 🔹 Word2Vec

Word2Vec is a neural network-based model that learns word embeddings by:

* Predicting a word from its context (**CBOW**)
* Predicting context words from a target word (**Skip-gram**)

---

### 🔹 Cosine Similarity

Cosine similarity measures the **angle between two vectors**:

* Value close to **1 → highly similar**
* Value close to **0 → not similar**

---

### 🔹 Context Matters

Words like *“cat”* and *“dog”* have similar vectors because they:

* Appear in similar contexts
* Share semantic meaning (animals, pets)

---

## ⚠️ Limitations

### ❌ Ambiguity Problem

* Words like **“bank”** have multiple meanings
* Word2Vec assigns **one vector per word**, causing mixed meanings

### ❌ Dataset Bias

* If words frequently appear together, similarity may reflect **bias** instead of true meaning

### ❌ Sparse Data Issue

* Unrelated words may appear similar due to common words

---

## 📊 Example Observations

* cosine(cat, dog) → High (similar context)
* cosine(cat, car) → Low (different context)
* cosine(bank, money) & cosine(bank, river) → Both moderately high

---

## 🚀 Key Takeaways

* Word meaning is learned from **context, not labels**
* Cosine similarity focuses on **direction, not magnitude**
* Static embeddings struggle with **multiple meanings**
* Context-aware models (like BERT) solve many limitations

---

## 📁 Files Included

* `notebook.ipynb` → Code and experiments
* `README.md` → Project documentation

---

## 🛠️ Tools & Libraries

* Python
* NumPy
* Matplotlib
* Scikit-learn

---

## 📚 Conclusion

This project demonstrates how machines understand language using vector representations and highlights both the strengths and limitations of Word2Vec and cosine similarity.

---

## 👤 Author

Your Name

---
