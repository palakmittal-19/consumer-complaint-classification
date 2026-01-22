# 📝 Consumer Complaint Classification

**A supervised machine learning system to classify consumer complaints into predefined categories.**  
Built using Python and natural language processing (NLP) techniques to preprocess text and train classification models.

---

## 🚀 Project Overview

This project tackles the problem of **automatically categorizing consumer complaints** using text data. Given a text describing a complaint, the model predicts the most likely complaint category, enabling efficient handling and routing of cases — especially useful in customer service automation and analytics.

---

## ✨ Key Features

- Clean and preprocess text data using NLP techniques  
- Convert text into numerical features using vectorization (TF-IDF)  
- Train multiple classification models using machine learning  
- Compare model performance using accuracy & other metrics  
- Predict class labels on new complaint text

---

## 🧠 Motivation

Consumer complaints often arrive in large volumes across channels like email, chat, social media, and web forms. Manual labeling and categorization is **slow and error-prone**. This project:

- Speeds up complaint handling  
- Helps understand trends in consumer issues  
- Enables automated routing to appropriate teams

---

## 📊 Dataset

The dataset contains consumer complaint text along with corresponding labels/categories.  
It was cleaned, processed, and split into training and testing sets for model evaluation.

---

## 🛠️ Tech Stack

| Category | Tools / Libraries |
|----------|-------------------|
| Language | Python |
| NLP | NLTK, Scikit-learn, Regex |
| Feature Engineering | TF-IDF Vectorizer |
| Classification | Logistic Regression, SVM, Random Forest |
| Evaluation | Confusion Matrix, Accuracy, Precision, Recall |

---

## 🧩 How It Works

### 1. Data Cleaning
- Convert text to lowercase  
- Remove punctuation and stop words  
- Tokenize sentences  
- Optional lemmatization/stemming  

### 2. Feature Extraction
Text is converted into numeric features using:
- **TF-IDF (Term Frequency – Inverse Document Frequency)**

### 3. Model Training
A classification model is trained against the vectorized text features. Models commonly used:
- Logistic Regression  
- Linear SVM  
- Random Forest

### 4. Evaluation
Performance is evaluated using metrics such as:
- Accuracy
- Precision
- Recall
- F1-score

---

## 📦 Installation & Setup

To run this project locally:

1. Clone the repository

```bash
git clone https://github.com/palakmittal-19/consumer-complaint-classification.git
cd consumer-complaint-classification
pip install -r requirements.txt
jupyter notebook Consumer_Complaint_Classification.ipynb

