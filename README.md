# Task-3-Credit-Card-Analysis
SQL Usage Summary in the Credit Card Dashboard
SQL played a crucial role in establishing the foundation for data storage, import, and preprocessing to enable effective dashboard visualization and analysis. Below is an overview of how SQL was utilized throughout the project:

 Database Setup
A dedicated database named ccdb was created to house all project-related data.

Two primary tables were structured:

cc_detail – Captures credit card transaction data and product-related attributes.

cust_detail – Contains customer demographic, financial, and behavioral information.

Data Import
Data from CSV files was seamlessly imported into the respective tables using the COPY command.

Additional data entries (for Week 53) were appended later using the same method to ensure completeness.

 Data Formatting and Error Handling
To address issues with invalid date formats (e.g., "0"), the SQL session's date format was explicitly set using:
SET datestyle TO 'ISO, DMY';
This ensured proper parsing and compatibility during data import.

