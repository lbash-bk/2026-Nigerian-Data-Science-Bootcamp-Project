# Data Science Nigeria Bootcamp 2026 — Sales Performance Analysis

A practical sales data analysis project completed as part of the Data Science Nigeria Bootcamp 2026, using Python, Pandas, and Microsoft Power BI.

## Project Overview

This project involved analysing sales transaction data as part of the Data Science Nigeria Bootcamp 2026.

The task focused on preparing raw sales data, addressing data quality issues, validating sales calculations, conducting exploratory analysis, and developing a Power BI dashboard to communicate relevant sales performance information.

The project was completed within two days, demonstrating practical data preparation, analytical problem-solving, and dashboard development skills.

## Project Objectives

- Inspect and understand the supplied sales dataset.
- Identify and handle duplicate transaction records.
- Investigate and treat missing values.
- Validate sales and revenue information.
- Prepare a clean dataset for analysis.
- Explore sales performance using Python.
- Develop a Power BI dashboard to communicate relevant KPIs and findings.

## Tools and Technologies

| Tool | Purpose |
|---|---|
| Python | Data preparation and analysis |
| Pandas | Data cleaning and manipulation |
| NumPy | Numerical operations |
| Jupyter Notebook | Analysis workflow |
| Microsoft Power BI | Dashboard development |

## Dataset Description

The original dataset contained:

- **432 rows**
- **16 columns**

The dataset included sales transaction information, including transaction identifiers and product cost information.

The dataset was inspected to understand its structure, identify data quality issues, and determine the preparation required before analysis.

## Data Cleaning and Preparation

Data cleaning was performed using Python and Pandas.

The major steps included:

### 1. Initial Data Inspection

- Loaded the supplied sales dataset.
- Examined its dimensions and column structure.
- Inspected data types and missing values.
- Investigated duplicate transaction records.

### 2. Duplicate Transaction Handling

Duplicate TransactionID records were identified and removed.

- Original records: 432
- Duplicate transaction records removed: 12
- Remaining records: 420

### 3. Missing Cost Per Unit Treatment

The `Cost_Per_Unit_NGN` column contained 31 missing values.

These missing values were handled using product-based imputation, using the product information to determine appropriate replacement values.

### 4. Revenue Validation

Revenue values were examined and validated against the available transaction information.

The validation process identified 398 out of 420 records with matching revenue calculations.

This step helped assess the consistency of the sales data before proceeding with analysis.

### 5. Final Data Preparation

The cleaned dataset was prepared for exploratory analysis and Power BI dashboard development.

The final working dataset contained 420 records and 20 columns after the preparation and feature-engineering steps.

## Exploratory Data Analysis

The cleaned sales dataset was used for exploratory analysis to examine the available sales information and prepare relevant metrics for dashboard presentation.

The analysis focused on understanding the dataset, examining sales-related variables, and preparing the information needed to communicate performance through Power BI.

## Power BI Dashboard

Microsoft Power BI was used to develop a sales performance dashboard based on the prepared dataset.

The dashboard was intended to communicate relevant sales KPIs and analytical findings in an interactive visual format.

**Dashboard screenshot:**

Add your actual dashboard screenshot to a `screenshots` folder and reference it below.

![Data Science Nigeria Bootcamp 2026 Sales Dashboard](screenshots/dsn_bootcamp_sales_dashboard.png)

## Project Highlights

- Completed as part of the Data Science Nigeria Bootcamp 2026.
- Completed within two days.
- Worked with an initial dataset of 432 records and 16 columns.
- Identified and removed 12 duplicate transaction records.
- Handled 31 missing product cost values using product-based imputation.
- Validated revenue calculations, with 398 out of 420 records matching.
- Prepared a cleaned dataset containing 420 records and 20 columns.
- Developed a Power BI dashboard to communicate sales performance information.

## Conclusion

This project provided practical experience in preparing and analysing sales transaction data under a structured bootcamp assignment.

The work involved data inspection, duplicate handling, missing-value treatment, revenue validation, exploratory analysis, and Power BI dashboard development.

Completing the assignment within two days strengthened practical skills in Python, Pandas, data quality assessment, analytical problem-solving, and data visualization.

The project also demonstrated the importance of validating data before using it to generate business insights.

---

**Programme:** Data Science Nigeria Bootcamp 2026

**Project Category:** Sales Data Analysis

**Original Dataset:** 432 rows × 16 columns

**Final Prepared Dataset:** 420 rows × 20 columns

**Tools:** Python, Pandas, NumPy, Jupyter Notebook, Microsoft Power BI

**Deliverable:** Sales Performance Dashboard
