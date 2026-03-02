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

## Input - Output
<img width="1661" height="616" alt="Captura de pantalla 2026-03-01 204259" src="https://github.com/user-attachments/assets/219569be-6244-4e3a-a0ba-dba4f4d1c568" />

--------------------------------------------------------------------------------------------------------------

<img width="1130" height="718" alt="Captura de pantalla 2026-03-01 222247" src="https://github.com/user-attachments/assets/63f3788b-d465-4144-ab57-df378f4a15e2" />


