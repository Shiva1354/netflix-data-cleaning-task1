# Netflix Data Cleaning – Task 1

## Internship: Data Analyst – Task 1: Data Cleaning and Preprocessing

### About the Dataset
This dataset contains details of movies and TV shows available on Netflix. It includes information such as title, cast, director, release year, country, duration, and the date the content was added to the platform.

Source: [Kaggle – Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)

### Objective
The goal of this task was to clean and preprocess the raw dataset to make it analysis-ready. This involved handling missing values, formatting inconsistencies, standardizing column names, and exporting a clean version of the dataset.

### Tools Used
- Python
- Pandas

### Cleaning Steps Performed
- Removed duplicate rows
- Filled missing values in columns like `director`, `cast`, and `country` with `'Unknown'`
- Standardized text values:
  - Converted `type` to lowercase
  - Converted `rating` to uppercase
- Cleaned and converted `date_added` to proper datetime format
- Renamed all columns to lowercase and replaced spaces with underscores (e.g., `Date Added` → `date_added`)
- Exported the cleaned dataset to CSV format

### Files Included
- `Netflix_data.ipynb` – Python notebook with full data cleaning process
- `netflix_cleaned.csv` – Final cleaned dataset
- `README.md` – This documentation file

### Status
✅ Task Completed and Submitted

---

📌 Submitted by:  
**D. Siva Kumar**  
**Date:** 4th August 2025
