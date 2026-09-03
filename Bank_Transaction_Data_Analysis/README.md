# 🏦 Bank Transaction Analysis | Python & Power BI

## 📌 Project Overview

This project focuses on analyzing bank transaction data to uncover meaningful insights into customer behavior, transaction activity, account balances, demographics, and locations.

The project follows an end-to-end data analytics workflow:

**Data Cleaning → Data Preparation → Exploratory Data Analysis → Visualization → Power BI Dashboard**

The dataset was cleaned and prepared using **Google Sheets with Gemini AI assistance**, followed by analysis and visualization using **Python** and **Power BI**.

---

## 📂 Dataset Information

The dataset contains both **customer-level and transaction-level information**.

The final processed dataset contains:

- **30,374 rows**
- **16 columns**

### 👤 Customer Information

The dataset contains customer-related information such as:

- `CustomerID` – Unique identifier for each customer
- `CustomerDOB` – Customer date of birth
- `CustGender` – Customer gender
- `CustLocation` – Customer location
- `CustAccountBalance` – Customer account balance

### 💳 Transaction Information

The dataset contains transaction-related information such as:

- `TransactionID` – Unique identifier for each transaction
- `TransactionDate` – Date of the transaction
- `TransactionTime` – Time of the transaction
- `TransactionAmount (INR)` – Transaction amount in Indian Rupees

### 🔧 Analytical Features

Additional features were created during data preparation to support analysis:

- `Age` – Customer age calculated from date of birth
- `Age-Groups` – Customers categorized into different age groups
- `TransactionYear` – Year of transaction
- `TransactionMonth` – Month number of transaction
- `TransactionMonthName` – Name of transaction month
- `DayOfWeek` – Day of the week of the transaction
- `Day` – Day of the month of the transaction

### 📊 Dataset Summary

| Metric | Value |
|---|---:|
| Rows | 30,374 |
| Columns | 16 |
| Customer Information | Yes |
| Transaction Information | Yes |
| Location Information | Yes |
| Account Balance | Yes |
| Transaction Amount | INR |

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Analyze overall transaction activity
- Understand customer demographics
- Compare transaction behavior across different age groups
- Analyze transaction behavior by gender
- Identify locations with high transaction activity
- Analyze transaction amounts and account balances
- Explore patterns and relationships within the data
- Build an interactive Power BI dashboard
- Generate business-oriented insights from transaction data

---

## 🛠️ Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| **Google Sheets** | Data cleaning and preparation |
| **Gemini AI** | AI-assisted data cleaning and productivity |
| **Python** | Data analysis and exploratory data analysis |
| **Pandas** | Data manipulation and analysis |
| **NumPy** | Numerical operations |
| **Matplotlib** | Data visualization |
| **Power BI** | Interactive dashboard development |
| **DAX** | Measures and calculations in Power BI |

---

## 🔄 Project Workflow

### 1. Data Cleaning

The raw dataset was inspected and cleaned before performing analysis.

The cleaning process included:

- Identifying and handling missing values
- Checking for duplicate records
- Standardizing categorical values
- Handling missing customer information
- Handling missing account balance values
- Checking and correcting data types
- Validating transaction-related fields
- Preparing the dataset for analysis

**Gemini AI** was used as an AI-assisted tool during the Google Sheets cleaning process to improve efficiency and speed while performing repetitive data-cleaning tasks.

---

### 2. Data Preparation

After cleaning, additional analytical features were created to support deeper analysis.

The prepared dataset includes:

- Customer age
- Age groups
- Transaction year
- Transaction month
- Transaction month name
- Day of week
- Day of month

These features make it possible to analyze transaction behavior across demographic and time-based dimensions.

---

### 3. Exploratory Data Analysis

Python was used to perform Exploratory Data Analysis (EDA) on the processed dataset.

The analysis focused on:

- Transaction amount distribution
- Transaction activity by gender
- Transaction activity by age group
- Average transaction amount by age group
- Transaction activity by location
- Transaction activity by day of week
- Relationship between account balance and transaction amount

**Pandas** was used for data manipulation and analysis, while **Matplotlib** was used to create visualizations.

---

# 📊 Power BI Dashboard

The processed dataset was imported into **Power BI** to create an interactive banking transaction dashboard.

## 📌 Dashboard KPIs

The dashboard includes the following key performance indicators:

- **Total Transactions**
- **Total Transaction Amount**
- **Average Transaction Amount**
- **Average Account Balance**
- **Unique Customers**

## 📈 Dashboard Visualizations

The dashboard includes:

- **Transaction Volume by Age Group**
- **Transaction Mix by Gender**
- **Top 10 Locations by Transaction Volume**
- **Average Transaction Value by Age Group**

## 🎛️ Interactive Filters

The dashboard allows users to dynamically filter the analysis using:

- Gender
- Age Group
- Customer Location
- Transaction Year
- Transaction Month

The filters interact with the dashboard visuals, allowing users to explore different customer and transaction segments.
