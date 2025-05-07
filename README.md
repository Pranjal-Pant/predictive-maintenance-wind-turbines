# Predictive Maintenance for Wind Turbines

This project applies machine learning to predict equipment failures in wind turbines using sensor data. The goal is to reduce maintenance downtime by forecasting potential failures before they occur.

## 📌 Problem Statement
Wind turbines generate large volumes of sensor data. Unplanned maintenance is costly and disruptive. This project builds predictive models that can identify early warning signs of failure.

## 🧠 Model Overview
Three models were trained:
- Logistic Regression
- Random Forest
- XGBoost

XGBoost performed best, with ~90% accuracy and strong recall.

## 📊 Dataset
- Records: ~20,000
- Features: Temp, pressure, vibration, etc.
- Target: Failure (1) or Normal (0)

## 📈 Results

| Model           | Accuracy | Recall | F1 Score |
|----------------|----------|--------|----------|
| Logistic Reg    | 84%     | 79%    | 80%      |
| Random Forest   | 88%     | 84%    | 85%      |
| **XGBoost**     | 90%     | 88%    | 88%      |

## 🧰 Tools Used
Python, Pandas, Scikit-learn, XGBoost, Matplotlib, Seaborn

## ✅ Next Steps
- Deploy model as a REST API
- Add SHAP for interpretability
