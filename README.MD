# Task 5 – Python Basics: Reading Data & Simple Cleaning

## Objective
The objective of this task is to practice basic data reading and data cleaning
using Python Pandas.

## Dataset
- Titanic Dataset  
- Dataset was loaded directly from an online source due to file upload issues.

## Tools Used
- Google Colab
- Python
- Pandas, NumPy

## Steps Performed
1. Loaded the dataset using pandas `read_csv()`.
2. Checked dataset structure using `head()` and `info()`.
3. Identified missing values using `isnull().sum()`.
4. Filled missing numeric values with median.
5. Filled missing categorical values with mode.
6. Dropped unnecessary column with many missing values.
7. Removed duplicate records.
8. Created a new column for basic feature engineering.
9. Saved the cleaned dataset as a CSV file.

## Files in This Repository
- `Task5_Cleaning.ipynb` – Jupyter Notebook with all code and outputs
- `cleaned_data.csv` – Cleaned dataset
- `README.md` – Task description and explanation

## Outcome
This task helped in understanding how Python Pandas can be used to clean and
prepare data efficiently instead of manual Excel operations.
