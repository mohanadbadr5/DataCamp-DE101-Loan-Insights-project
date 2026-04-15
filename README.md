# DataCamp-DE101-Loan-Insights-project

<img width="836" height="390" alt="lending_schema" src="https://github.com/user-attachments/assets/f4b89158-a05b-4b4d-a032-6c543633f4a5" />

# Loan Insights: Data Cleaning and Analysis (SQL)

### Project Overview
This project focuses on cleaning a complex loan database and performing analytical joins using **PostgreSQL**. The goal was to transform messy categorical data and handle missing values to generate insights into loan distributions and interest rates.

### Key Tasks Accomplished:
*   **Data Cleaning:** Fixed inconsistent date formats (e.g., "July 2022") and corrected spelling errors in categorical fields (e.g., "emplouyed").
*   **Imputation:** Handled missing values in repayment channels using conditional logic (`CASE` statements) based on transaction amounts.
*   **Relational Joins:** Merged multiple tables (`client`, `loan`, `contract`) to filter high-value US-based loans.
*   **Aggregation:** Calculated average interest rates across different loan types and geographic regions.

### Technologies Used
*   PostgreSQL
*   DataLab / DataCamp Environment
