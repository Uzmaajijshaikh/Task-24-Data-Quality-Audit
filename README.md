Data Analytics Internship – Task 24 (Data Quality Audit)

This repository contains my submission for Task 24 of the Data Analytics Internship.

Dataset - Sample Superstore Dataset

Objective - The objective was to audit the dataset for missing values, duplicate records, range issues, and consistency issues, quantify the identified issues, and create a cleaned sample.

Tools Used
1. Google Colab (Python/Pandas)
2. GitHub

Data Quality Audit
1. Used the Sample Superstore dataset containing 9,994 records and 13 columns.
2. Checked all columns for missing values.
3. Checked for duplicate records and identified 17 duplicate rows.
4. Created validation rules for Quantity, Sales, Discount, and Postal Code.
5. Checked categorical fields for consistency.
6. Found no missing values, invalid Quantity, invalid Sales, invalid Discount, invalid Postal Code, or identified categorical consistency issues.
7. Created an Issue Log documenting the identified duplicate records.
8. Removed the 17 duplicate rows to create a cleaned dataset containing 9,977 records.
9. Re-ran the quality checks and confirmed that no duplicate rows or other identified validation issues remained.

Quality Audit Results
1. Original records - 9,994
2. Duplicate rows identified - 17
3. Duplicate rows removed - 17
4. Final records - 9,977
5. Missing values - 0
6. Invalid Quantity values - 0
7. Invalid Sales values - 0
8. Invalid Discount values - 0
9. Invalid Postal Code values - 0
10. Consistency issues - 0

Files
1. Task_24.ipynb - Notebook containing the data quality audit, validation rules, cleaning, and final checks
2. Issue_Log.csv - Issue log containing the identified data quality issue
3. Task_24.csv - Cleaned dataset after removing duplicate records
4. README.md - Summary of the data quality audit

Conclusion
The Data Quality Audit was successfully completed on the Sample Superstore dataset. The audit identified 17 duplicate records, which were removed during the cleaning process. The final dataset contains 9,977 records with no remaining duplicate rows or other identified validation issues. The task provided practical experience in creating validation rules, documenting issues, and verifying data quality after cleaning.
