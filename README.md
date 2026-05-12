# 🏠 California Housing Prices - Regression

Predicting California house prices using the California Housing dataset.

---

## 📁 Project Versions

| Version | Approach | R² |
|---------|----------|----|
| [V1](./California_Housing_v1) | Basic ML - Multiple Models (Linear, GBR, XGBoost, RF) | ~0.82 |
| [V2](./California_Housing_v2) | Pipeline + XGBoost + Cross Validation + Hyperparameter Tuning | 0.841 |
| [V3](./California_Housing_v3) | Full Features + Capped Values Experiment | 0.841+ |

---

## 🧠 Key Learnings

- V1 → V2 : تحول من موديلات منفصلة إلى Pipeline متكامل
- V2 → V3 : اكتشاف مشكلة الـ Capped Values عند 500K وتأثيرها على الموديل

---

## 📦 Requirements

pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost

---

## 📊 Dataset

[California Housing Dataset - Kaggle](https://www.kaggle.com/datasets/camnugent/california-housing-prices)
