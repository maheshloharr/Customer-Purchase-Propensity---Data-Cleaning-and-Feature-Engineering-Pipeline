# 🛒 Customer Purchase Propensity
## Data Cleaning and Feature Engineering Pipeline

## 📌 Project Overview

This project focuses on building a complete **Data Cleaning, Data Preprocessing, Exploratory Data Analysis (EDA), and Feature Engineering pipeline** for customer purchase data.

The objective is to prepare raw customer and transaction data for a future Machine Learning model that can predict whether a customer will make a purchase.

This project focuses on **Data Preprocessing and Feature Engineering only**. No Machine Learning model is trained in this project.

---

## 🎯 Project Objective

The main objective of this project is to:

- Load data from multiple sources.
- Clean and preprocess raw data.
- Perform Exploratory Data Analysis (EDA).
- Handle missing values using different techniques.
- Detect and handle outliers.
- Process Date and Time variables.
- Encode categorical variables.
- Apply feature scaling techniques.
- Create new features from existing data.
- Prepare a final dataset for Machine Learning.

---

## 🤖 Machine Learning Problem

The dataset can be framed as a **Binary Classification problem**.

### Target Variable: `purchased`

| Purchased | Meaning |
|---|---|
| 1 | Customer made a purchase |
| 0 | Customer did not make a purchase |

The future Machine Learning model can use customer demographics, transaction history, product information, and engineered features to predict customer purchase behavior.

---

# 📂 Data Sources

The project uses data from multiple sources:

### 1️⃣ CSV File

`customers.csv`

Contains customer demographic information and customer IDs.

### 2️⃣ JSON File

`transactions.json`

Contains customer transaction records.

### 3️⃣ MySQL Database

`products` table

Contains product-related information such as:

- Product ID
- Product Name
- Category
- Price
- Stock

### 4️⃣ API

DummyJSON Users API:

`https://dummyjson.com/users`

Provides additional user-related information.

---

# 🔄 Project Workflow

```text
Data Collection
      ↓
Data Understanding
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
Missing Value Handling
      ↓
Outlier Detection
      ↓
Date Feature Engineering
      ↓
Categorical Encoding
      ↓
Feature Scaling
      ↓
Feature Construction
      ↓
Final Processed Dataset
