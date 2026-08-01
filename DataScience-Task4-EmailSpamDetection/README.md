# Email Spam Detection using Machine Learning

## Project Overview

This project was completed as part of the **Oasis Infobyte Data Science Internship**.

The objective of this project is to develop a Natural Language Processing (NLP) based machine learning model capable of automatically classifying emails as **Spam** or **Ham (Legitimate)**.

Email spam detection is one of the most common real-world applications of machine learning and NLP. By applying text preprocessing techniques, feature extraction using TF-IDF, and multiple classification algorithms, this project demonstrates how machine learning can effectively identify unwanted emails.

The notebook covers the complete NLP pipeline, including data preprocessing, feature extraction, model training, evaluation, comparison of classifiers, and prediction of unseen email messages.

---

# Objective

The primary objectives of this project are:

- Build an NLP-based spam email classifier.
- Clean and preprocess raw email text.
- Convert text into numerical features using TF-IDF Vectorization.
- Train multiple machine learning classification models.
- Compare model performance using standard evaluation metrics.
- Predict whether a new email is Spam or Ham.

---

# Dataset

The project uses the **Spam Email Dataset**.

### Dataset Information

The dataset contains two primary columns:

- **Label**
  - Spam
  - Ham (Legitimate Email)

- **Email Message**
  - Raw text of the email

The dataset was used to train and evaluate machine learning models for binary text classification.

---

# Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK

---

# Data Preprocessing

Before training the machine learning models, the email text was carefully cleaned and prepared.

The preprocessing steps included:

- Dataset loading
- Dataset inspection
- Missing value analysis
- Duplicate record checking
- Lowercase conversion
- Punctuation removal
- Stopword removal
- Text cleaning
- Label encoding

These preprocessing techniques improve the quality of text data and enhance model performance.

---

# Text Feature Extraction

Since machine learning algorithms cannot work directly with text, feature extraction was performed using the **TF-IDF (Term Frequency–Inverse Document Frequency) Vectorizer**.

TF-IDF converts textual email messages into numerical feature vectors by measuring the importance of each word within the dataset.

This representation enables machine learning models to learn meaningful patterns from email content.

---

# Machine Learning Models

Two supervised machine learning classifiers were trained and evaluated.

## 1. Multinomial Naive Bayes

A probabilistic classifier widely used for text classification problems due to its efficiency and strong performance on document data.

---

## 2. Logistic Regression

A linear classification algorithm used as an alternative model to compare performance against Naive Bayes.

---

# Model Evaluation

The trained models were evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

These evaluation metrics provide a comprehensive assessment of each classifier's performance.

---

# WordCloud Visualization

WordCloud visualizations were generated to explore the most frequently occurring words in:

- Spam Emails
- Ham (Legitimate) Emails

These visualizations provide intuitive insights into the vocabulary commonly associated with each email category.

---

# Project Workflow

1. Import Required Libraries
2. Load Dataset
3. Dataset Inspection
4. Data Cleaning
5. Text Preprocessing
6. Label Encoding
7. TF-IDF Feature Extraction
8. Train-Test Split
9. Train Multiple Classification Models
10. Model Evaluation
11. Model Comparison
12. WordCloud Visualization
13. Spam Prediction
14. Conclusion

---

# Project Structure

```
DataScience-Task4-EmailSpamDetection
│
├── OIBSIP_Task4_Email_Spam_Detection.ipynb
├── spam.csv
└── README.md
```

---

# Key Insights

The project revealed several important observations:

- Text preprocessing significantly improves classification performance.
- TF-IDF effectively transforms text into meaningful numerical features.
- Both classifiers achieved high prediction accuracy.
- Spam emails contain distinct word patterns compared to legitimate emails.
- Recall is particularly important because missing a spam email can reduce the effectiveness of spam filtering systems.

---

# Future Improvements

Possible future enhancements include:

- Hyperparameter tuning
- Cross-validation
- Advanced NLP techniques
- Word Embeddings (Word2Vec, GloVe)
- Deep Learning using LSTM or Transformer models
- Deployment as a web application using Flask or Streamlit

---

# Learning Outcomes

Through this project, the following concepts were explored:

- Natural Language Processing (NLP)
- Text Preprocessing
- TF-IDF Vectorization
- Text Classification
- Machine Learning
- Model Evaluation
- Binary Classification
- WordCloud Visualization

---

# Internship Information

**Internship:** Oasis Infobyte Internship

**Domain:** Data Science

**Task:** Task 4 – Email Spam Detection using Machine Learning

---

# Author

**Anirban Garai**

GitHub Repository: **OIBSIP**

---

# Conclusion

This project successfully demonstrates how Natural Language Processing and Machine Learning can be combined to automatically classify emails as Spam or Ham.

By applying text preprocessing, TF-IDF feature extraction, multiple classification algorithms, comprehensive model evaluation, and visualization techniques, the project presents a complete end-to-end NLP workflow.

The implementation provides practical experience in text classification and highlights how machine learning can be applied to real-world communication systems to improve email security and user experience.
