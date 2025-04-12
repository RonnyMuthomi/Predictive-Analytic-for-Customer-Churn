# 📉 Predicting Customer Churn for Subscription-Based Businesses

## 📌 Project Overview

In today's competitive digital economy, subscription-based businesses face a major challenge: **customer churn**. Companies lose millions in revenue due to churn, often without understanding the root causes. This project aims to tackle that challenge by analyzing customer behavior patterns, engagement rates, and transaction data to **predict churn risk** and provide actionable insights.

---

## ❓ Problem Statement

> **"Businesses lose millions due to customer churn, but most don't know why people leave."**

The inability to detect early churn signals limits a company's capacity to respond proactively. Understanding *why* customers churn is just as critical as *knowing* who will churn.

---

## 💡 Project Solution

This project uses a combination of **exploratory data analysis (EDA)**, **feature engineering**, and **data visualization** to uncover trends that lead to customer churn. We also leverage predictive modeling techniques to identify at-risk customers before they leave.

---

## 🎯 Objectives

1. **Understand churn behavior** by identifying customer usage patterns and common churn traits.
2. **Determine key factors** that influence customer churn.
3. **Quantify the business impact** of churn (e.g., revenue loss, customer lifetime value).
4. **Predict churn risk** using machine learning.
5. **Communicate findings** through storytelling using Tableau dashboards.
6. **Recommend strategies** for churn mitigation and customer retention.

---

## 🗃️ Dataset Description

- **Source**: Kaggle  
  [`Predictive Analytics for Customer Churn: Dataset`](https://www.kaggle.com/datasets/safrin03/predictive-analytics-for-customer-churn-dataset)

- **Key Columns**:
  - `CustomerID`: Unique customer identifier  
  - `SubscriptionType`: Basic, Premium, or Deluxe  
  - `PaymentMethod`, `PaperlessBilling`  
  - `ViewingHoursPerWeek`, `AccountAge`, `TotalCharges`, `MonthlyCharges`  
  - `SupportTicketsPerMonth`, `UserRating`, `WatchlistSize`, etc.  

> 🔍 **Note**: The dataset does not explicitly contain a churn label. Therefore, a churn indicator was engineered based on user inactivity, low engagement, and usage patterns.

---

## 🛠️ Tools & Technologies

| Category        | Tools Used                              |
|----------------|------------------------------------------|
| Data Handling   | Python, Pandas, NumPy                    |
| Data Visualization | Tableau, Matplotlib, Seaborn        |
| Modeling        | Scikit-learn (Logistic Regression, Decision Trees) |
| IDE             | Jupyter Notebook, VSCode                |

---

## 📊 Methodology

### 1. Data Preprocessing
- Handled missing values
- Converted numerical features appropriately
- Created a binary `Churned` column based on business logic (e.g., no engagement in recent periods)

### 2. Exploratory Data Analysis (EDA)
- Identified patterns in customer engagement and satisfaction
- Visualized churn by subscription type, account age, content type, etc.

  **Analysis chart**
  
   <img src="https://github.com/user-attachments/assets/4c217e92-f6c2-40ae-8a94-be527759de07" height="250">

   <img src="https://github.com/user-attachments/assets/2e17651f-d6df-46ed-826c-2f8456f18f3b" height="250">


### 5. Dashboard in Tableau
- Created interactive visualizations to explain churn insights
- Dashboards include churn trends, user segments, engagement analysis
  **Dashboard**
  https://public.tableau.com/app/profile/ronny.muthomi5399/viz/churn1_17444751962460/customer-churndash?publish=yes

---

## 📈 Key Insights

- Customers with **low viewing hours**, **frequent support tickets**, and **low ratings** were more likely to churn.
- **Deluxe plan users** had the highest retention rate.
- **Electronic Check** users churned more than those using **credit cards** or **PayPal**.
- Majority of churned users had a **small watchlist size** and **minimal content downloads**.

---

## 🛡️ Recommendations

- Target at-risk users with personalized offers or retention campaigns.
- Improve onboarding for low-engagement customers.
- Encourage watchlist building and multiple device access to increase engagement.
- Monitor support tickets as an early churn indicator.

---

## 📌 Folder Structure (Suggested)

