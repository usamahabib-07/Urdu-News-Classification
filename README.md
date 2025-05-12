# Urdu-News-Classification

A Natural Language Processing (NLP) project for classifying Urdu news articles based on sentiment using machine learning techniques.

## 🧠 Project Overview

This project focuses on building an end-to-end Urdu text classification pipeline using machine learning algorithms and deep learning models. The goal was to accurately classify Urdu news articles by sentiment (positive/negative/neutral) through robust preprocessing and model tuning.

## 🛠️ Tools & Libraries Used

- **Python**
- **UrduHack** – Text preprocessing for Urdu (normalization, lemmatization, stopword removal)
- **Scikit-learn** – TF-IDF vectorization, Logistic Regression, SVM
- **Keras / TensorFlow** – Neural Network implementation
- **Matplotlib / Seaborn** – Performance visualization

## 📈 Key Results

- Achieved **94.7% classification accuracy**
- Improved model performance by **7%** after Urdu-specific preprocessing using UrduHack
- Tested models:
  - Logistic Regression
  - Support Vector Machines (SVM)
  - Multi-layer Neural Networks

## 🔍 Pipeline Highlights

1. **Data Cleaning**
   - Unicode normalization, punctuation removal, and diacritic stripping

2. **Text Preprocessing**
   - Tokenization and stopword removal using `UrduHack`
   - Lemmatization of Urdu terms

3. **Feature Extraction**
   - TF-IDF vectorization with n-grams

4. **Modeling**
   - Training and testing multiple classifiers
   - Hyperparameter tuning and validation

5. **Evaluation**
   - Accuracy, precision, recall, F1-score
   - Confusion matrix and classification reports
