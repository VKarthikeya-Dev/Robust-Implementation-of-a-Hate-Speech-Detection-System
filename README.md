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


---

## 5. Implementation Details

### ✔ Data Preprocessing
- Tokenization  
- Stop-word removal  
- Stemming / Lemmatization  
- Cleaning special characters  
- Handling imbalanced datasets (if required)

### ✔ Feature Extraction
- TF-IDF Vectorizer  
- Bag-of-Words  

### ✔ Model Training
Models commonly used in this project:
- Naive Bayes  
- Support Vector Machine (SVM)

### ✔ Model Evaluation
Metrics used:
- Accuracy  
- Precision  
- Recall  
- F1-Score  

---

## 6. Output

### Hate Speech Detected  
The input text is classified as harmful or abusive and targets a specific group or individual.

### Offensive Language Detected  
The text contains rude or insulting language but does not qualify as hate speech.

### No Hate / Clean Speech  
Neutral or respectful text with no harmful intent.

---

## 7. Future Scope
- Better multilingual and code-mixed text support  
- Improved contextual understanding  
- Integration with deep learning models  
- Deployment as a real-time moderation tool  

---

## 8. Conclusion

This project demonstrates a simple and practical approach for detecting hate speech using basic ML and NLP methods.  
By preprocessing text, extracting features, training models, and evaluating performance, the system can classify text into hate, offensive, and clean categories based on the dataset used.

---

## Authors
- **Dr. Vidya Lakshmi V**  
- **V Karthikeya Reddy**


