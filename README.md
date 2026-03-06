# Global Layoffs Data Cleaning Project (MySQL)

## Project Overview
This project focuses on cleaning and preparing a global layoffs dataset using MySQL. 
The raw dataset contained inconsistencies, duplicate records, and missing values. 
SQL was used to transform and standardize the data to improve its quality and make it suitable for analysis.

## Dataset
The dataset contains information about company layoffs across different industries and countries.  
It includes details such as company name, industry, location, total layoffs, percentage laid off, and date.

## Data Cleaning Steps
The following cleaning operations were performed:

1. Created a staging table to preserve the original dataset.
2. Removed duplicate records using the `ROW_NUMBER()` window function.
3. Trimmed and standardized company names.
4. Standardized industry values.
5. Converted date fields to proper date format.
6. Handled missing or NULL values.
7. Removed unnecessary or inconsistent data.

## Tools Used
- MySQL
- SQL
- MySQL Workbench
- GitHub

## Repository Structure

mysql-data-cleaning-project
│
├── data
│   ├── layoffs.csv (raw dataset)
│   └── layoffs_cleaned.csv (cleaned dataset)
│
├── sql
│   └── data_cleaning.sql (SQL script used for cleaning)
│
└── README.md

## Skills Demonstrated
- Data Cleaning
- SQL Queries
- Window Functions
- Handling Missing Data
- Data Transformation
- Data Quality Improvement

## Project Outcome
The dataset was successfully cleaned and standardized using MySQL. 
The cleaned dataset (layoffs_cleaned.csv) is now ready for further analysis such as identifying layoffs trends by company, industry, or year.
