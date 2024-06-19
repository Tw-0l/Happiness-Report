## Happiness Report Data Cleaning

This script cleans and prepares happiness report data from multiple CSV files for further analysis.

**Libraries:**

* pandas
* numpy

**Data Files:**

The script assumes you have CSV files named `2015.csv`, `2016.csv`, ..., `2019.csv` containing happiness report data for each year.

**Steps:**

1. **Import Libraries:** Import necessary libraries like pandas and numpy.
2. **Load Data:** Use `pandas.read_csv` to load data from each CSV file into separate DataFrames.
3. **Data Profiling:**
    * Print info about each DataFrame using `df.info()`. This displays data types, missing values, and memory usage.
    * Print the shape of each DataFrame using `df.shape` to get the number of rows and columns.
    * Print column names of each DataFrame.
4. **Data Quality Checks:**
    * **Consistency:** Check if all DataFrames have the same columns. Identify and potentially remove extra columns using `df.drop()`.
    * **Relevance:** Identify and potentially remove irrelevant columns based on your analysis goals.
    * **Uniqueness:** Check for duplicate records using `df.duplicated().sum()` and remove them if necessary.
    * **Completeness:** Check for missing values using `df.isnull().sum()`. Decide on a strategy to handle missing values (e.g., imputation, deletion).
    * **Accuracy:** Validate data types and identify outliers using methods like boxplots, z-scores, or interquartile ranges (IQR). You can choose to handle outliers by removing them, capping them, or winsorizing them.

**Note:** The script currently includes comments and explanations for each step but does not implement the data cleaning actions within the comments. You will need to uncomment and modify the code sections based on your specific data quality issues.

**Additional Considerations:**

* The script can be extended to handle data cleaning tasks specific to your analysis, such as handling string formatting inconsistencies or converting data types.
* You may want to save the cleaned data to new CSV files or pickle files for later use.

**Example Usage:**

```python
# ... (script code)

# After cleaning the data, you can proceed with your analysis

# Example: Analyze happiness score by country
average_happiness = data_2019.groupby('Country or region')['Score'].mean()
print(average_happiness.sort_values(ascending=False).head(10))
```

This example retrieves the average happiness score for each country in the 2019 data (assuming data cleaning is complete).

Remember to adapt this script to your specific data cleaning needs and analysis goals.
