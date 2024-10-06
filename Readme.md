# Employee Performance Analysis with Pandas

<img src="./assets/data-pandas.webp" alt="Pandas Logo" width="300">


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

### 1.1. Convert all column names to lowercase

Use the `df.columns = df.columns.str.lower()` to convert all column names to lowercase.

This will make it easier to work with the data in the rest of the challenge.

### 2. Explore the DataFrame:

Write a function `explore_employee_dataframe(df)` to:

- Display the first 10 rows.
- Show the DataFrame info.
- Provide summary statistics.

### 3. Select and Filter Data:

Write a function `select_and_filter_employee_data(df)` to:

- Select the 'employee_id', 'first_name', 'last_name', and 'performance_score' columns.
- Filter employees with a `performance_score` greater than 80.
- Use `loc` to select specific rows and columns.

### 4. Perform Data Operations:

Write a function `employee_data_operations(df)` to:

- Add a new column `salary_per_year` that displays the salary based on the number of years the employee has worked at the company.
- Sort the DataFrame by `performance_score` in descending order.


### 5. Find the top 3 employees with the highest salary

Write a function `top_3_employees_with_highest_salary(df)` to:

- Sort the DataFrame by `salary` in descending order.
- Select the top 3 employees.
- Display their `fist_name`, `last_name` and `email`, and `salary. Salary should be rounded to 2 decimal places.


### 6. Calculate the average performance score by department

Write a function `avg_performance_score_by_department(df)` to calculate the average performance score by department.

- Display the average performance score for each department.

### 7. Plot a scatter plot of salary vs years_at_company

Write a function `plot_salary_vs_years_of_experience(df)` to plot a scatter plot of salary vs years_at_company. 

- use plt.scatter to plot the data
- use plt.show to display the plot




### Resources

[Pandas Documentation](https://pandas.pydata.org/docs/)
[Matplotlib Documentation](https://matplotlib.org/stable/users/index.html)
[Go To Pandas Basics Tutorial](https://github.com/jdrichards-pursuit/week-5.1-python-theory)
