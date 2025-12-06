# 🛡️ Hate Speech Detection Using Machine Learning
A robust Machine Learning and Natural Language Processing (NLP) system designed to automatically classify text into **Hate Speech**, **Offensive Language**, and **Non-Hate** categories. The project focuses on improving online safety through intelligent content moderation.

---

## 📘 Overview
This project implements a complete ML pipeline—from **data preprocessing** to **model deployment**—using classical ML models (SVM, Naive Bayes) as well as advanced models (RNNs & BERT).  
The system is built and tested in **Jupyter Notebook** and can be deployed using **Flask/FastAPI**.

---

## 🚀 Features
- 🔹 Comprehensive NLP preprocessing (tokenization, stopwords, stemming, lemmatization)  
- 🔹 Models supported: SVM, Naive Bayes, Logistic Regression, RNN, BERT  
- 🔹 TF-IDF, Bag-of-Words & BERT embeddings  
- 🔹 Handles imbalanced datasets efficiently  
- 🔹 Multilingual and code-mixed text support  
- 🔹 High detection accuracy with contextual understanding  
- 🔹 Easy deployment as a REST API  

---

## 🧠 System Workflow
```text
Data Collection
        ↓
Data Preprocessing
        ↓
Feature Extraction (TF-IDF / BoW / BERT)
        ↓
Model Training (SVM / NB / RNN / BERT)
        ↓
Model Evaluation (Accuracy, Precision, Recall, F1)
        ↓
Deployment (Flask / FastAPI)
