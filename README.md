#  Heart Disease Prediction using Logistic Regression

## 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early prediction can help healthcare professionals take preventive action.

This project builds a Machine Learning classification model using Logistic Regression to predict whether a patient has heart disease based on various medical attributes.

---

## 📊 Dataset Information

The dataset contains medical attributes such as:

- Age  
- Sex  
- Chest Pain Type (cp)  
- Resting Blood Pressure (trestbps)  
- Cholesterol (chol)  
- Fasting Blood Sugar (fbs)  
- Resting ECG (restecg)  
- Maximum Heart Rate Achieved (thalach)  
- Exercise Induced Angina (exang)  
- ST Depression (oldpeak)  
- Slope  
- Number of Major Vessels (ca)  
- Thal  

### 🎯 Target Variable

- `1` → Heart Disease Present  
- `0` → No Heart Disease  

---

## ⚙️ Project Workflow

1. Data Loading and Exploration  
2. Feature & Target Separation  
3. Train-Test Split (80-20)  
4. Feature Scaling using StandardScaler  
5. Logistic Regression Model Training  
6. Model Evaluation using:
   - Accuracy  
   - Precision  
   - Recall  
   - F1 Score  
   - Confusion Matrix  

---

## 📈 Model Performance

| Metric      | Score |
|------------|--------|
| Accuracy   | 86% |
| Precision  | 87% |
| Recall     | 87% |
| F1 Score   | 87% |

*Performance may vary slightly depending on train-test split.*

---

## 🧠 Model Explanation

Logistic Regression predicts the log-odds of heart disease:

log(p / (1 - p)) = β₀ + β₁X₁ + β₂X₂ + ...

The sigmoid function converts this value into a probability between 0 and 1.

If probability > 0.5 → Heart Disease predicted  
If probability ≤ 0.5 → No Heart Disease  

---

## 🛠️ Tech Stack

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## 📂 Project Structure

```
heart-disease-prediction-logistic-regression/
│
├── heart.csv
├── logistic_regression.ipynb
├


## 👤 Author
Amit Parmar  
