# 🏦 Bank Customer Attrition Prediction using Machine Learning

## 📌 Project Overview

Customer attrition is one of the biggest challenges faced by banks, as acquiring new customers is significantly more expensive than retaining existing ones. Predicting which customers are likely to leave enables financial institutions to implement proactive retention strategies, improve customer satisfaction, and reduce revenue loss.

This project presents an end-to-end machine learning solution for predicting customer attrition using customer demographics, relationship, credit, and transaction data. The project follows a complete data science workflow, beginning with business understanding and exploratory data analysis, followed by predictive modeling, hyperparameter tuning, model evaluation, and business recommendations.

---

## 🎯 Business Problem

The objective of this project is to identify customers who are likely to discontinue their relationship with the bank (customer churn) before attrition occurs.

By accurately identifying high-risk customers, banks can:

- Improve customer retention
- Reduce revenue loss
- Optimize marketing campaigns
- Enhance customer satisfaction
- Support data-driven business decisions

---

## 📂 Dataset

- **Dataset Name:** BankChurners.csv
- **Records:** 10,127 customers
- **Target Variable:** Attrition_Flag

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---


## 📈 Model Performance

| Model | Training Accuracy | Testing Accuracy |
|--------|------------------:|-----------------:|
| Logistic Regression | 90.60% | 89.90% |
| Decision Tree | 100.00% | 93.00% |
| Tuned Decision Tree | 97.69% | 94.23% |
| ⭐ Tuned Random Forest | **99.85%** | **95.31%** |

The hyperparameter-tuned Random Forest achieved the highest testing accuracy and was selected as the final predictive model.

---

## 💡 Key Business Insights

- Customer behaviour is a stronger predictor of attrition than demographic characteristics.
- Customers with fewer transactions and lower transaction amounts are more likely to churn.
- Increased customer inactivity is strongly associated with higher attrition.
- Customers maintaining relationships across multiple banking products exhibit greater loyalty.
- Frequent customer service contacts may indicate dissatisfaction and increased churn risk.

---

## 🚀 Business Impact

The developed Random Forest model can be integrated into a banking CRM system to identify customers at high risk of attrition. This enables the bank to implement proactive retention strategies, improve customer engagement, and reduce customer churn through targeted interventions.

---

## 📁 Repository Structure

```
Bank-Customer-Attrition-Prediction/
│
├── Bank Attrition Project.ipynb
├── BankChurners.csv
├── README.md

```

---
