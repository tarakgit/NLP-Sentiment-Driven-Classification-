# 🛍️ Amazon Sentiment Analysis

This project performs sentiment classification on Amazon product reviews using multiple machine learning models. The goal is to predict the sentiment category (e.g., Positive, Negative, Neutral) of a review based on its textual content and metadata.

---

## 📌 Project Overview

- **Objective**: Classify Amazon product reviews into sentiment categories using supervised learning techniques.
- **Techniques Used**: 
  - Text preprocessing & feature extraction (TF-IDF)
  - Model training using:
    - Naive Bayes
    - Random Forest
    - Support Vector Machine (SVM)

---

## ⚙️ Tools & Technologies

- Python (3.x)
- Scikit-learn
- Pandas
- NumPy
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 🧪 Key Features

- Excludes non-English reviews and unnecessary fields like reviewer name and URLs
- TF-IDF feature engineering on text data
- Use of categorical fields as additional model features
- Trains and compares performance of multiple classifiers
- Avoids data leakage by not using original `review_rating` directly

---

## 📊 Models Implemented

- **Naive Bayes** – Simple, fast, and effective baseline classifier
- **Random Forest** – Ensemble-based method to improve accuracy
- **Support Vector Machine (SVM)** – High performance for small-to-medium datasets

---

## 🧼 Data Preprocessing

- Removed non-English reviews
- Dropped unnecessary fields: `URL`, `Reviewer Name`, `Review Date`, etc.
- Converted categorical labels into numerical features
- Transformed text reviews into TF-IDF vectors

