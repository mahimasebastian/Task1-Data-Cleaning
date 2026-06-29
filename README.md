# Data Cleaning and Preprocessing

## Objective
The objective of this task was to clean and preprocess the Customer Personality Analysis dataset using Python and Pandas.

## Dataset
Customer Personality Analysis (Kaggle)

## Tools Used
- Python
- Pandas
- Jupyter Notebook

## Data Cleaning Steps Performed

1. Loaded the dataset using Pandas.
2. Read the dataset using the correct tab (`\t`) separator.
3. Checked for missing values using `isnull().sum()`.
4. Filled missing values in the `Income` column with the mean value.
5. Checked for duplicate rows and confirmed no duplicates were present.
6. Converted the `Dt_Customer` column from text to datetime format.
7. Renamed all column headers to lowercase and replaced spaces with underscores.
8. Standardized text columns (`education` and `marital_status`).
9. Verified the data types of all columns.
10. Saved the cleaned dataset as `cleaned_marketing_campaign.csv`.

## Outcome
The dataset is now clean, consistent, and ready for further analysis and visualization.