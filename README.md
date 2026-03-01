# TV Schedule ETL Pipeline

**Technologies:** Python 3.10+, Pandas, Google Sheets API.

## Project Overview
This project automates the processing of TV broadcast schedules. It transforms raw Excel files into a standardized format using Python, reducing manual work by 90%.

## Key Features
- **Data Cleaning:** Uses Regex to extract Season/Episode info and handle special events like UFC/Boxing.
- **Logic:** Handles "late-night" broadcasts (crossing midnight) correctly.
- **Google Sheets Integration:** Connects to a Google Sheet to allow manual corrections for specific edge cases.
- **Duplicate Prevention:** Uses MD5 hashing to merge duplicates without losing data.

## Note
This is a portfolio project demonstrating ETL logic. It requires private credentials to run locally.
