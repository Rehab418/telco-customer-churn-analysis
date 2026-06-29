# 📊 Customer Churn Analysis Dashboard | Power BI

## 📌 Project Overview

Customer churn is one of the most important business challenges for subscription-based companies. Losing customers directly impacts revenue and increases customer acquisition costs.

This project analyzes customer churn using Power BI to identify:

- Customers most likely to churn
- Revenue at risk
- Customer retention performance
- High-risk customer segments
- Business drivers behind churn

The dashboard enables decision-makers to monitor KPIs, explore customer behavior, and identify actionable insights to improve retention.

---

# 🎯 Business Objectives

- Measure customer churn and retention.
- Calculate monthly revenue loss caused by churn.
- Identify high-risk customers.
- Analyze churn by customer demographics and services.
- Discover revenue at risk.
- Enable interactive customer exploration.

---

# 📂 Dataset

**Source:** Telco Customer Churn Dataset

The dataset contains customer information including:

- Customer demographics
- Contract type
- Internet service
- Payment method
- Monthly charges
- Tenure
- Customer status (Churn / No Churn)

---

# 🛠 Tools Used

- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Field Parameters
- Git & GitHub

---

# 📐 Data Model

The project follows a Star Schema design.

### Fact Table

- Telco_Churn

### Dimension Tables

- Date
- KPI Parameter
- Customer Segmentation Parameters

---

# 📊 Dashboard Pages

## 1️⃣ Executive Dashboard

Provides an overview of the business performance.

### KPIs

- Total Customers
- Churned Customers
- Churn Rate
- Retention Rate
- Monthly Revenue Lost
- Revenue at Risk
- Average Monthly Charge

### Interactive Features

- Dynamic KPI Selection
- Time Period Selector
- Revenue Analysis
- Churn Distribution
- Demographic Analysis
- Payment Method Analysis

---

## 2️⃣ Customer Risk Dashboard

Customers are segmented into four risk categories:

- 🔴 Critical
- 🟠 High
- 🟡 Medium
- 🟢 Low

Each segment displays:

- Customer Count
- Monthly Revenue
- Average Monthly Charge
- Fiber Optic %
- Electronic Check %
- Average Tenure

Additionally, a table highlights the highest-risk customers.

---

## 3️⃣ Customer Explorer

An interactive customer-level report that allows users to:

- Search customers
- Filter by:
  - Risk Level
  - Internet Service
  - Contract Type
  - Payment Method

Customer information includes:

- Customer ID
- Gender
- Senior Citizen
- Tenure
- Internet Service
- Contract
- Payment Method
- Tech Support
- Monthly Charges
- Risk Score
- Risk Level

---

# 📈 Key Metrics

Examples of DAX measures include:

- Customer Count
- Churn Rate
- Retention Rate
- Revenue at Risk
- Monthly Revenue Lost
- Average Monthly Charge

---

# ✨ Features

- Dynamic KPI Selection using Field Parameters
- Interactive slicers
- Drill-through analysis
- Responsive dashboard layout
- Customer Risk Scoring
- Dynamic visuals
- Clean star schema model

---

# 💡 Business Insights

The dashboard helps answer questions such as:

- Which customers are most likely to churn?
- Which payment methods have higher churn?
- Which contract types retain customers longer?
- How much monthly revenue is being lost?
- Which customer segments require immediate attention?

---

# 📷 Dashboard Preview

## Executive Dashboard

<img src="images/dashboard1.png" width="900"/>

## Customer Risk Dashboard

<img src="images/dashboard2.png" width="900"/>

## Customer Explorer

<img src="images/dashboard3.png" width="900"/>

---

# 🚀 Project Structure

```
Customer-Churn-Analysis/
│
├── Dashboard/
│   └── Customer Churn.pbix
│
├── Dataset/
│   └── Telco_Churn.csv
│
├── Images/
│   ├── dashboard1.png
│   ├── dashboard2.png
│   └── dashboard3.png
│
├── README.md
└── LICENSE
```

---

# 📌 Skills Demonstrated

- Data Cleaning
- Data Modeling
- Star Schema Design
- Power Query
- DAX
- Business Intelligence
- Data Visualization
- Dashboard Design
- KPI Development
- Customer Analytics
- Churn Analysis

---

# 📢 Business Recommendations

Based on the churn analysis, the following actions are recommended:

### 1. Prioritize Critical and High-Risk Customers
Critical and High-risk segments represent a significant portion of customers at risk of churn and account for substantial monthly revenue. Implement proactive retention campaigns targeting these customers before cancellation occurs.

### 2. Promote Long-Term Contracts
Many high-risk customers are associated with month-to-month contracts and shorter tenure periods. Offering discounts or incentives for annual contracts may improve customer retention.

### 3. Review Fiber Optic Customer Experience
A large percentage of customers in the Critical and High-risk segments use Fiber Optic services. Further investigation should be conducted to identify potential service quality, pricing, or support issues affecting these customers.

### 4. Encourage Automatic Payment Methods
Electronic Check is highly represented among high-risk customers. Encouraging customers to switch to automatic payment methods may improve customer commitment and reduce churn.

### 5. Focus on Early Customer Engagement
Customers with lower tenure exhibit higher churn risk. Implement onboarding programs, welcome campaigns, and customer success initiatives during the first months of the customer lifecycle.

### 6. Retain High-Value Customers
Several high-risk customers generate above-average monthly revenue. Prioritizing retention efforts for these customers can significantly reduce revenue loss and protect future revenue streams.

### 7. Monitor Revenue at Risk
Establish regular monitoring of Revenue at Risk and Monthly Revenue Lost KPIs to evaluate the effectiveness of retention strategies and identify emerging churn trends.
