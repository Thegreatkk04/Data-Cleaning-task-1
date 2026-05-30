# Data-Cleaning-task-1
about preprocessing of data
# Data Cleaning and Preprocessing - Task 1

## Overview

The objective of this task  was to clean and preprocess a raw dataset by handling missing values, removing duplicates, standardizing formats, and preparing the data for further analysis.

## Dataset

**Dataset Name:**-market_campaign 

**Source:** Kaggle

**Original Dataset File:** market_campaign.csv

**Cleaned Dataset File:** cleaned_market_campaign.csv

## Objectives

* Identify and handle missing values.
* Remove duplicate records.
* Standardize text and categorical values.
* Convert date columns into a consistent format.
* Rename column headers for better readability.
* Correct inappropriate data types.
* Prepare the dataset for analysis and visualization.

## Data Cleaning Steps Performed

### 1. Missing Value Treatment

* Checked missing values using `isnull().sum()`.
* Filled missing values where appropriate.
* Removed rows/columns with excessive missing data.

### 2. Duplicate Removal

* Identified duplicate records.
* Removed duplicates using Pandas `drop_duplicates()`.

### 3. Column Name Standardization

* Converted column names to lowercase.
* Replaced spaces with underscores.
* Removed unnecessary special characters.

### 4. Data Type Correction

* Converted numeric columns to appropriate numeric types.
* Converted date columns to datetime format.

### 5. Text Standardization

* Standardized categorical values.
* Fixed inconsistent spellings and capitalization.

### 6. Data Validation

* Verified dataset integrity after cleaning.
* Checked for remaining null values and duplicates.

## Technologies Used

* Python
* Pandas
* Jupyter Notebook

## Files Included

| File                                | Description            |
| -------------------                 | ---------------------- |
| market_campaign.csv                 | Original raw dataset   |
| cleaned_market_campaign.csv         | Final cleaned dataset  |
| Data-analyst-internship-task1.ipynb | Data cleaning notebook |
| README.md                           | Project documentation  |

## Results

### Before Cleaning

* Missing values present
* Duplicate records present
* Inconsistent formatting
* Mixed data types

### After Cleaning

* Missing values handled
* Duplicate records removed
* Standardized formatting
* Correct data types assigned
* Dataset ready for analysis

## Key Learnings

* Handling missing values using Pandas.
* Removing duplicate records.
* Standardizing and validating data.
* Performing real-world data preprocessing.
* Preparing data for analysis and machine learning workflows.

## Author

Kapil Kumar
