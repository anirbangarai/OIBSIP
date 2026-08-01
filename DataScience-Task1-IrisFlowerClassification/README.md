# Iris Flower Classification using Machine Learning

## Project Overview

This project was completed as part of the **Oasis Infobyte Data Science Internship**.

The objective of this project is to build a machine-learning classification model that accurately identifies an Iris flower Species based on its physical measurements. The Iris dataset is one of the most widely used benchmark datasets in machine learning and pattern recognition.

The notebook covers the complete machine learning workflow, including data exploration, visualization, feature analysis, model training, evaluation, comparison of multiple classification algorithms, and prediction of new samples.

---

# Objective

The primary objective of this project is to classify Iris flowers into one of the following three species:

- Iris Setosa
- Iris Versicolor
- Iris Virginica

using four flower measurements:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

---

# Dataset

This project uses the **built-in Iris dataset** provided by Scikit-learn.

```python
from sklearn.datasets import load_iris
```

No external dataset download is required.

### Dataset Information

- Total Samples: **150**
- Features: **4**
- Target Classes: **3**

Target Classes:

- Setosa
- Versicolor
- Virginica

---

# Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# Exploratory Data Analysis (EDA)

Several exploratory data analysis techniques were performed before training the machine learning models.

### Dataset Inspection

- Dataset Shape
- Column Information
- Data Types
- Statistical Summary
- Missing Value Analysis

### Data Visualization

- Pairplot
- Boxplots
- Correlation Heatmap

These visualizations helped to understand feature distributions and relationships between different Iris species.

---

# Machine Learning Models

Three supervised machine learning algorithms were trained and evaluated.

## 1. Logistic Regression

A linear classification algorithm used as a baseline model.

---

## 2. K-Nearest Neighbors (KNN)

A distance-based classification algorithm that predicts classes based on neighboring samples.

---

## 3. Random Forest Classifier

An ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy.

---

# Model Evaluation

The models were evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

Performance metrics included:

- Precision
- Recall
- F1-Score

The best-performing model was selected based on overall classification accuracy.

---

# Feature Analysis

Feature importance analysis indicates that:

- Petal Length
- Petal Width

are the most influential features for identifying Iris species.

These features contribute significantly more than sepal measurements during classification.

---

# Project Workflow

1. Import Required Libraries
2. Load Iris Dataset
3. Dataset Inspection
4. Data Cleaning
5. Exploratory Data Analysis
6. Feature Selection
7. Train-Test Split
8. Train Multiple Classification Models
9. Model Evaluation
10. Model Comparison
11. Best Model Selection
12. Sample Prediction
13. Conclusion

---

# Project Structure

```
DataScience-Task1-IrisFlowerClassification
│
├── OIBSIP_Task1_Iris_Flower_Classification.ipynb
└── README.md
```

---

# Future Improvements

Possible enhancements include:

- Hyperparameter tuning
- Cross-validation
- Additional ensemble learning techniques
- Deployment using Flask or Streamlit
- Interactive prediction interface

---

# Learning Outcomes

Through this project, the following concepts were explored:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Data visualization
- Feature importance
- Classification algorithms
- Model evaluation
- Machine Learning workflow

---

# Internship Information

**Internship:** Oasis Infobyte Internship

**Domain:** Data Science

**Task:** Task 1 – Iris Flower Classification

---

# Author

**Anirban Garai**

GitHub Repository: **OIBSIP**

---

# Conclusion

This project successfully demonstrates how machine learning algorithms can accurately classify Iris flower species using simple physical measurements.

The implementation follows a complete end-to-end machine learning pipeline, beginning with data exploration and ending with model comparison and prediction. It provides a strong foundation for understanding supervised classification techniques and their real-world applications in data science.
