# Task 3: Cleaning Data  

**Intern:** Malaika Saleem  
**Track:** Data Analytics  
**Program:** Oasis Infobyte Internship (OIBSIP)  

## Overview  
  
This project cleans the Titanic passenger dataset step by step, so that it is ready for analysis.  

## Steps Performed

1. Checked data quality (shape, duplicates, missing values)
2. Handled missing values (Age and Fare filled with median, Cabin dropped)
3. Checked duplicates and formatting
4. Detected outliers using the IQR method
5. Capped Fare outliers in a new column, `Fare_capped`
6. Corrected data types (PassengerId changed to str)
7. Created a before vs after summary table
8. Saved the cleaned data as `tested_cleaned.csv`

## Files

- `cleaning_data.ipynb`: notebook with all the cleaning steps
- `tested.csv`: original (raw) dataset
- `tested_cleaned.csv`: cleaned dataset

## Tools Used

Python, Pandas, Jupyter Notebook (VS Code)