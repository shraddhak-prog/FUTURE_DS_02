# FUTURE_DS_02

# 📊 Customer Churn Analysis Dashboard (Power BI and Jupyter Notebook)

## 📌 Project Overview

This project analyzes customer data from a subscription-based business to identify **churn patterns**, **retention drivers**, and **customer lifetime trends**.
The dashboard helps businesses understand why customers leave and how to improve retention.

## 🎯 Objectives

* Identify churn patterns and high-risk customers
* Analyze factors influencing customer retention
* Measure customer lifetime value (CLV)
* Discover trends in revenue and tenure

## 📂 Dataset

The dataset contains customer information such as:

* Customer ID
* Tenure (months)
* Monthly Charges
* Total Charges
* Contract Type
* Payment Method
* Churn (Yes/No)

## 🛠 Tools & Technologies

* **Power BI** – Dashboard creation & data visualization
* **DAX** – Measures & calculated columns
* **Excel/CSV** – Data source


## 📊 Key Metrics (KPIs)

| Metric          | Description                      |
| --------------- | -------------------------------- |
| Total Customers | Total number of customers        |
| Churn Rate      | Percentage of customers who left |
| Average Tenure  | Average duration customers stay  |
| Average CLV     | Average customer lifetime value  |


## 🧮 DAX Calculations

### 🔹 Churn Flag (Column)
Churn Flag = IF('Customer_retention'[Churn] = "Yes", 1, 0)


### 🔹 Customer Lifetime Value
CLV = 'Customer_retention'[MonthlyCharges] * 'Customer_retention'[Tenure]


## 📈 Dashboard Visuals

### 🔹 KPI Cards

* Total Customers
* Churn Rate
* Average Tenure
* Average CLV

### 🔹 Charts

| Visual                   | Purpose              | X-Axis          | Y-Axis         |
| ------------------------ | -------------------- | --------------- | -------------- |
| Churn by Tenure          | Identify early churn | Tenure          | Churn Count    |
| Churn by Contract        | Retention by plan    | Contract Type   | Churn Rate     |
| Monthly Charges vs Churn | Price sensitivity    | Monthly Charges | Churn Rate     |
| CLV Distribution         | Customer value       | CLV Range       | Customer Count |
| Payment Method vs Churn  | Risky payment types  | Payment Method  | Churn Count    |

## 🔍 Key Insights

* Customers with shorter tenure are more likely to churn
* Month-to-month contracts show higher churn rates
* Higher monthly charges may increase churn risk
* Certain payment methods correlate with higher churn


## 👩‍💻 Author
**Shraddha Kale**
**Data Science & Analytics Intern Future Interns**
