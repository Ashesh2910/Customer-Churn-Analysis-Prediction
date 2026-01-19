## 📊 Customer Churn Analysis & Prediction

## Power BI + Python Machine Learning Project

## 🔍 Project Overview

Customer churn is one of the biggest challenges for subscription-based businesses. This project delivers an end-to-end churn analytics and prediction solution designed to help organizations understand why customers leave, identify who is likely to churn next, and take proactive retention action.

## The solution combines:

Power BI for interactive business intelligence and storytelling

Python machine learning for customer-level churn prediction

By integrating predictive outputs into a Power BI dashboard, this project bridges the gap between advanced analytics and business decision-making.

## 💡 Business Problem

Many companies rely on historical churn reports, which explain what already happened but fail to prevent future losses.

This project helps businesses:

Detect churn risk before customers leave

Prioritize retention efforts based on risk level

Optimize decisions around contracts, pricing, and service offerings

## 📊 Dataset

Source: Telco Customer Churn Dataset (Kaggle)

Records: 7,043 customers

Data Includes:

Customer demographics

Contract type and tenure

Services subscribed

Payment methods

Monthly and total charges

Churn indicator

## 📸 Dashboard Previews

## 📸 Dashboard Previews

### Churn Analysis Dashboard
![Churn Analysis Dashboard](<img width="1788" height="731" alt="Screenshot 2026-01-20 005551" src="https://github.com/user-attachments/assets/5c70d65d-b71e-45a0-8036-0a8295acdf66" />
)

### Churn Prediction & Risk Segmentation Dashboard
![Churn Prediction Dashboard](<img width="1787" height="727" alt="Screenshot 2026-01-20 005527" src="https://github.com/user-attachments/assets/5600efd0-f488-4153-9b22-4b512401eb58" />
)


## 🛠 Tech Stack

Power BI

Interactive dashboards

DAX measures

Risk segmentation visuals

Python

pandas

scikit-learn

Machine Learning

Logistic Regression

Data Formats

CSV / Excel

## 🔄 Project Workflow

# 1️⃣ Data Cleaning & Preparation

Converted TotalCharges to numeric format

Handled missing values

Created churn flag and model-ready features

# 2️⃣ Churn Analysis (Power BI)

Overall churn rate

Churn by:

Contract type

Internet service

Payment method

Comparison of tenure and charges between churned and retained customers

# 3️⃣ Churn Prediction (Python)

Trained a Logistic Regression model

## Key features:

Tenure

MonthlyCharges

TotalCharges

Contract type

Internet service

Payment method

Model output:

ChurnProbability

ChurnPredicted

# 4️⃣ Prediction Dashboard (Power BI)

Integrated ML predictions into Power BI

Segmented customers into:

High Risk: ≥ 0.70

Medium Risk: 0.40 – 0.69

Low Risk: < 0.40

Built visuals for targeted retention analysis

## 📌 Key Insights

Month-to-month contracts have the highest churn rate

Customers with higher monthly charges are more likely to churn

Early-tenure customers are especially vulnerable

Customers without support and security services churn more often

## 🎯 Business Recommendations

Based on the analysis and predictions:

Encourage customers to move to long-term contracts

Proactively target high-risk customers with retention offers

Improve onboarding and engagement for new customers

Bundle technical support and security services to increase stickiness

## 📸 Dashboards Included

Churn Analysis Dashboard
Visualizes churn drivers and customer behavior

Churn Prediction & Risk Segmentation Dashboard
Highlights high-risk customers to support targeted action

## 🌱 Future Enhancements

Real-time churn scoring

Customer Lifetime Value (CLV) integration

Advanced models (XGBoost, Random Forest)

CRM automation for retention actions

## 🚀 Key Takeaway

This project demonstrates how analytics and machine learning can be operationalized to support real business outcomes. It moves beyond static reporting and delivers a proactive, insight-driven approach to customer retention.
