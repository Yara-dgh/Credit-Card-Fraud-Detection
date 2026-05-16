# 💳 Credit Card Fraud Detection
Pattern Recognition Project - DA360
Yarmouk University

## 📌 Project Overview
This project applies Machine Learning and Pattern Recognition techniques
to detect fraudulent credit card transactions. The dataset is highly 
imbalanced, so we used SMOTE to balance it before training our models.


## 🗂️ Dataset
- Source: Kaggle - Credit Card Fraud Detection
- 284,807 transactions | 492 fraud cases
- Features: V1-V28 (PCA anonymized), Amount, Time, Class
- Link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## ⚙️ Preprocessing Steps
1. Missing values check
2. Feature Scaling (StandardScaler)
3. Outlier Removal (IQR method)
4. PCA - Dimensionality Reduction
5. Train/Test Split + SMOTE balancing

## 🤖 Models Used
| Model | Type |
|---|---|
| Logistic Regression | Linear Classifier |
| Decision Tree | Non-linear Classifier |

## 📊 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## 🛠️ Tools & Libraries
- Python
- pandas, numpy
- scikit-learn
- imbalanced-learn (SMOTE)
- matplotlib, seaborn
- Google Colab
