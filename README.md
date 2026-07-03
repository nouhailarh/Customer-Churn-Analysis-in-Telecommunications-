# 📊 Customer Churn Analysis in Telecommunications

## 📌 Project Overview

Customer churn is one of the biggest challenges for telecommunications companies, as losing customers directly impacts revenue and profitability.

This project aims to analyze customer churn, identify the key factors driving customer attrition, predict customers at risk of leaving using Machine Learning, and build an interactive Power BI dashboard to support business decision-making.

---

## 🎯 Objectives

- Explore and understand customer behavior through Exploratory Data Analysis (EDA).
- Identify the main factors influencing customer churn.
- Build and compare Machine Learning models to predict churn.
- Estimate customer churn probability and revenue at risk.
- Design an interactive Power BI dashboard to support retention strategies.

---

## 📂 Dataset

- **Source:** Telco Customer Churn Dataset (Kaggle)
- **Industry:** Telecommunications
- **Customers:** 7,043
- **Target Variable:** `Churn Value`

---

# 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **XGBoost**
- **Power BI**
- **DAX**
- **Power Query**

---

# 🔍 Exploratory Data Analysis (EDA)

The first phase focused on understanding customer behavior and preparing the dataset.

### Data Preparation

- Data inspection
- Missing values verification
- Data type correction
- Feature engineering
- Data cleaning

### Exploratory Analysis

The analysis focused on:

- Customer demographics
- Customer tenure
- Contract types
- Internet services
- Payment methods
- Monthly charges
- Customer Lifetime Value (CLTV)
- Financial impact of churn

### Statistical Validation

To validate the observations, statistical tests were performed:

- **Chi-Square Test** for categorical variables
- **Independent T-Test** for numerical variables

---

# 🤖 Machine Learning

A classification model was developed to predict the probability of churn for active customers.

### Workflow

- Feature Selection
- One-Hot Encoding
- Train/Test Split
- Class Balancing using SMOTE
- Model Training
- Model Comparison
- Best Model Selection
- Customer Risk Prediction

---

## Models Compared

- Logistic Regression
- Random Forest
- XGBoost

Models were evaluated using:

- Recall
- F1-Score
- ROC-AUC

The selected model was then used to generate:

- Churn Probability
- Risk Level
- Revenue at Risk

---

# 📈 Power BI Dashboard

The project includes a three-page interactive dashboard.

---

## 📄 Page 1 — Executive Overview

**Business Question**

> What is happening?

Main indicators:

- Total Customers
- Churn Rate
- Lost Customers
- Annual Revenue Lost
- Average CLTV

Visualizations:

- Churn evolution
- Revenue loss by contract
- Churn by tenure
- Top cities by revenue loss

---

## 📄 Page 2 — Factors & Risks

**Business Question**

> Why are customers leaving?

Analysis includes:

- Most risky contract
- Average tenure of churners
- Most associated service
- Riskiest payment method
- Churn reasons
- Churn by services
- Churn by payment methods

---

## 📄 Page 3 — Predictive Analysis

**Business Question**

> Which customers should be targeted?

Main KPIs:

- High-risk active customers
- Revenue at risk
- Average churn probability
- Average CLTV at risk

Visualizations:

- Risk level distribution
- Probability vs Revenue at Risk
- Top high-risk customers
- Business recommendations

---

# 💡 Key Insights

- Month-to-Month contracts have the highest churn rate.
- Customers with shorter tenure are more likely to leave.
- Customers without Online Security show a significantly higher churn rate.
- Electronic Check is the payment method most associated with churn.
- Machine Learning enables proactive identification of customers likely to churn before they actually leave.

---

# 📊 Business Recommendations

- Prioritize retention efforts for high-risk customers.
- Focus first on customers with the highest revenue at risk.
- Encourage migration to annual contracts.
- Promote Online Security offers.
- Encourage automatic payment methods.

---

# 🚀 Future Improvements

- Deploy the model using an API.
- Automate predictions with scheduled refresh.
- Integrate real-time customer data.
- Monitor churn continuously using Power BI Service.

---


