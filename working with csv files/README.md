# Working with CSV Files

This folder contains notebooks for reading, writing, and manipulating CSV files.

## Contents
- `working_with_csv.ipynb` - CSV file operations
- `IPL.csv` - Sample cricket dataset
- `Titanic-Dataset.csv` - Sample mortality dataset
- `netflix_titles.csv` - Sample streaming dataset
- `zomato.csv` - Sample restaurant dataset
- `countries_data.tsv` - Tab-separated values format

## Learning Topics
- Reading CSV files with pandas
- Writing DataFrames to CSV
- Handling different delimiters (CSV, TSV, PSV)
- Data cleaning from CSV sources
- Handling missing values
- Data type inference
- Encoding issues

## Key Skills
- Using pd.read_csv() with various parameters
- File encoding handling
- Delimiter specification
- Data type conversion
- DataFrame export to CSV
- Memory efficient reading

## Important Parameters
- `sep` or `delimiter` - Field separator
- `encoding` - File encoding (UTF-8, latin1, etc.)
- `na_values` - Missing value indicators
- `dtype` - Column data types
- `chunksize` - For large files
