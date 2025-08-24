# 📚 Algorithms for Massive Data (DSE) – Project

This repository contains my **course project** for **Algorithms for Massive Data (DSE)**.  
The project focuses on analyzing and finding similarities between large-scale book reviews using **PySpark** and text similarity algorithms.

---

## 📌 Project Overview
The aim of this project is to apply **algorithms for massive data** to real-world text data (Amazon Book Reviews) and study different methods for similarity detection.

### Objectives:
1. Explore and preprocess large-scale text data.  
2. Apply **Shingling** and **Jaccard similarity** for text comparison.  
3. Investigate scalable methods such as **MinHash** and **Locality-Sensitive Hashing (LSH)**.  
4. Evaluate algorithm performance in terms of efficiency and accuracy on large data.

---

## 📂 Dataset
Dataset: [Amazon Book Reviews – Kaggle](https://www.kaggle.com/datasets/mohamedbakhet/amazon-books-reviews)  

- Large-scale dataset of book reviews and ratings.  
- The **reviewText** column is used for similarity analysis.  

---

## ⚙️ Methods & Algorithms
- **Preprocessing**
  - Tokenization & stopword removal  
  - Shingling (k-grams)  

- **Similarity Computation**
  - Jaccard Similarity  
  - MinHash for approximate similarity  
  - Locality-Sensitive Hashing (LSH) for scalable near-duplicate detection  
