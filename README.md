# 🔍 Crime Category Prediction using Machine Learning

This project focuses on predicting **crime categories** using structured data consisting of incident date/time, geographic location, victim demographics, and other related features. The goal is to develop accurate classification models that can effectively identify the type of crime based on these attributes.

---

## 📌 Problem Statement

The objective is to build robust and interpretable machine learning models that can predict the **type of crime** based on:

- Time and date of occurrence  
- Geographical location (latitude, longitude)  
- Victim demographic information  
- Crime descriptions and administrative classifications  
- Other relevant structured data

---

## 🗂️ Project Overview

- Conducted **Exploratory Data Analysis (EDA)** and **data visualization** to understand trends and anomalies  
- Performed **feature engineering** and preprocessing to prepare data for modeling  
- Implemented and tuned **multiple classification models**  
- Applied **hyperparameter optimization** to improve model performance  
- Evaluated all models using metrics such as **accuracy, precision, recall, and F1-score**  
- Selected **XGBoost** as the final model based on test set performance

---

## 🔧 Data Preprocessing

- Handled missing and inconsistent values  
- Encoded categorical variables using **OrdinalEncoder**  
- Extracted time-based features (e.g., hour of day, day of week) from datetime  
- Normalized features using **StandardScaler**  
- Balanced class distribution using **stratified sampling** techniques

---

## 🤖 Models Implemented & Tuned

| Model                | Status            |
|---------------------|-------------------|
| Logistic Regression | ✅ Tuned & Evaluated |
| Random Forest       | ✅ Tuned & Evaluated |
| Gradient Boosting   | ✅ Tuned & Evaluated |
| XGBoost             | ✅ Final Model       |

---

## ✅ Key Takeaways

- Effective feature extraction and class balancing significantly improve classification performance  
- XGBoost outperformed other models in both training and testing phases  
- Real-world structured data requires careful preprocessing and validation for reliable results

---

Feel free to ⭐ the project or leave feedback!
