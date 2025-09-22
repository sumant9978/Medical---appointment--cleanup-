# Data Cleaning & Preprocessing Task

This repository contains the deliverables for the data cleaning internship task.

## Files Included
1. **cleaned_dataset.csv**  
   - A cleaned dataset with missing values handled, duplicates removed, and standardized formats.

2. **summary_of_changes.pdf**  
   - A short summary of the changes made during the data cleaning process.

## Cleaning Steps Performed
- Converted `Age` column to numeric and filled missing values with the median.  
- Standardized `Gender` values to 'male', 'female', or 'unknown'.  
- Standardized `Country` names to 'usa', 'canada', 'india', or 'unknown'.  
- Removed duplicate rows.  
- Dropped rows with missing `CustomerID`.  
- Cleaned `Name` column (trimmed spaces, proper case).  
- Converted `JoinDate` to a proper datetime format.  
- Renamed all column headers to lowercase.

## How to Use
- Download the `cleaned_dataset.csv` file to use in your analysis.  
- Refer to `summary_of_changes.pdf` for a quick overview of the modifications.

---
✔️ Prepared as part of the Data Cleaning & Preprocessing internship task.
