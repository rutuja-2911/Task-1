# Task 1: Data Cleaning and Preprocessing
Objective: Clean and prepare a raw dataset (with nulls, duplicates, inconsistent formats).
Tools: Python (Pandas)
This script performs basic data cleaning operations on a customer personality dataset stored in a CSV file. It uses Python and the pandas library to read, clean, and save the processed data.

# Steps Performed
# 1. Load Data
Reads the dataset from Customer_Personality_Analysis.csv using pandas.read_csv().

# 2. Initial Inspection
Displays the shape of the dataset.
Prints data types for each column.
Shows the number of missing values per column.
Identifies and removes duplicate rows.

# 3. Text Cleaning
Strips whitespace and standardizes case for Gender and Country columns if they exist.

# 4. Date Parsing
Attempts to convert all object-type columns to datetime format (assuming day-first format).

# 5. Column Renaming
Normalizes column names by converting them to lowercase, replacing spaces with underscores, and stripping whitespace.

# 6. Type Conversion
Converts the age column to integer type if it exists.

# 7. Save Cleaned Data
Saves the cleaned DataFrame to a CSV file named customer_personality_cleaned.csv.

# 8. Final Output
Prints the final shape of the dataset and displays a sample of the cleaned data.
