**Data Cleaning with Python**

This repository contains Python scripts to clean raw CSV data. The cleaning process involves several steps to ensure the data is accurate, consistent, and ready for analysis.

### Steps to Clean the Data:

1. **Importing Libraries and Reading Data:**
   - We will be using Python and the pandas library for data manipulation.
   - First, import the pandas library.
   - Read the raw CSV file to get an overview of the data.

2. **Removing Unnecessary Columns:**
   - Iterate through the columns and remove those that are not needed for analysis.

3. **Checking for Duplicate Rows:**
   - Detect and remove duplicate rows to avoid redundancy in the dataset.

4. **Merging Duplicate Records:**
   - If duplicate records are found, merge them to consolidate the information.

5. **Correcting Dates:**
   - Remove any decimals or inconsistencies in date formats to ensure accuracy.

6. **Handling Null Values:**
   - Assign 'unknown' to null data in columns such as country, artist nationality, and culture to maintain completeness.

7. **Saving Clean Data:**
   - Save the cleaned data to a new CSV file for further analysis.


### Requirements:

- Python 3.x
- pandas library

### Contributing:

Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.


### Acknowledgments:

Thank you to the pandas development team for providing such a powerful tool for data manipulation.
