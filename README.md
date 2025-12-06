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
```


## 5. Implementation

The implementation of the Hate Speech Detection System is carried out in Jupyter Notebook.  
The process includes preparing the dataset, transforming the text, training the model, and evaluating its performance.

### 5.1 Data Preprocessing
The following steps are applied to clean and prepare the text data:

- Converting all text to lowercase  
- Removing special characters, URLs, symbols, and numbers  
- Tokenization of sentences into words  
- Stop-word removal  
- Applying stemming or lemmatization to normalize words  

These steps help reduce noise in the dataset and improve model performance.

### 5.2 Feature Extraction
After preprocessing, the text is converted into numerical features using:

- **Bag-of-Words (BoW)**  
- **TF-IDF Vectorizer**

These methods transform text into a format that machine learning algorithms can understand.

### 5.3 Model Training
The preprocessed and vectorized data is used to train machine learning classifiers.  
Common models used include:

- **Naive Bayes**  
- **Support Vector Machine (SVM)**  

The dataset is split into training and testing sets to evaluate how well the model generalizes.

### 5.4 Model Evaluation
The performance of the model is measured using standard metrics:

- Accuracy  
- Precision  
- Recall  
- F1-Score  

These metrics help understand how correctly the model identifies hate speech, offensive language, and clean text.

### 5.5 Output
The system classifies each input text into one of the following categories:

#### **Hate Speech Detected**
Text that promotes hostility, violence, or discrimination toward a group or individual.

#### **Offensive Language Detected**
Text containing insulting or rude language but not explicitly hateful.

#### **No Hate / Clean Speech**
Neutral or respectful content without harmful expressions.

Example outputs include:

- *“I hate people like you” → Hate Speech Detected*  
- *“You are annoying” → Offensive Language Detected*  
- *“Everyone is welcome here” → No Hate / Clean Speech*  

---

## 6. Future Scope
- Support for multilingual and mixed-language datasets  
- Improved handling of sarcasm and context  
- Integration with deep learning models (RNN, Transformers)  
- Real-time deployment using web frameworks or APIs  

---

## 7. Conclusion
This project demonstrates a simple but effective approach to detecting hate speech using basic NLP and machine learning techniques.  
Through preprocessing, feature extraction, model training, and evaluation, the system can categorize text into hate speech, offensive language, or clean speech.  
The results show that machine learning can assist in moderating online content and improving digital safety.

---

## Authors
- **Dr. Vidya Lakshmi V**  
- **V Karthikeya Reddy**

