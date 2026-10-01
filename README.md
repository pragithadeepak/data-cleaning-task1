## Task 1: Data Cleaning and Preprocessing

## Objective
Clean and prepare the Netflix Movies and TV Shows dataset for analysis using Python Pandas.

## Tools Used
- Python
- Pandas
- Google Colab
- GitHub Desktop

## Dataset
- Original file: `netflix_titles.csv`
- Source: https://www.kaggle.com/datasets/shivamb/netflix-shows

## Cleaning Summary
- Checked missing values, duplicate rows, and column data types.
- Standardized column names to lowercase with underscores.
- Removed unnecessary spaces from text values.
- Checked for and removed exact duplicate rows.
- Filled missing director, cast, and country values with "Unknown".
- Converted `date_added` to datetime and exported dates in DD-MM-YYYY format.
- Converted `release_year` to a nullable integer type.
- Reviewed the cleaned dataset for remaining issues.

## Results
- Final dataset size: 8,807 rows and 12 columns.
- Remaining duplicate rows: 0.
- No missing values remain in director, cast, or country.
- date_added was converted to datetime.
- release_year was converted to nullable integer (Int64).

## Repository Files
- `netflix_titles.csv` — Original dataset.
- `cleaned_dataset.csv` — Cleaned dataset.
- `task1_data_cleaning.ipynb` — Python code and notebook outputs.
- `README.md` — Project description and cleaning summary.

## How to Run
1. Open `task1_data_cleaning.ipynb` in Google Colab.
2. Run the upload cell and select `netflix_titles.csv`.
3. Run the remaining cells in order.
4. Download the generated `cleaned_dataset.csv`.
