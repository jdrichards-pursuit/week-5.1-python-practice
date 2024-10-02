# Employee Performance Data Dictionary

| Column Name        | Data Type | Description                                                   |
|--------------------|-----------|---------------------------------------------------------------|
| EMPLOYEE_ID        | Integer   | Unique identifier for each employee                           |
| FIRST_NAME         | String    | First name of the employee                                    |
| LAST_NAME          | String    | Last name of the employee                                     |
| EMAIL              | String    | Email address of the employee                                 |
| PHONE_NUMBER       | String    | Phone number of the employee                                  |
| HIRE_DATE          | Date      | Date when the employee was hired                              |
| JOB_ID             | String    | Identifier for the employee's job role                        |
| SALARY             | Integer   | Annual salary of the employee in USD                          |
| COMMISSION_PCT     | Float     | Commission percentage (appears to be 0 for all employees)     |
| MANAGER_ID         | Integer   | Identifier for the employee's manager                         |
| DEPARTMENT_ID      | Integer   | Identifier for the department the employee belongs to         |
| PERFORMANCE_SCORE  | Integer   | Employee's performance score (range: 60-95)                   |
| YEARS_AT_COMPANY   | Integer   | Number of years the employee has been with the company        |

## Detailed Field Descriptions

1. EMPLOYEE_ID: A unique numerical identifier assigned to each employee in the company. This serves as the primary key for employee records.

2. FIRST_NAME: The given name of the employee. This field contains the employee's first name as a text string.

3. LAST_NAME: The family name or surname of the employee. This field contains the employee's last name as a text string.

4. EMAIL: The official email address assigned to the employee by the company. It is typically used for work-related communication.

5. PHONE_NUMBER: The contact number for the employee. This may be a work phone number or a personal number used for work purposes.

6. HIRE_DATE: The date when the employee officially joined the company. This helps in tracking employee tenure and may be used for various HR processes.

7. JOB_ID: A code or identifier that represents the specific job role or position of the employee within the company's job classification system.

8. SALARY: The annual compensation paid to the employee, expressed in US dollars. This represents the base salary before any bonuses or commissions.

9. COMMISSION_PCT: The percentage of sales or other metrics that an employee might earn as additional compensation. In this dataset, it appears to be 0 for all employees, suggesting commissions may not be applicable.

10. MANAGER_ID: The EMPLOYEE_ID of the person who directly manages this employee. This helps in understanding the reporting structure within the company.

11. DEPARTMENT_ID: A numerical identifier for the department to which the employee belongs. This helps in organizing employees into different functional areas of the company.

12. PERFORMANCE_SCORE: A numerical evaluation of the employee's job performance, ranging from 60 to 95. Higher scores likely indicate better performance, though the specific criteria for these scores are not provided in the dataset.

13. YEARS_AT_COMPANY: The number of complete years the employee has worked at the company, calculated from their hire date to the present or to the date when this data was compiled.

