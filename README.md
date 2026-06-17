# Loan Default Analysis

## Project Overview

This project analyzes loan applicant and loan performance data to identify factors associated with loan defaults. The objective is to uncover high-risk borrower characteristics, understand default patterns, and build an interactive Power BI dashboard for business decision-making.

---

## Business Problem

Financial institutions face significant losses due to loan defaults. Identifying high-risk borrowers and understanding the factors contributing to default can help lenders improve underwriting decisions, reduce risk exposure, and optimize loan approval strategies.

---

## Dataset Information

* Total Records: 10,000 loans
* Target Variable: `loan_default`
* Data Type: Lending and borrower information
* Features Included:

  * Borrower characteristics
  * Credit history
  * Loan attributes
  * Repayment behavior

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Power BI
* DAX

---

## Project Workflow

### 1. Data Understanding

Performed initial data exploration to understand:

* Dataset structure
* Data types
* Missing values
* Variable distributions

**Notebook:**

* `data_understanding.ipynb`

---

### 2. Data Cleaning

Data preprocessing included:

* Handling missing values
* Removing inconsistencies
* Feature preparation
* Creating the target variable `loan_default`

**Notebook:**

* `data_cleaning.ipynb`

---

### 3. Exploratory Data Analysis (EDA)

Conducted detailed analysis of borrower and loan characteristics, including:

* Loan Grade Analysis
* Loan Purpose Analysis
* Homeownership Analysis
* Loan Term Analysis
* State-Level Analysis
* Correlation Analysis

**Notebook:**

* `eda.ipynb`

---

## Key Findings

### Loan Grade Risk

* Grade F loans had the highest default rate (**12.07%**).
* Grade A loans had the lowest default rate (**0.77%**).
* Default risk increased as loan grade worsened.

### Loan Purpose Risk

* House loans showed the highest default rate (**6.62%**).
* Medical loans showed elevated default rates (**3.70%**).
* Credit card loans had relatively low default rates (**1.07%**).

### Loan Term Risk

* 60-month loans had a higher default rate (**2.31%**).
* 36-month loans had a lower default rate (**1.55%**).

### Interest Rate Analysis

* Borrowers who defaulted generally carried higher interest rates.
* Higher interest rates were associated with increased default risk.

### Geographic Analysis

* Among states with meaningful loan volume, North Carolina, New York, and Nevada showed relatively higher default rates.

---

## Business Recommendations

* Apply stricter underwriting for Grade E, F, and G borrowers.
* Monitor House and Medical loan categories more closely.
* Implement additional risk checks for long-term (60-month) loans.
* Review lending strategies in higher-risk geographic regions.
* Combine loan grade and interest rate information to improve risk assessment.

---

## Power BI Dashboard

### Dashboard Page 1

KPIs:

* Total Loans
* Default Rate
* Average Interest Rate
* Average Loan Amount

Visuals:

* Default Rate by Grade
* Default Rate by Loan Purpose

### Dashboard Page 2

Visuals:

* Default Rate by Loan Term
* Default Rate by State

---


## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Data Visualization
* Business Insight Generation
* Power BI Dashboard Development
* DAX Measures
* Risk Analysis

---

## Project Files

* `data_understanding.ipynb`
* `data_cleaning.ipynb`
* `eda.ipynb`
* `cleaned_loan_data.csv`
* `Loan_Default_Dashboard.pbix`

---

## Author

**Mohini Patil**

Aspiring Data Analyst | Python | SQL | Power BI | Data Visualization
