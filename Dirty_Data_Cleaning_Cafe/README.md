# Cafe Sales Data Cleaning Project 

## Overview

This project focuses on cleaning and preparing a raw cafe sales dataset for analysis using Python and Pandas. The dataset contained inconsistent values, missing information, incorrect data types, and formatting issues.

The objective was to transform raw transactional data into a clean, analysis-ready dataset through data cleaning, validation, and transformation techniques.
Dataset Source

## Dataset

The original dataset was obtained from Kaggle and contained raw cafe sales data requiring preparation before analysis.

The dataset contained missing values, unknown entries, inconsistent formatting, and inconsistencies that required cleaning and transformation before analysis.

Both the raw and cleaned datasets are provided:
* Raw dataset: Original unprocessed data
* Cleaned dataset: Final analysis-ready dataset after applying Python cleaning techniques

The original dataset was obtained from Kaggle:
https://www.kaggle.com/datasets/ahmedmohamed2003/cafe-sales-dirty-data-for-cleaning-training



## Tools Used

* Python
* Pandas
* NumPy
* Jupyter Notebook

## Data Cleaning Process

The following steps were performed:

### Data Exploration

* Imported the dataset into Pandas.
* Reviewed:
  - Dataset structure
  - Column data types
  - Summary statistics
  - Missing values
  - Data inconsistencies

### Data Standardisation

* Standardised column names by:
  - Removing unnecessary spaces
  - Converting column names into a consistent format

* Cleaned categorical columns:
  - Standardised item names
  - Corrected inconsistent values
  - Replaced invalid entries such as errors with appropriate values

### Handling Missing Values

* Investigated missing values across columns.
* Columns with excessive unknown values and limited analytical usefulness, such as payment method and location, were removed.
* Remaining missing values were handled based on the context of each column.


### Data Type Correction

* Converted numerical columns into appropriate numeric formats.
* Removed unwanted characters using string cleaning techniques.
* Converted date columns into proper datetime format.


### Data Validation & Data Reconstruction

Data quality checks were performed to ensure the cleaned dataset was accurate:

* Product pricing was validated against expected values.
* Product information was corrected using price-based mapping.
* Missing values were reconstructed where possible:
 - Total spending was calculated using:
    - Quantity × Unit Price
 - Missing quantities were calculated using:
    - Total Spending ÷ Unit Price
   
Validation checks were performed throughout the process to confirm the accuracy of the transformations.


### Final Output

The cleaned dataset was exported and can be used for future analysis and visualisation.
