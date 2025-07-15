This project demonstrates a comprehensive data cleaning process for café sales data, transforming raw transactional records into a clean, structured dataset ready for meaningful analysis. The before-and-after screenshots highlight the significant improvements in data quality.

Before Cleaning
The original dataset presented several data quality issues, including:

Inconsistent column names (e.g., Name, Time, Number, Value)

Missing values (empty cells)

Inconsistent data formats (e.g., non-numeric entries like “EB808” in the quantity field)

Duplicate column names (Value appearing twice)

Unclear transaction IDs (TXN numbers mixed with unrelated data)

No clear structure to support reliable analysis

After Cleaning
The cleaned dataset now includes:

Clear, descriptive column names

Properly structured and organized transaction records

Complete data with no missing values

Consistent, validated data formats

Additional useful fields (Payment Method, Service Type, Transaction Date)

A calculated Total Spent column (Quantity × Price Per Unit)

Properly formatted dates with extracted month information

3,089 high-quality records ready for analysis

Key Data Cleaning Steps

Column Renaming: Replaced vague headers with descriptive names

Data Type Conversion: Standardized data types for consistency

Missing Value Handling: Addressed and filled empty cells appropriately

Error Correction: Fixed invalid entries (e.g., removed “EB808” from quantity field)

Calculated Fields: Added Total Spent column for each transaction

Date Processing: Extracted month from transaction dates for time-based analysis

Data Validation: Verified all values fall within expected ranges

Duplicate Handling: Identified and removed duplicate records
