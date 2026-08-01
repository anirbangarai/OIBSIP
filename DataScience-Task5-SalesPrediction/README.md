# Sales Prediction using Machine Learning

## Project Overview

This project was completed as part of the **Oasis Infobyte Data Science Internship**.

The objective of this project is to develop a machine learning regression model capable of predicting product sales based on advertising expenditure across different marketing channels. By analyzing historical advertising data, businesses can estimate future sales and optimize their marketing budgets more effectively.

The project demonstrates a complete end-to-end machine learning workflow, including data preprocessing, exploratory data analysis (EDA), regression modeling, model evaluation, feature importance analysis, and sales prediction.

---

# Objective

The primary objectives of this project are:

- Analyze the relationship between advertising expenditure and product sales.
- Perform data cleaning and exploratory data analysis.
- Visualize relationships among advertising channels and sales.
- Train multiple regression models.
- Compare model performance using standard regression metrics.
- Predict product sales for new advertising budgets.
- Identify the advertising channel with the greatest impact on sales.

---

# Dataset

The project uses the **Advertising Dataset**, which contains advertising budgets allocated across different media channels.

### Dataset Information

The dataset consists of the following variables:

- TV Advertising Budget
- Radio Advertising Budget
- Newspaper Advertising Budget
- Sales (Target Variable)

Target Variable:

- **Sales**

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

# Data Preprocessing

Before training the machine learning models, the dataset was carefully inspected and prepared.

The preprocessing steps included:

- Dataset loading
- Dataset inspection
- Shape verification
- Data type inspection
- Missing value analysis
- Missing value visualization
- Duplicate record checking
- Removal of unnecessary columns (if present)
- Statistical summary

These preprocessing steps ensured the dataset was clean and ready for model training.

---

# Exploratory Data Analysis (EDA)

Several exploratory analyses were performed to understand the relationship between advertising expenditure and sales.

### Visualizations Created

- Sales Distribution
- Pairplot
- Sales vs TV Advertising
- Sales vs Radio Advertising
- Sales vs Newspaper Advertising
- Correlation Heatmap

Each visualization includes observations explaining the patterns identified within the dataset.

---

# Machine Learning Models

Two supervised machine learning regression algorithms were trained and evaluated.

## 1. Linear Regression

A baseline regression model that estimates sales using a linear relationship between advertising expenditure and sales.

---

## 2. Random Forest Regressor

An ensemble learning algorithm capable of modeling complex and non-linear relationships between advertising channels and product sales.

---

# Model Evaluation

The regression models were evaluated using the following metrics:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

The best-performing model was selected based on prediction accuracy and overall goodness of fit.

---

# Feature Importance Analysis

Feature importance analysis was performed using the Random Forest Regressor.

This analysis identifies which advertising channel contributes most significantly to predicting product sales.

Understanding feature importance enables businesses to allocate advertising budgets more efficiently.

---

# Residual Analysis

Residual analysis was performed to evaluate the quality of the regression model.

The residual plot helps determine whether prediction errors are randomly distributed around zero, indicating that the model provides a good fit for the data.

---

# Project Workflow

1. Import Required Libraries
2. Load Dataset
3. Dataset Inspection
4. Data Cleaning
5. Missing Value Analysis
6. Exploratory Data Analysis
7. Correlation Analysis
8. Train-Test Split
9. Train Regression Models
10. Model Evaluation
11. Model Comparison
12. Residual Analysis
13. Feature Importance Analysis
14. Sales Prediction
15. Conclusion

---

# Project Structure

```
DataScience-Task5-SalesPrediction
│
├── OIBSIP_Task5_Sales_Prediction.ipynb
├── Advertising.csv
└── README.md
```

---

# Key Insights

The analysis revealed several important findings:

- TV advertising shows the strongest relationship with product sales.
- Radio advertising also contributes positively to sales prediction.
- Newspaper advertising has a comparatively weaker influence.
- Random Forest effectively captures complex relationships among advertising variables.
- Feature importance analysis highlights the advertising channels that most influence sales.

---

# Future Improvements

Possible future enhancements include:

- Hyperparameter tuning using GridSearchCV
- Cross-validation for improved model generalization
- Advanced ensemble regression algorithms such as XGBoost
- Interactive sales prediction dashboard using Streamlit
- Deployment as a web application using Flask

---

# Learning Outcomes

Through this project, the following concepts were explored:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Regression Analysis
- Correlation Analysis
- Machine Learning
- Feature Importance
- Model Evaluation
- Predictive Analytics

---

# Internship Information

**Internship:** Oasis Infobyte Internship

**Domain:** Data Science

**Task:** Task 5 – Sales Prediction using Machine Learning

---

# Author

**Anirban Garai**

GitHub Repository: **OIBSIP**

---

# Conclusion

This project successfully demonstrates how machine learning regression techniques can be used to predict product sales based on advertising expenditures across multiple media channels.

By combining data preprocessing, exploratory data analysis, regression modeling, feature importance analysis, residual analysis, and model evaluation, the project presents a complete end-to-end predictive analytics workflow.

The implementation highlights how data-driven insights can help businesses optimize advertising strategies, improve marketing efficiency, and make informed decisions based on predictive models.
