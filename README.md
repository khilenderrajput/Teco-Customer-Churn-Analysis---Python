# 📊 Customer Churn Analysis

## 📌 Project Overview

Customer churn is an important business problem for subscription-based and service-oriented companies. Understanding why customers leave and identifying the customer segments associated with higher churn can help businesses improve customer retention and make better data-driven decisions.

This project performs an end-to-end **Customer Churn Exploratory Data Analysis (EDA)** using Python. The analysis focuses on understanding customer characteristics, service usage, contract behavior, tenure, payment methods, and other factors associated with customer churn.

The project uses **Pandas, NumPy, Seaborn, and Matplotlib** for data cleaning, analysis, visualization, and insight generation.

---

## 🎯 Project Objective

The main objectives of this project are:

- Analyze the overall customer churn distribution.
- Understand the characteristics of churned and retained customers.
- Explore demographic differences in customer behavior.
- Analyze the relationship between customer tenure and churn.
- Examine churn patterns across different contract types.
- Analyze internet service categories and their churn patterns.
- Study the impact of additional services on customer behavior.
- Analyze customer churn across different payment methods.
- Create clear and informative visualizations.
- Identify customer segments associated with higher churn.
- Generate meaningful business-oriented insights from the data.

---

## 📂 Dataset Overview

The dataset contains customer-level information related to:

- Customer demographics
- Account information
- Service subscriptions
- Contract details
- Payment methods
- Tenure
- Monthly charges
- Total charges
- Churn status

The dataset contains **7,043 customer records and 21 attributes**.

### Important Dataset Columns

| Column | Description |
|---|---|
| `customerID` | Unique customer identifier |
| `gender` | Customer gender |
| `SeniorCitizen` | Indicates whether the customer is a senior citizen |
| `Partner` | Whether the customer has a partner |
| `Dependents` | Whether the customer has dependents |
| `tenure` | Number of months the customer has stayed with the company |
| `PhoneService` | Whether phone service is subscribed |
| `MultipleLines` | Multiple-line phone service status |
| `InternetService` | Type of internet service |
| `OnlineSecurity` | Online security service status |
| `OnlineBackup` | Online backup service status |
| `DeviceProtection` | Device protection service status |
| `TechSupport` | Technical support service status |
| `StreamingTV` | Streaming TV service status |
| `StreamingMovies` | Streaming movies service status |
| `Contract` | Customer contract type |
| `PaperlessBilling` | Whether paperless billing is enabled |
| `PaymentMethod` | Customer payment method |
| `MonthlyCharges` | Monthly amount charged |
| `TotalCharges` | Total amount charged |
| `Churn` | Whether the customer left the service |

---

# 🛠️ Technologies Used

The project was developed using the following technologies:

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Development Environment
- Jupyter Notebook

### Version Control
- Git
- GitHub

---

# 🔄 Project Workflow

The project follows a complete exploratory data analysis workflow:

```text
Raw Dataset
     ↓
Data Loading
     ↓
Data Inspection
     ↓
Data Cleaning
     ↓
Data Type Conversion
     ↓
Missing Value Analysis
     ↓
Duplicate Check
     ↓
Exploratory Data Analysis
     ↓
Univariate Analysis
     ↓
Categorical Analysis
     ↓
Churn Analysis
     ↓
Data Visualization
     ↓
Pattern Identification
     ↓
Business Insights
