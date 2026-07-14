# Minor-Project-3
# 🚨 RedFlag – SQL Fraud Detection Engine

## 📌 Project Overview

RedFlag is a real-world SQL analytics project focused on detecting fraudulent financial transactions in a simulated fintech environment. The objective is to identify suspicious user and merchant behavior using only SQL—without Python, Machine Learning, or external analytics tools.

The project analyzes over **200,000 transactions** across six months and detects **12 different fraud patterns** commonly encountered by fintech companies.

---

## 🎯 Problem Statement

A fictional payment aggregator, **PayFast**, processes thousands of digital transactions daily. Hidden within these transactions are multiple fraudulent activities including:

- Card Testing
- Velocity Fraud
- Money Laundering
- Account Takeover
- Refund Abuse
- Merchant Collusion
- Structuring
- Mule Accounts
- Geographic Impossibility
- and more...

The goal is to write optimized SQL queries capable of identifying each fraud pattern accurately.

---

## 📊 Dataset

- **Transactions:** 200,000+
- **Users:** ~14,700
- **Merchants:** 800
- **Time Period:** January 2024 – June 2024

Dataset contains:

- Transaction ID
- User ID
- Merchant ID
- Amount
- Transaction Time
- Transaction Status
- Payment Mode
- City
- Transaction Type

---

## 🔍 Fraud Patterns Detected

### Tier 1
- ✅ Velocity Fraud
- ✅ Round Amount Clustering
- ✅ Card Testing
- ✅ Failed → Successful Transactions
- ✅ Odd Hour Transaction Concentration

### Tier 2
- ✅ Mule Accounts
- ✅ Refund Abuse
- ✅ Merchant Collusion
- ✅ Just Under KYC Threshold (₹9,999)
- ✅ Dormant Then Active Accounts

### Tier 3
- ✅ Velocity Spike Detection
- ✅ Geographic Impossibility Detection

---

## 🛠️ SQL Concepts Used

- SELECT
- WHERE
- GROUP BY
- HAVING
- CASE WHEN
- Aggregate Functions
- DATE(), HOUR(), DATE_FORMAT()
- TIMESTAMPDIFF()
- Joins
- Correlated Subqueries
- EXISTS
- Common Table Expressions (CTEs)
- Window Functions
  - ROW_NUMBER()
  - LAG()
  - OVER()

---

## 💻 Tech Stack

- MySQL 8
- MySQL Workbench
- SQL

---

## 📁 Project Structure

```
RedFlag/
│
├── RedFlag_YourName.sql
├── README.md
└── screenshots/
    ├── pattern1.png
    ├── pattern5.png
    ├── pattern8.png
    └── pattern12.png
```

---

## 📈 Key Learning Outcomes

- Applied SQL to solve real-world fintech problems
- Built fraud detection logic without Machine Learning
- Improved SQL query optimization
- Worked with large-scale transaction datasets
- Practiced CTEs, Window Functions, and Correlated Subqueries
- Understood common fraud detection techniques used in digital payments

---

## 📸 Project Preview

> Add screenshots of your SQL query outputs inside the **screenshots/** folder and embed them here.

Example:

```
![Velocity Fraud](screenshots/pattern1.png)
```

---

## 🚀 Future Improvements

- Interactive Power BI Dashboard
- Fraud Risk Scoring
- Stored Procedures
- Scheduled SQL Reports
- Real-time Fraud Monitoring

---

## 👨‍💻 Author

**Yathish M S**

Aspiring Data Analyst | SQL | Python | Power BI | Data Visualization

Connect with me on LinkedIn.
