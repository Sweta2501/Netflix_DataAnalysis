# Netflix Dataset Analysis

## Data Exploration
- **head()**: Displays the first few rows of the dataset.
- **tail()**: Displays the last few rows of the dataset.
- **shape**: Returns the dimensions of the dataset (number of rows and columns).
- **size**: Returns the total number of elements in the dataset.
- **columns**: Returns the column names of the dataset.
- **dtypes**: Returns the data types of each column in the dataset.
- **info()**: Provides a concise summary of the DataFrame.

## Data Cleaning
- **isnull()**: Identifies missing values in the dataset.
- **dropna()**: Removes rows with missing values (by default).

## Data Transformation
- **to_datetime()**: Converts a string or numeric column to datetime format.
- **str.contains()**: Filters rows based on patterns within a string column.
- **str.split()**: Splits a string column into separate values based on a delimiter.

## Data Analysis
- **value_counts()**: Returns the number of times each unique value appears in a column.
- **groupby()**: Groups the dataset by one or more columns and allows for aggregate operations on each group.
- **countplot()**: Creates a count plot to visualize the number of times each unique value appears in a categorical column.
- **unique()**: Returns the unique values in a column.
- **nunique()**: Returns the number of unique values in a column.
- **max()**, **min()**, **mean()**: Return the maximum, minimum, and mean values of a numeric column.
