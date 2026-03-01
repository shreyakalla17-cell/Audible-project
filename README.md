# Audible-project
This project focuses on cleaning and transforming an audiobook dataset from Audible, a leading digital audiobook and spoken-word entertainment platform owned by Amazon. The objective was to convert raw, inconsistent data into a structured, analysis-ready format using Microsoft Excel Power Query.
Project Overview

This project focuses on cleaning and transforming raw audiobook data from Audible, a digital audiobook and spoken-word entertainment platform owned by Amazon.

The dataset contained inconsistencies, missing values, incorrect data types, and formatting issues that made it unsuitable for analysis. Using Microsoft Excel Power Query, an ETL (Extract, Transform, Load) process was implemented to clean, standardize, and prepare the dataset for reporting and dashboard creation.

🎯 Project Objectives

Clean and standardize raw data

Remove duplicates and handle missing values

Convert incorrect data types (Text → Number/Date/Duration)

Transform unstructured columns into analysis-ready format

Automate repeatable data cleaning steps

🛠 Tool Used

Microsoft Excel – Power Query

Built-in ETL tool

Supports automated, repeatable transformations

Handles large datasets efficiently

📂 Dataset Information

Source: Audible dataset (CSV file)

Key Columns:

Book Title

Author

Rating

Price

Duration

Release Date

❗ Data Issues Identified

Price column contained text and symbols

Ratings stored as text instead of numeric

Duration column in text format (e.g., "5 hrs 30 mins")

Missing / Null values in multiple columns

Duplicate records

Inconsistent date formats

🔄 Data Cleaning Steps

✔ Removed duplicate records
✔ Changed data types (Price → Decimal, Rating → Decimal, Date → Date, Duration → Duration)
✔ Handled missing/null values
✔ Cleaned text using Trim, Clean & Proper Case
✔ Standardized date formats

🔧 Data Transformation

Extracted numeric values from text columns

Converted duration into total minutes

Created calculated columns (e.g., Age from Release)

Renamed columns for reporting clarity

📈 Business Impact

Faster reporting through automation

Reduced manual errors

Improved data accuracy and consistency

Reusable query steps for future datasets

📚 What I Learned

Importance of data quality in analytics

Practical ETL implementation

Automation advantages of Power Query

Real-world data transformation techniques

🚀 Conclusion

Raw datasets often contain inconsistencies that prevent accurate analysis. This project demonstrates how Power Query can efficiently clean and transform messy data into a structured, analysis-ready format, enabling reliable insights and better decision-making.

