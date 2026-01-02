# Customer Churn Analysis (End-to-End Case Study)

## Project Overview
Customer churn is one of the most important challenges for subscription-based businesses.  
This project presents an end-to-end churn analysis case study, covering data preparation, exploratory analysis, feature engineering, predictive modeling, postdictive analysis, and business recommendations.

The goal is not just to build a predictive model, but to **understand why customers churn** and how businesses can act on those insights.

---

## Business Problem
Customer churn occurs when a customer stops using a company’s service.  
Reducing churn is critical because acquiring new customers is significantly more expensive than retaining existing ones.

This project aims to:
- Identify key drivers of churn
- Predict churn risk at the customer level
- Translate model outputs into actionable retention strategies

---

## Dataset
The dataset contains customer demographics, subscription details, service usage, billing information, and churn labels.

**Target variable:**  
- `Churn` (Yes / No)

---

## Methodology

### 1. Data Cleaning & Preparation
- Validated data types and target variable
- Handled missing and inconsistent values
- Standardized categorical variables

### 2. Exploratory Data Analysis (EDA)
- Compared churned vs non-churned customers
- Analyzed tenure, pricing, contract type, and service usage
- Identified early-tenure and high-cost customers as high-risk groups

### 3. Feature Engineering
- Created meaningful business features such as:
  - Tenure groups
  - Number of subscribed services
  - High monthly charge indicator
  - Long-term contract indicator
- Encoded categorical variables for modeling

### 4. Modeling
Two classification models were trained and evaluated:
- **Logistic Regression** (baseline, interpretable)
- **Random Forest** (non-linear comparison)

**Evaluation metrics:**
- Precision, Recall, F1-score
- Confusion Matrix
- ROC-AUC

### 5. Postdictive Analysis
- Analyzed false negatives (missed churners) and false positives
- Identified where the model performs well and where it fails
- Highlighted data limitations and unobserved churn drivers

---

## Key Results
- Logistic Regression achieved a **ROC-AUC of ~0.84**
- The model performs well at **ranking churn risk**, making churn probability more useful than binary predictions
- High churn risk is associated with:
  - Short tenure
  - High monthly charges
  - Month-to-month contracts
  - Electronic check payments

---

## Business Recommendations
- Prioritize retention efforts for **early-tenure, high-paying customers**
- Encourage migration to **long-term contracts and auto-pay**
- Improve onboarding and early customer experience
- Use churn probability scores to target retention campaigns efficiently


---

## Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Jupyter Notebook

---
