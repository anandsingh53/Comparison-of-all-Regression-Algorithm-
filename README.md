# E-commerce Sales Machine Learning Algorithm Comparison

## 📌 Project Overview
This project compares multiple Machine Learning algorithms on an E-commerce sales dataset to evaluate their performance in both **regression** and **classification** tasks.

## 📊 Dataset
**ecommerce_sales_data.csv**

Columns:
- Order Date
- Product Name
- Category
- Region
- Quantity
- Sales
- Profit

## 🎯 Objectives
- Predict Sales using regression models
- Classify High vs Low Sales
- Compare accuracy and error metrics
- Apply PCA for dimensionality reduction

## 🤖 Algorithms Used

### Regression
- Multiple Linear Regression
- KNN Regressor
- Decision Tree Regressor
- Support Vector Regressor

### Classification
- Logistic Regression
- KNN Classifier
- Naïve Bayes
- Decision Tree Classifier
- Support Vector Machine
- PCA + Logistic Regression

## 🧪 Evaluation Metrics
- Mean Squared Error (Regression)
- Accuracy (Classification)

## ▶️ How to Run
```bash
pip install -r requirements.txt
python src/main.py
