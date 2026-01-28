# CSV Data Cleaning Using Google Sheets
Data cleaning project using Google Sheets to fix improperly formatted CSV data by correcting delimiter issues and splitting text into columns.

## Project Overview
This project demonstrates how to clean improperly formatted CSV data using Google Sheets. 
The original dataset was imported incorrectly due to a delimiter issue, causing all values to appear in a single column.

## Problem
- The CSV file used semicolons (`;`) as delimiters
- Google Sheets initially interpreted the file using commas (`,`)
- As a result, all data appeared in one column instead of being properly separated

## Tools Used
- Google Sheets
- CSV file format

## Cleaning Steps
1. Imported the CSV file into Google Sheets
2. Identified that the data was not properly separated into columns
3. Selected the affected column
4. Navigated to **Data → Split text to columns**
5. Selected **Semicolon (;)** as the delimiter
6. Verified that the data was correctly aligned into individual columns
   
## Results
- Data was successfully split into correct columns
- Dataset is now clean and ready for analysis

## Files Included
- `raw_data.csv` – original dataset with delimiter issue
- `cleaned_data.csv` – corrected dataset
