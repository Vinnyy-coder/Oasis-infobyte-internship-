# Task 3: Data Cleaning

## Project Overview

This project focuses on cleaning and preprocessing the Airbnb NYC 2019 dataset. Data cleaning is a crucial step in data analysis as it improves data quality, consistency, and reliability.

## Dataset

* Dataset Name: AB_NYC_2019
* Source: Airbnb New York City Listings
* Total Records: 48,895
* Total Features: 16

## Objectives

* Identify and handle missing values
* Detect and remove duplicate records
* Standardize text data
* Detect and remove outliers
* Convert data types where necessary
* Create a clean dataset for further analysis

## Steps Performed

### 1. Dataset Loading

Loaded the Airbnb NYC 2019 dataset using Pandas.

### 2. Data Exploration

Analyzed dataset structure, dimensions, and data types.

### 3. Missing Value Handling

Handled missing values in:

* name
* host_name
* last_review
* reviews_per_month

### 4. Duplicate Record Removal

Checked and removed duplicate records from the dataset.

### 5. Data Standardization

Standardized text columns to maintain consistency.

### 6. Outlier Detection and Removal

Used Boxplot visualization and IQR method to detect and remove outliers from the price column.

### 7. Date Conversion

Converted the last_review column into datetime format.

### 8. Export Clean Dataset

Saved the cleaned dataset as a new CSV file.

## Tools and Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Project Files

* AB_NYC_2019.csv
* AB_NYC_2019_Cleaned.csv
* OIBSIP_Task3_DataCleaning.ipynb
* README.md

## Conclusion

The Airbnb NYC 2019 dataset was successfully cleaned by handling missing values, removing duplicate records, standardizing data formats, detecting and removing outliers, and converting data types. The final dataset is ready for further analysis and visualization.
