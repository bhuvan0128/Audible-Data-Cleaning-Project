# Audible-Data-Cleaning-Project

# Project Description:


Utilize Power Query Editor in Excel to clean and standardize an Audible dataset. Tasks include formatting columns, ensuring data consistency, and preparing the dataset for analysis.

**Dataset Link:** https://drive.google.com/file/d/1yjyozaSrwShoaROq-TDuSgC5HNLLmrTE/view?usp=sharing


# Project Objectives
- Data Cleaning and Preparation:
- Standardize the name column.
- Separate combined author names.
- Ensure consistent date formatting in the release date column.
- Convert time, price, and ratings columns into appropriate formats.
- Merge release date and language columns into a single new column.
- Ensure currency formatting in the price column.
- Data Analysis Readiness: Format data so that it’s ready for more in-depth analysis.

# Tasks and Steps

1. Standardize the name column to ensure consistent title casing.
2. Separate combined first and last names in the author column if they are currently combined.
3. Ensure all entries in the releasedate column follow a consistent date format (DD-MM-YYYY).
4. Convert the time column from text format to a duration format that Excel recognizes.
5. Ensure the price column is in a numeric format, and identify any non-numeric values.
6. Convert text ratings in the stars column to numeric values.
7. Split the narratedby column into multiple columns if multiple narrators are listed.
8. Merge the releasedate and language columns into a single new column named releaseinfo with the format "DD-MM-YYYY, Language."
9. Ensure all currency values in the price column are formatted consistently with two decimal places.


# Steps to Clean and Standardize the Dataset
**Open Power Query Editor:**
- Load your dataset into Power Query Editor in Excel to begin cleaning and transforming the data.
**Apply Transformations:**
- Follow the tasks outlined above to clean and standardize the dataset using Power Query Editor.

**Final Steps:**
- Apply Changes: Once all transformations are complete, click "Close & Load" to load the cleaned dataset back into Excel.
- Verify Data: Review the dataset to ensure all transformations have been applied correctly, ensuring the data is ready for analysis.

# Technologies Used
- Power Query Editor in Excel
- Excel Functions for data transformations (e.g., "Capitalize Each Word," "Split Column," "Change Type")
- Data Cleaning & Standardization Techniques

# Project Impact
This project enhances the quality of the Audible dataset by transforming and cleaning the data. It ensures consistency in key columns, making it more ready for analysis. These improvements allow for more accurate insights into the dataset and better decision-making for future analyses.
