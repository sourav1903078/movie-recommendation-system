# 🎬 Movie Recommendation System

A comparative study of **Content-Based Filtering**, **Collaborative Filtering** (user-based and item-based), and **Matrix Factorization (SVD)** on a synthetic movie dataset.

This project was completed as part of the **Real-Life Project: Recommendation System** assignment.

---

## 📖 Project Summary

Modern streaming platforms (Netflix, Amazon Prime, etc.) rely on recommendation systems to suggest relevant content to users. This project builds and compares three families of recommenders on a synthetic dataset of **75 movies**, **320 users**, and **~3,500 ratings**:

1. **Content-Based Filtering** — TF-IDF on movie tags/descriptions + cosine similarity
2. **Collaborative Filtering** — User-Based and Item-Based similarity
3. **Matrix Factorization** — Truncated SVD on the mean-centered user-item matrix

The models are evaluated on the same held-out test set using **RMSE**, and compared qualitatively on cold-start scenarios. Key findings, limitations, and a proposed hybrid recommender are discussed in the accompanying report.

---

## 📂 Repository Structure
