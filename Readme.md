# Employee Performance Analysis with Pandas

## Objective:

Analyze the employee performance dataset using Pandas to perform data loading, exploration, selection, and operations. (feel free to take a look at the data in the [employee_performance.csv](./data/employee_performance.csv)) as well as the [data-dictionary.md](./data/data-dictionary.md) to understand the data.

## Code

Place your code for this challenge in the `employee_performance_analysis.py` file.

## Dataset:

The employee performance dataset is stored in a CSV file named [`employee_performance.csv`](./data/employee_performance.csv) in the `data` directory.

**Note:** If you can't remember how to complete any of the steps, check out the [Pandas Basics Tutorial](https://github.com/jdrichards-pursuit/week-5.1-python-theory) for a refresher. Try not to use AI for this, use the lesson, documentation for [Pandas](https://pandas.pydata.org/docs/) or do the research online. If you do use AI, create prompts that check for understanding and avoid simply giving you the answer.

## Steps:

### 1. Load the Data:

Write a function `load_employee_data()` to load the dataset into a Pandas DataFrame.

### 2. Explore the DataFrame:

Write a function `explore_employee_dataframe(df)` to:

- Display the first 10 rows.
- Show the DataFrame info.
- Provide summary statistics.

### 3. Select and Filter Data:

Write a function `select_and_filter_employee_data(df)` to:

- Select the `name` and `department` columns.
- Filter employees with a `performance_score` greater than 80.
- Use `loc` to select specific rows and columns.

### 4. Perform Data Operations:

Write a function `employee_data_operations(df)` to:

- Add a new column `salary_per_year` calculated as `salary / years_at_company`.
- Sort the DataFrame by `performance_score` in descending order.

### 5. Advanced Tasks:

Write a function `advanced_employee_analysis(df)` to:

- Find the department with the highest average `performance_score`.
- Identify the top 3 employees with the highest `salary_per_year` and display their `name`, `department`, and `salary_per_year`.

[Back to Readme](README.md)

[Go To Pandas Basics Tutorial](./pandas_basics.ipynb)
