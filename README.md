# 🤰 Pregnancy & Fetal Health Risk Prediction

# 🤖 Dual-Model Machine Learning for Maternal & Fetal Health Risk Prediction

A dual-model machine learning project aiming to improve maternal and fetal healthcare through predictive analytics. We built two separate classifiers:

- **🔹 PredictRisk**: Predicts pregnancy risk levels (`low`, `mid`, `high`) using maternal physiological parameters.
- **🔹 Fetal Health Classifier**: Assesses fetal health condition based on cardiotocograms (CTG) data.

---

## 🌟 Key Features

### ✅ Pregnancy Risk Prediction
Utilizes health indicators such as:
- Age  
- Blood Sugar Levels  
- Blood Pressure  
- Body Temperature  
- Heart Rate  

to classify maternal risk into:
- **Low**
- **Mid**
- **High**

---

### ✅ Fetal Health Prediction
Analyzes CTG (Cardiotocogram) data, including:
- Baseline Fetal Heart Rate  
- Accelerations  
- Uterine Contractions  
- Variability and Decelerations  

to classify fetal health into three categories using:
- **Gradient Boosting Classifier**

---

This repository presents a comprehensive machine learning pipeline for:

1. **Maternal Health Risk Prediction** – using physiological features to classify risk levels.
2. **Fetal Health Prediction** – using CTG features to determine fetal well-being.

---

## 🔍 Project Overview

### 1. Maternal Health Risk Predictor (`PredictRisk`)
- **Objective**: Classify maternal health risk into `Low`, `Mid`, or `High`.
- **Dataset**: [Maternal Health Risk Data Set](https://www.kaggle.com/datasets/andrewmvd/maternal-health-risk-data)
- **Best Model**: Gradient Boosting Classifier
- **Accuracy**: ~84%

### 2. Fetal Health Classifier
- **Objective**: Predict fetal health condition (3 classes) using CTG recordings.
- **Dataset**: [Fetal Health Classification Data](https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification)
- **Best Model**: Gradient Boosting Classifier
- **Accuracy**: ~90%

---

## 🧪 Models Used
- Logistic Regression
- K-Nearest Neighbors
- Random Forest Classifier
- Gradient Boosting Classifier (Best performing for both tasks)

---

## 📈 Evaluation Metrics
- Accuracy, Precision, Recall, F1 Score
- Confusion Matrix
- Cross-validation

---

## 🔍 Notebooks & Scripts
- 📁 `maternal_health_risk/` — code and model for maternal risk
- 📁 `fetal_health_prediction/` — code and model for fetal risk
- 🧠 Saved models (`.sav`) using `pickle`

---

## 💾 Deployment
The models can be easily deployed via:
- Flask or FastAPI for backend APIs
- Streamlit dashboards for real-time input and prediction
- Integration with EHR systems

---

## 📊 Results Summary

| Model                    | Accuracy | Precision | Recall | F1 Score |
|-------------------------|----------|-----------|--------|----------|
| Maternal - Gradient Boosting | 84.2%   | 84.2%     | 84.2%  | 84.1%    |
| Fetal - Gradient Boosting    | ~90%    | —         | —      | —        |

---

## ✍️ Author
- **[Your Name]**  
  M.Sc. Data Science | Aspiring ML Engineer  
  📧 your.email@example.com  
  🌐 [LinkedIn](#) | [Portfolio](#)

