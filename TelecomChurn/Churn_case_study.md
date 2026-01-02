### Step 1: Problem Framing
1.1 **Business Context**

The dataset represents a subscription-based telecommunications business.
Each row corresponds to a customer, capturing:
- Demographic information (e.g. gender, senior citizen status)
- Subscription details (contract type, internet service, add-on services)
- Usage and billing data (tenure, monthly charges, total charges)
- Engagement and payment behavior
- A churn indicator

The company’s goal is to understand, predict, and reduce customer churn.


**1.2 What Is Churn in This Context?**

In this business context, churn refers to:

A customer who has cancelled their subscription or stopped using the company’s services.

The target variable is the Churn column:
- Churn = "Yes" → Customer has churned
- Churn = "No" → Customer is still active
This makes churn a binary classification problem.


**1.3 Why Is Churn Important?**

Customer churn is a critical business problem for subscription-based companies because:
- Acquiring new customers is significantly more expensive than retaining existing ones
- High churn leads to:

    - Revenue loss

    - Increased marketing and acquisition costs

    - Lower customer lifetime value (CLV)

- Churn often signals:

    - Poor customer experience

    - Pricing or contract dissatisfaction

    - Low product engagement

*By identifying customers who are at risk of churning, the company can:*
- Take proactive retention actions
- Improve customer satisfaction
- Increase long-term revenue stability


**1.4 Problem Statement**

The objective of this project is to:

Analyze customer behavior and subscription patterns to identify key drivers of churn and build a predictive model that can flag customers at high risk of churning.

This includes:
- Understanding behavioral differences between churned and retained customers
- Engineering meaningful features related to tenure, services, and engagement
- Training and evaluating a classification model to predict churn
- Translating analytical insights into actionable business recommendations


**1.5 Success Criteria**

This project will be considered successful if it:
- Clearly identifies patterns and signals associated with churn
- Produces a model that can reasonably distinguish churners from non-churners
- Provides interpretable insights that stakeholders can act on
- Demonstrates strong business understanding, not just technical execution