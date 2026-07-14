# 🐍 Telecom Customer Churn Analysis (Python)

Welcome to my first Python data analytics repository! This project focuses on analyzing customer behavior data to understand the root causes of customer attrition (churn) in a telecom company.

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Environment:** Google Colab
* **Libraries:** Pandas (Data Cleaning), Seaborn & Matplotlib (Data Visualization)

## 🧼 Data Preprocessing Steps
* Detected hidden empty strings in the `TotalCharges` column.
* Converted blank entries into `NaN` values and removed them using `.dropna()` to prevent data skewness.
* Formatted data types to prepare the dataset for Exploratory Data Analysis (EDA).

## 📊 Key Insights Found
1. **Contract Type:** Month-to-month contract customers have the highest churn rate compared to long-term contracts.
2. **Payment Method:** Electronic Check users are highly likely to leave the service.
3. **Tenure:** New customers (low tenure) show early signs of churn, indicating a need for better onboarding engagement.

---
*Note: This entire project was coded and executed on a mobile device via Google Colab, proving that logic and persistence overcome hardware limitations.*
