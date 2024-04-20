# Employee_Salary_Analysis

Sathish |
Data Analyst |
20/04/2024 |
sathishgudri@gmail.com |
Bangalore, India |

## About Dataset:
Annual salary information including gross pay and overtime pay for all active, permanent employees of Montgomery County, MD paid in calendar year 2023. This dataset is a prime candidate for conducting analyses on salary disparities, the relationship between department/division and salary, and the distribution of salaries across gender and grade levels.

## Approach:
- Goal:
  - Understanding the salary structures of the employees.
  - Generating insights about Department-wise employees and their salaries.
  - Identifying potential salary gaps.
  - Understanding the impact of Overtime and Longevity Pay.

- Data Cleaning & Pre-processing:
  - Identified and treated missing values.
  - Eliminated duplicate records from the dataset.

- Tools & Technologies:
  Programming Language Python, with its libraries (Pandas, NumPy, Matplotlib, Seaborn) is used.
## Analysis & Insights:
Department v/s Employee Counts
 - Department "POL", "HHS", "FRS" contains most number of the employees of the Company.
 - Department "BOA", "MPB", "ECM" has the least number of employees.
 - All department have atleast one female employees, however, department 'BOA', 'IGR', 'ORE', 'ZAH' do not have any male employees even though the employee count is more than 2.

Gender v/s Total Employees
 - Company has more male employees than females.
 - The imbalnce ratio between male and female is 1.43.

Average base salary v/s Department
 - The top departments with highest average basic salaries are 'IGR', 'ZAH', 'OLR', 'ELM', and 'NDA'.
 - Departments with lowest average basic salaries are 'LIB', 'ABS', 'CEC', 'OAS', and 'DOT'.

Average base salary v/s Employee Count
 - There is a negative correlation between the Average Base Salary and Employees Count i.e, more the number of employees, lesser the average salary.

Average base salary v/s Gender
 - The average base salary based on gender is highest in the case of male employees, however, the difference between the male and female is just Rupees.4738 only.

Average base salary v/s Salary Gap
 - Out of the total 38 departments having combination of both male and female employees, 15 departments have salary gap of male employees, and 23 departments have that of female employees.
 - 'MPB', 'ECM', 'OGM', 'CEX' AND 'OLO' departments are the top 5 departments with highest salary gap and department 'OIG' marks as the department with the lowest.
 - Due to the want of data, the reasons for the salary gap is not known. The general possibilities includes experience, qualification, job role etc.

Overtime v/s Department
 - even though 'FRS' and 'COR' are ranked 3 and 5 in terms of departments having highest employees, they are also the departments paying highest overtime pay.
 - Department 'OIG', 'OLO', 'OGM', 'OFR', 'ORE', 'OCP', 'OAG', 'NDA', 'MPB', 'IGR', 'ECM', 'ZAH' are the departments which do not pay any overtime charges.

Gender v/s Overtime
 - Out of the total number of overtime employees, 74% are male employees.
 - with only 26%, female employees are less likely to choose overtime work.

Longevity Analysis
 - 'POL', 'FRS', 'SHF', 'HRC', 'DGS' are the departments with highest longevity pay.
 - Department 'HRC', with only 11 employees on board, is the 4th highest longevity paying department.
 - 'ECM','OGM', 'OFR', 'MPB' departments do not pay any longevity pay.

Base Salary v/s Overtime Pay v/s Longevity Pay
 - There is a slight upward trend between the data points in both the cases of Overtime Pay, and Longevity Pay, indicating that employees with higher base salary tends to receive higher Overtime Pay or Longevity Pay.

# Thank You
