# Retail Sales Profitability Classification Project

## Overview
This project focuses on analyzing retail sales data to build a classification model that predicts whether an order will be profitable or not. It includes data cleaning, feature engineering, model building, and actionable business insights.

## Dataset
- Source: Superstore sales data
- 9,000+ rows
- 18 columns including sales, profit, category, region, shipping details, etc.

## Objective
Classify retail orders as **Profitable (1)** or **Non-Profitable (0)** using historical sales and shipping data.

---

## Tools & Technologies
- Python (Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn)
- Jupyter Notebook
- Git & GitHub

---

## Process Breakdown

### 1. Data Cleaning & Preprocessing
- Removed unnecessary columns (Row ID, Country, Postal Code, etc.)
- Handled date formats
- Created new features (Shipping Duration, Order Month, etc.)
- Label Encoded categorical data

### 2. Feature Engineering
- Converted profit column into a binary target variable
- Removed 'Profit', 'Customer ID', etc., from the model training features

### 3. Model Building
- Model Used: Random Forest Classifier
- Accuracy Achieved: **94.7%**
- Confusion Matrix, Classification Report & Feature Importance analyzed

### 4. Business Insights
- High discounts & longer shipping durations reduce profitability
- Profitability varies across regions and categories
- Recommendations provided to optimize profitability

---

## Conclusion
- Built a robust model to predict order profitability
- Generated insights to support strategic business decisions in marketing, pricing, and logistics

---

## Author
Sriharsha | Data Science & Analytics Enthusiast  
LinkedIn: [https://www.linkedin.com/in/sriharsha-aithal/]  
GitHub: [https://github.com/harsh-aithal/]
