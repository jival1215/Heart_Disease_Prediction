# 🫀 Heart Disease Prediction

## 📌 Overview
This project builds a **machine learning pipeline** to predict whether a patient has heart disease based on various health metrics.  
It uses multiple models, evaluates them with **ROC-AUC**, and saves the best model for reuse.

## 🎯 Objective
- Predict the presence of heart disease (**1 = Disease, 0 = No Disease**).
- Compare multiple classification algorithms.
- Select the best model using **ROC-AUC** as the primary metric.

## 📂 Dataset
- Source: [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+disease) (or your provided CSV).
- Features include: age, sex, cholesterol, resting blood pressure, chest pain type, max heart rate, etc.
- Target: `1` = heart disease present, `0` = no heart disease.

## 🛠 Tech Stack
- **Language:** Python 3.x
- **Libraries:** pandas, numpy, scikit-learn, matplotlib, joblib
- **Model Types:** Logistic Regression, Random Forest, Gradient Boosting

## 📊 Methodology
1. **Data Preprocessing**
   - Missing value imputation
   - Scaling numerical features
   - Encoding categorical variables
2. **Model Training**
   - Logistic Regression
   - Random Forest Classifier
   - Gradient Boosting Classifier
3. **Model Evaluation**
   - ROC-AUC
   - Accuracy
   - F1-score
   - Confusion Matrix
4. **Model Saving**
   - Best model saved as `.pkl` using `joblib`.

## 📈 Results
- **Best Model:** Random Forest
- **ROC-AUC:** 0.8988
- **Accuracy:** 81.97%
- **F1-score:** 0.8533
- **Confusion Matrix:**
