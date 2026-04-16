# Experiment-13
## Aim
To perform data wrangling and preprocessing on a dataset, specifically focusing on identifying and dealing with missing values, standardizing inconsistent data, and converting data types using the Python pandas library.

## Theory
Data wrangling (or data munging) is the process of cleaning, structuring, and enriching raw data into a desired format for better decision-making in less time. Real-world data is often messy, containing missing values, inconsistent formatting, or incorrect data types, which can hinder data analysis and machine learning models.

Key preprocessing techniques covered in this experiment include:

Identifying Missing Values: Using functions like isna(), notna(), and isnull().sum() to detect the presence and count of NaN (Not a Number) values across rows and columns.

Handling Missing Values:

Deletion: Removing entire rows or columns containing missing data using dropna(). This is useful when the missing data is sparse.

Imputation: Filling in missing values using fillna(). Data can be replaced with a constant value (e.g., 0 or 'DEFAULT'), or statistical measures like the mean or median of the respective column to maintain the dataset's distribution.

Standardizing Inconsistent Data: Replacing placeholder characters (like "-") with standard NaN values to allow programmatic handling. It also involves standardizing string cases (e.g., converting all department names to uppercase using .str.upper()) to ensure uniformity.

Type Conversion: Converting raw string data into proper numeric formats using pd.to_numeric(), and parsing date strings into standard datetime objects using pd.to_datetime(), which enables time-series analysis.

## Conclusion
In this experiment, data preprocessing techniques were successfully implemented using the pandas and numpy libraries. The exercise demonstrated how to systematically clean a raw dataset by identifying missing values, dropping incomplete records, and applying various imputation strategies (constant, mean, and median).
