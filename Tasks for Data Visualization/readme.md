# Data Visualization Assignment

## Introduction
This assignment was provided by **Saylani Mass IT Program (SMIT)** as part of the **Tasks for Data Visualization** module. The dataset used in this assignment is a CSV file containing COVID-19 country-wise latest data. The objective of this assignment is to perform various data cleaning, analysis, and visualization tasks using Python and relevant libraries.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Tasks Performed
### **Task 1: Load and Display Data**
- Read the dataset from the provided CSV file using Pandas.
- Display the first 5 rows of the dataset.

### **Task 2: Set the Dataset Index**
- Set the index of the dataset to the `Unnamed: 0` column.

### **Task 3: Rename the Index Column**
- Replace the index column name with `index`.

### **Task 4: Replace Whitespace in Column Names**
- Created a function to replace spaces in column names with underscores.

### **Task 5: Check Basic Information**
- Displayed column names, data types, and missing values.

### **Task 6: Handle Missing Values**
- Filled NaN values in numerical columns with their respective mean values.

### **Task 7: Count Unique Countries**
- Found the number of unique countries present in the dataset.

### **Task 8: Remove Duplicate Entries**
- Checked for duplicate country entries and removed them.

### **Task 9: Statistical Summary of Total Cases**
- Computed the mean, median, and standard deviation of total confirmed cases.

### **Task 10: Handling Strings in Death Column**
- Replaced string values in the `Deaths` column with the mean of valid numeric values.

### **Task 11: Convert Data Types**
- Converted the `Deaths` column to a numeric data type.

### **Task 12: Calculate Global Totals**
- Computed the total number of deaths and recoveries worldwide.

### **Task 13: Identify Countries with High Cases**
- Found the number of countries with more than 1 million cases.

### **Task 14: Identify High Recovery Rate Countries**
- Listed countries with a recovery rate above 95%.

### **Task 15: Drop Unnecessary Columns**
- Dropped `WHO_Region` and `Confirmed` columns from the dataset.

### **Task 16: Find the Country with the Most Deaths**
- Identified the country with the highest number of deaths.

### **Task 17: Sort Countries by Deaths**
- Sorted the dataset in descending order based on `Deaths`.

### **Task 18: Create a Total Cases Column**
- Created a new column `Total_cases` summing `Deaths`, `Recovered`, and `Active` cases.

### **Task 19: Calculate Death Rate**
- Computed the death rate as a percentage of total cases.

### **Task 20: Identify Countries with Increasing Cases but Low Death Rate**
- Analyzed and listed countries where cases are increasing but death rates remain low.

### **Task 21: Display Select Columns**
- Printed the first few rows containing only `Country/Region` and `Death_Rate`.

### **Task 22: Scatter Plot of Total Cases vs Deaths**
- Created a scatter plot comparing total cases and total deaths by country.

### **Task 23: Save Processed Dataset**
- Saved the cleaned and processed dataset as `processed_covid_data.csv`.

## Conclusion
This assignment involved extensive data cleaning, analysis, and visualization tasks using Pandas, NumPy, Matplotlib, and Seaborn. The dataset was processed efficiently to extract meaningful insights about COVID-19 cases, deaths, and recovery rates worldwide.

