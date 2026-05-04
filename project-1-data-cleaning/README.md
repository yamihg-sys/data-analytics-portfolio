# Project 1: Data Cleaning and Transformation

## Overview
This project focuses on cleaning and preparing a used car dataset using Python and Pandas. The objective is to improve data quality and prepare the dataset for further analysis.

---

## Dataset
- Source: Car Dekho dataset  
- Initial Records: 4,340 rows  
- Final Records: 3,577 rows (after cleaning)

---

## Cleaning Process

### 1. Data Exploration
- Loaded dataset using Pandas
- Reviewed structure using `df.info()` and `df.columns`

### 2. Missing Values
- Checked for missing values using `df.isnull().sum()`
- No missing values were found in the dataset

### 3. Data Standardization
- Converted all text values to uppercase for consistency

### 4. Duplicate Removal
- Identified 763 duplicate records
- Removed duplicates to ensure data accuracy

### 5. Feature Engineering
- Created a new column **brand** from the car name
- Extracted brand names to enhance data usability

---

## Results
- Clean dataset with no duplicates
- Standardized text format
- Added new feature (brand column)
- Improved dataset structure and usability

---

## Tools Used
- Python
- Pandas
- Google Colab

---

## Preview

### Raw Data
![Raw Data](01_raw_data.png)

### Missing Values Check
![Missing Values](02_missing_values.png)

### Dataset Structure
![Dataset Structure](03_dataset_structure.png)

### Missing Values Cleaned
![Missing Values Cleaned](04_missing_values_cleaned.png)

### Uppercase Transformation
![Uppercase Transformation](05_uppercase_transformation.png)

### Duplicates Before Removal
![Duplicates Before](06_duplicates_before.png)

### Duplicates Removed
![Duplicates Removed](07_duplicates_removed.png)

### Brand Extraction
![Brand Extraction](08_brand_extraction.png)

### Final Dataset Shape
![Final Dataset Shape](09_final_dataset_shape.png)
