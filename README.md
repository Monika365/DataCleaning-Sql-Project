# Data Cleaning & EDA in SQL
## Project Overview
This repository contains two SQL scripts designed for data cleaning and exploratory data analysis (EDA) on a raw dataset. The scripts are structured to help data analysts transform messy source data into actionable insights using pure SQL methods.
- **Data_Cleaning.sql:** Performs step-by-step data cleaning operations (removing duplicates, handling missing values, standardizing fields, etc.)
- **EDA.sql:** Provides exploratory data analysis on the cleaned dataset with key summary statistics and trend identification.
Contents
  - **Data_Cleaning.sql:** Cleans and preprocesses the original data table.
- **EDA.sql:** Applies analytic queries to the preprocessed data to uncover patterns and insights.
How to Use This Repository
1. Clone the repository text git clone https://github.com/Monika365/DataCleaning-Sql-Project.git
2. Review or download the dataset Data should be imported into a SQL-compatible environment (PostgreSQL, MySQL, SQL Server) and named according to your schema conventions. 
3. Run the scripts:
    ** Execute the code in Data_Cleaning.sql first to prepare the raw data.
    ** Proceed with the queries in EDA.sql to perform analytical exploration.

## Data Cleaning Steps
* Remove duplicate records using row number or distinct clauses.
* Fill or drop missing/invalid values.
* Standardize field formats (dates, strings, nulls).
* Optionally, create staging/intermediate tables to manage process flow.
* Finalize clean data for analysis.
Exploratory Data Analysis (EDA)
* Generate basic statistics (count, average, min, max).
* Identify key trends, outliers, and distributions.
* Group and summarize numeric and categorical fields.
* Use SQL GROUP BY, WHERE, and aggregate functions to uncover patterns.
## Prerequisites
* SQL database engine (e.g., PostgreSQL, MySQL, SQL Server).
* Basic familiarity with running SQL scripts.
* A dataset loaded into your database instance.
Results and Next Steps
After running both scripts:
* You'll have a cleaned, trusted dataset ready for reporting.
* Key findings and potential areas for deeper analysis are highlighted via queries.
* Extend or customize the scripts for your own dataset and requirements.

