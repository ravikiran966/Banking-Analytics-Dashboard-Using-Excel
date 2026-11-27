# 🏦 Banking Analytics Dashboard Using Excel

## 📌 Project Overview

The Banking Analytics Dashboard is a data analysis project developed using Microsoft Excel to analyze customer accounts and banking transactions.

The dashboard provides insights into customer account distribution, account balances, transaction activities, payment methods, KYC verification, and flagged transactions.

## 🎯 Project Objectives

- Analyze bank accounts by account type and city.
- Analyze total account balances.
- Monitor customer KYC verification status.
- Analyze transaction status and payment methods.
- Compare debit and credit transactions.
- Identify monthly transaction trends.
- Analyze flagged transactions.

## 📂 Dataset Description

This project uses two datasets:

### 1. Bank Accounts Dataset
File: `bank_accounts.csv`

Contains 1,000 account records.

| Column | Description |
|---|---|
| account_id | Unique account ID |
| customer_name | Customer name |
| age | Customer age |
| city | Customer city |
| branch_code | Branch code |
| account_type | Account type |
| kyc_status | KYC verification status |
| balance_inr | Account balance |
| account_status | Account status |
| opened_at | Account opening timestamp |

### 2. Bank Transactions Dataset
File: `bank_transactions.csv`

Contains 3,453 transaction records.

| Column | Description |
|---|---|
| txn_id | Transaction ID |
| account_id | Customer account ID |
| txn_type | Debit or Credit |
| category | Transaction category |
| mode | Payment mode |
| amount_inr | Transaction amount |
| status | Transaction status |
| is_flagged | Flagged transaction indicator |
| txn_ts | Transaction timestamp |

## 🛠️ Tools & Technologies

- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Excel Formulas
- Slicers
- Data Cleaning
- Data Visualization
- Dashboard Development

## 📊 Dashboard Features

### 1. KPI Analysis
- Total Bank Accounts
- Total Transactions
- Total Account Balance
- Flagged Transactions

### 2. Account Analysis
- Bank Accounts by Account Type
- City-Wise Account Distribution
- Customer KYC Verification Status
- Total Account Balance by City

### 3. Transaction Analysis
- Transaction Status Distribution
- Monthly Transaction Trends
- Transaction Volume by Payment Mode
  



## 📈 Key Dataset Statistics

| Metric | Value |
|---|---:|
| Total Accounts | 1,000 |
| Total Transactions | 3,453 |
| Successful Transactions | 3,264 |
| Flagged Transactions | 167 |
| Flagged Transaction Percentage | 4.84% |

## 💡 Key Insights

- Analyzed customer account distribution across different cities.
- Compared account balances across locations.
- Evaluated KYC verification status.
- Examined successful, failed, and pending transactions.
- Identified popular payment methods.
- Analyzed monthly transaction trends.
- Identified transactions requiring potential risk review.

## 📁 Project Structure

```text
Banking-Analytics-Dashboard/
│
├── Dataset/
│   ├── bank_accounts.csv
│   └── bank_transactions.csv
│
├── Dashboard/
│   └── Banking_Data_Analysis_Dashboard.xlsx
│
└── README.md


