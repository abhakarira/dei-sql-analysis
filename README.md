# Belongingness Survey Analysis (SQL)
This project demonstrates how raw Belongingness survey data can be cleaned, validated, and analyzed using SQL.  
The analysis explores how different aspects of belongingness perceptions vary alongside overall satisfaction with workplace culture.

## Data Overview
- Sample Belongingness survey dataset representing ~1,000 employees  
- Long-format structure with multiple survey items per employee  
- Mixed Likert scales (1-5 and 0-10)  
- Dataset is synthetic and used for demonstration purposes

## Project Goal
To examine how employees’ perceptions of different belongingness dimensions (e.g., fair treatment, workforce diversity, comfort of speech) vary across levels of overall satisfaction with workplace culture.

## Repository Structure
- `data/raw/` – original sample dataset (unchanged)  
- `data/processed/` – cleaned and validated dataset  
- `sql/01_schema.sql` – final table schema and data types  
- `sql/02_cleaning.sql` – data cleaning and validation logic  
- `sql/03_analysis.sql` – descriptive analysis queries  
- `docs/data_dictionary.md` – variable definitions and scales

## Status
Cleaning and validation completed.  
Descriptive analysis in progress.
