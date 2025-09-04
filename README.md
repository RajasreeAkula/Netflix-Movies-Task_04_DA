# Netflix-Movies-Task_01_DA
Cleaned and standardized Netflix titles dataset with consistent date format, fixed data types, and ready for analysis

Netflix Data Cleaning in Excel & Python
This project focuses on cleaning and standardizing the Netflix Titles dataset (netflix_titles.csv). The dataset contains information about Netflix movies and TV shows.

**Dataset Columns**
show_id, type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, description

**Data Cleaning Steps**
**Step 1: Handle Missing Value**s
Replaced blank values in director, cast, and country with "Unknown".
Converted valid date_added values into dd-mm-yyyy format.
Filled missing date_added values with "Unknown".

**Step 2: Remove Duplicates**
Removed duplicate rows across all columns.

**Step 3: Standardize Text**
Applied lower() and trim() to text columns.
Standardized country names (e.g., "United States" → "usa").

**Step 4: Convert Date Formats**
Converted date_added to dd-mm-yyyy format.

**Step 5: Rename Columns**
Converted all column headers to lowercase and replaced spaces with underscores.

**Step 6: Fix Data Types**
Ensured release_year is numeric.

**Output**
Final cleaned dataset: Netflix Movies and TV Shows Sales Data

**Technologies Used**
Excel (formula reference)

