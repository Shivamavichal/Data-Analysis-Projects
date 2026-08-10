# customer_behavior_ananlysis
data_analysis project showcasing customer behavior analysis using python , SQL and Power Bi

# 📊 Data Analysis Project

## Overview

This project demonstrates an end-to-end data analysis workflow, starting from raw data and ending with an interactive dashboard and business report. The project includes data loading, cleaning, exploratory data analysis (EDA), SQL-based analysis, Power BI dashboard creation, and presentation of key insights.

The objective is to transform raw data into meaningful insights that support better decision-making.

---

## Dataset

- **Dataset:** customer_shopping_behavior.csv
- **Format:** CSV
- **Source:** Public Dataset
- **Records:** 3900
- **Features:** - Customer demographics (Age, Gender, Location, Subscription Status) - Purchase details (Item Purchased,Category, Purchase Amount, Season, Size, Color) - Shopping behavior (Discount Applied, Promo Code Used,Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type) - Missing Data: 37 values in Review Rating column 

## Project Workflow

### 1. Data Loading
- Imported the dataset using Python.
- Explored dataset structure.
- Checked data types and dimensions.

### 2. Data Cleaning
- Removed duplicate records.
- Handled missing values.
- Corrected inconsistent data.
- Standardized column names.
- Converted data into appropriate data types.

### 3. Exploratory Data Analysis (EDA)
- Generated summary statistics.
- Analyzed distributions.
- Identified trends and patterns.
- Created visualizations using Python.

### 4. SQL Analysis (MySQL)
- Imported cleaned dataset into MySQL Server.
- Wrote SQL queries to answer business questions.
- Used:
  - SELECT
  - WHERE
  - GROUP BY
  - ORDER BY
  - HAVING
  - Aggregate Functions
  - JOINs (if applicable)

### 5. Power BI Dashboard
Created an interactive dashboard including:
- KPI Cards
- Sales/Performance Overview
- Category Analysis
- Trend Analysis
- Filters and Slicers
- Charts and Graphs

### 6. Report Creation
Prepared a report summarizing:
- Key findings
- Business insights
- Recommendations

### 7. Presentation
Created a professional presentation using **Gamma** to communicate project objectives, methodology, insights, and conclusions.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- MySQL Server
- SQL
- Power BI
- Gamma

## Dashboard

The Power BI dashboard provides:

- Executive KPI Summary
- Interactive Filters
- Trend Analysis
- Category Comparison
- Performance Insights
- Business Metrics

## Results

The project successfully:

- Cleaned and prepared raw data.
- Performed exploratory data analysis.
- Extracted insights using SQL.
- Built an interactive Power BI dashboard.
- Generated a business report.
- Presented findings in a professional presentation.

The analysis helps stakeholders understand data trends and supports data-driven decision-making.-

## Project Structure

```
Data-Analysis-Project/
│
├── Dataset/
│   └── data.csv
│
├── Python/
│   └── Data_Analysis.ipynb
│
├── SQL/
│   └── Queries.sql
│
├── PowerBI/
│   └── Dashboard.pbix
│
├── Report/
│   └── Project_Report.pdf
│
├── Presentation/
│   └── Gamma_Presentation.pdf
│
└── README.md
```

---

## How to Run

### Clone the repository

```bash
git clone https://github.com/your-username/your-repository.git
```

### Install dependencies

```bash
pip install pandas numpy matplotlib jupyter
```

### Run the notebook

Open Jupyter Notebook and execute:

```
Python/Data_Analysis.ipynb
```

### Run SQL Queries

- Open MySQL Server.
- Import the cleaned dataset.
- Execute the queries from:

```
SQL/Queries.sql
```

### Open Dashboard

Launch the following file in Power BI Desktop:

```
PowerBI/Dashboard.pbix
```

---

## Key Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- SQL Query Writing
- Business Intelligence
- Dashboard Development
- Report Writing
- Data Storytelling

---

## Future Improvements

- Automate the data pipeline.
- Integrate live database connectivity.
- Deploy the dashboard online.
- Add predictive analytics using Machine Learning.

---

## Author
Shivam Avichal


