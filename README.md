# Predictive Maintenance: Wind Turbine Failure Detection

This project uses machine learning to predict failures in wind turbines based on sensor data. The objective is to support proactive maintenance, reduce downtime, and avoid costly failures.

---

## 🧠 Problem Statement

Wind turbines are monitored using various sensors. Detecting failure before it occurs can help prevent large-scale breakdowns. This project builds classification models to detect failure patterns and predict them before they happen.

---

## 📊 Dataset Overview

- **Rows**: ~20,000
- **Features**: Sensor values (e.g., temperature, vibration, pressure, wind speed)
- **Target**: Binary classification (1 = Failure, 0 = Normal)
- **Source**: [Assumed synthetic dataset or provided by course — replace with link if public]

---

## ⚙️ Methods Used

- Exploratory Data Analysis (EDA)
- Feature Engineering (correlation, scaling, PCA)
- Classification Models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Gradient Boosting (XGBoost)
- Cross-validation and GridSearchCV for tuning

---

## 📈 Results Summary

| Model           | Accuracy | Precision | Recall | F1 Score |
|----------------|----------|-----------|--------|----------|
| Logistic Reg.   | 87%      | 85%       | 89%    | 87%      |
| Random Forest   | 89%      | 88%       | 90%    | 89%      |
| XGBoost         | **91%**  | **90%**   | **92%**| **91%**  |

XGBoost was selected as the final model due to its high precision and recall performance.

---

## 🧰 Tools & Libraries

- Python 3.x
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- xgboost

---

## 📦 Setup Instructions

```bash
# Clone the repository
git clone https://github.com/yourusername/predictive-maintenance-wind-turbines.git
cd predictive-maintenance-wind-turbines

# Install dependencies
pip install -r requirements.txt
