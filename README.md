📊 Data Cleaning in Excel

A complete data cleaning project performed in Microsoft Excel to improve data quality by handling missing values, checking duplicates, correcting formats, and validating dataset consistency.

📁 Project Overview

This project focuses on cleaning and preparing a raw sales/order dataset for analysis using Excel.

The dataset contained:
1. Missing values
2. Data formatting inconsistencies
3. Potential duplicate records
4. Validation requirements for numerical accuracy

The goal was to transform raw data into a structured and analysis-ready dataset.

🎯 Objectives
1. Identify and handle missing/null values
2. Detect and remove duplicate records
3. Correct inconsistent data formats
4. Standardize text and numerical fields
5. Validate calculated fields for accuracy

🛠 Tools Used
1. Excel Formulas
2. Conditional Formatting
3.Data Validation
4. Remove Duplicates Tool
5. Filter & Sorting Functions

📂 Dataset Information

The dataset contains approximately:

1,200 rows
Customer orders and transaction records
Main Columns:
Order ID
Customer ID
Product
Quantity
Unit Price
Total Price
Payment Method
Coupon Code
Order Status
Referral Source
Date

🧹 Data Cleaning Process
1️⃣ Handling Missing Values
Problem:
The CouponCode column contained missing values.

Solution:
Blank values were replaced with:
No Coupon
Formula Used:
=IF(L2="", "No Coupon", L2)

2️⃣ Removing Duplicate Records
Process:
Used Excel’s Remove Duplicates feature
Checked all columns for repeated entries
Result:

✅ No duplicate records were found.

3️⃣ Correcting Data Formats
Date Formatting
The Date column was standardized into a consistent format.
Numerical Formatting

Applied:
Currency formatting for price columns
Number formatting for quantity fields
Text Standardization

Verified consistency in:
Payment methods
Order status
Referral sources

4️⃣ Data Validation

Validated that:

TotalPrice = Quantity × UnitPrice
Formula Used:
=E2*F2=N2

This ensured pricing accuracy across the dataset.

📈 Results

After cleaning:

Missing values were handled
Dataset consistency improved
Data became analysis-ready
Formatting issues were corrected
Validation checks confirmed accuracy

🚀 Key Learnings

Through this project:

Learned practical Excel data cleaning techniques
Improved understanding of data preprocessing
Applied validation and quality assurance methods
Developed structured workflows for preparing datasets

📌 Future Improvements

Possible future enhancements:

Automating cleaning using Power Query
Building dashboards from cleaned data
Performing exploratory data analysis (EDA)
Creating visual reports using Pivot Tables & Charts

👨‍💻 Author
Muhammad Ali Imran
BS Business Analytics — FAST NUCES Islamabad

⭐ Repository Purpose
This repository demonstrates practical data cleaning skills in Excel for:

Data Analytics
Business Intelligence
Data Preprocessing
Academic & Portfolio Projects
