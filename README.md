# churn-ltv-prediction
Churn and lifetime value prediction using XGBoost and SHAP on Telco dataset


# 🧠 Customer Churn & Lifetime Value Prediction

This end-to-end project predicts **customer churn** and **lifetime value (LTV)** using the Telco dataset and interpretable machine learning models.

---

## 📌 Problem Statement
Customer churn leads to major revenue loss for subscription-based businesses. This project predicts whether a customer is likely to churn and estimates their future revenue using regression models.

---

## 📊 Tools & Libraries
- Python | pandas | scikit-learn | XGBoost | SHAP
- seaborn | matplotlib | Jupyter

---

## 📁 Dataset
**Telco Customer Churn Dataset**  
Source: [Kaggle - Telco Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
Features include: tenure, contract type, charges, payment method, services, and more.

---

## 🔧 Methodology
- Cleaned missing values in `TotalCharges`
- Engineered features like tenure groups, service count, and interaction terms
- **Classification model** (churn): XGBoost + SHAP for explainability
- **Regression model** (LTV): XGBoostRegressor based on tenure and charges
- Avoided leakage by removing post-churn variables

---

## 📈 Results
- Churn prediction F1-score: **84%**
- LTV prediction MAE: **±$12**
- SHAP revealed top churn factors: month-to-month contracts, high tenure drop-off, online security absence

---

## 📌 Key Takeaways
- Combines classification and regression in one pipeline
- Interpretable ML using SHAP for stakeholder trust
- Ready for business-facing dashboards (Tableau optional)

---

## 📁 Project Structure
