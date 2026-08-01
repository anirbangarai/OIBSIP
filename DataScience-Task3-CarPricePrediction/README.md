# Car Price Prediction using Machine Learning

## Project Overview

This project was completed as part of the **Oasis Infobyte Data Science Internship**.

The objective of this project is to develop a machine learning regression model capable of predicting the selling price of used cars based on various vehicle characteristics such as brand, manufacturing year, fuel type, transmission type, kilometers driven, and ownership history.

The project demonstrates a complete machine learning workflow including data preprocessing, feature engineering, exploratory data analysis (EDA), model training, evaluation, feature importance analysis, and prediction of selling prices for new car records.

---

# Objective

The primary objectives of this project are:

- Analyze the factors affecting used car prices.
- Clean and preprocess the dataset.
- Perform feature engineering to improve model performance.
- Explore relationships between different vehicle attributes.
- Train multiple regression models.
- Compare model performance using regression evaluation metrics.
- Predict the selling price of used cars accurately.

---

# Dataset

The project uses the **Car Data** dataset containing information about used vehicles.

### Dataset Information

The dataset includes features such as:

- Car Name
- Year
- Selling Price
- Present Price
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission
- Owner

Target Variable:

- **Selling Price**

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

Before training the machine learning models, the dataset was carefully prepared.

The preprocessing steps included:

- Dataset loading
- Dataset inspection
- Missing value analysis
- Duplicate record checking
- Data cleaning
- Feature engineering
- Creation of Car Age feature
- Removal of unnecessary columns
- Encoding categorical variables

These preprocessing steps improve model accuracy and ensure data consistency.

---

# Exploratory Data Analysis (EDA)

Several exploratory analyses were performed to better understand the dataset.

### Visualizations Created

- Selling Price Distribution
- Selling Price vs Car Age
- Selling Price vs Fuel Type
- Selling Price vs Transmission
- Correlation Heatmap
- Feature Relationship Analysis

These visualizations helped identify patterns and important variables influencing car prices.

---

# Feature Engineering

Feature engineering was performed to improve prediction performance.

The following transformations were applied:

- Calculated **Car Age** from the manufacturing year.
- Encoded categorical variables.
- Removed unnecessary columns.
- Prepared numerical features for regression modeling.

---

# Machine Learning Models

Two regression algorithms were trained and evaluated.

## 1. Linear Regression

A baseline regression model used to understand the linear relationship between vehicle features and selling price.

---

## 2. Random Forest Regressor

An ensemble learning algorithm capable of capturing complex non-linear relationships between features and the target variable.

---

# Model Evaluation

The regression models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

The best-performing model was selected based on prediction accuracy and goodness of fit.

---

# Feature Importance Analysis

Feature importance analysis was performed using the Random Forest model.

This analysis identifies which vehicle characteristics contribute most to predicting the selling price.

The feature importance chart helps understand how different variables influence price estimation.

---

# Project Workflow

1. Import Required Libraries
2. Load Dataset
3. Dataset Inspection
4. Data Cleaning
5. Missing Value Analysis
6. Feature Engineering
7. Exploratory Data Analysis
8. Correlation Analysis
9. Feature Encoding
10. Train-Test Split
11. Train Regression Models
12. Model Evaluation
13. Model Comparison
14. Feature Importance Analysis
15. Sample Price Prediction
16. Conclusion

---

# Project Structure

```
DataScience-Task3-CarPricePrediction
│
├── OIBSIP_Task3_Car_Price_Prediction.ipynb
├── car data.csv
└── README.md
```

---

# Key Insights

The project revealed several important findings:

- Car age significantly influences selling price.
- Newer vehicles generally have higher resale values.
- Fuel type and transmission affect market price.
- Random Forest captures complex feature relationships more effectively than simple linear regression.
- Feature importance analysis highlights the variables that most strongly impact price prediction.

---

# Future Improvements

Possible future enhancements include:

- Hyperparameter tuning using GridSearchCV
- Cross-validation for better generalization
- Advanced ensemble models such as XGBoost
- Deployment using Streamlit or Flask
- Integration with a real-time used car price prediction application

---

# Learning Outcomes

Through this project, the following concepts were explored:

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Regression Algorithms
- Model Evaluation
- Feature Importance
- Predictive Modeling

---

# Internship Information

**Internship:** Oasis Infobyte Internship

**Domain:** Data Science

**Task:** Task 3 – Car Price Prediction using Machine Learning

---

# Author

**Anirban Garai**

GitHub Repository: **OIBSIP**

---

# Conclusion

This project successfully demonstrates how machine learning regression techniques can be used to estimate the selling price of used cars based on historical vehicle data.

By combining data preprocessing, feature engineering, exploratory data analysis, regression modeling, feature importance analysis, and model evaluation, the project presents a complete end-to-end predictive analytics workflow.

The implementation provides practical experience in regression-based machine learning and highlights how data-driven models can assist buyers, sellers, and businesses in making informed pricing decisions.
