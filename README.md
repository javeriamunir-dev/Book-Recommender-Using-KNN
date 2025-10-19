<!-- 🖼️ Banner -->
![Book Recommender Banner](assets/book_recommender_banner.png)

# 📚 Book Recommendation Engine using KNN

A Machine Learning project built with **Python** and **Scikit-Learn**, designed to recommend books similar to a given title using the **K-Nearest Neighbors (KNN)** algorithm.

Developed and trained entirely in **Google Colab**.

---

## 🧠 Overview

This project creates a **Book Recommendation System** based on user ratings from the **Book-Crossings Dataset**, which includes:

- 📊 1.1 million book ratings  
- 👤 90,000 users  
- 📘 270,000 books  

The algorithm uses **cosine similarity** to measure the closeness between books based on how users rated them.

---

## 🎯 Project Objective

To build a function `get_recommends(book_title)` that:
- Takes a book title as input  
- Returns a list of **5 similar books** along with their **distance scores**

---

## ⚙️ Technologies Used

| Tool / Library | Purpose |
|-----------------|----------|
| **Python 3** | Programming language |
| **Pandas, NumPy** | Data manipulation & analysis |
| **Scikit-learn (KNN)** | Machine learning model |
| **Google Colab** | Development environment |

---

## 🧩 Dataset Details

The **Book-Crossings dataset** is already included in the Colab notebook.

- **Ratings scale:** 1–10  
- **Filtering applied:**  
  - Removed users with `< 200 ratings`  
  - Removed books with `< 100 ratings`

---

## 🧠 Model Building Steps

1. **Data Preprocessing**
   - Cleaned the dataset
   - Removed infrequent users and books

2. **Matrix Creation**
   ```python
   matrix = ratings.pivot_table(index='Book-Title', columns='User-ID', values='Book-Rating').fillna(0)
   ---

## 👩‍💻 Author

**Javeria Munir**  
🔗 [GitHub Profile](https://github.com/javeriamunir-dev)

📧 *For collaboration or queries:* [javeriamunirbwn@email.com](mailto:javeriamunirbwn@email.com)

---
⭐ Don’t forget to give this repository a star if you found it helpful!

