# Pewlett-Hackard-Analysis
## Build Employee Database with PostgreSQL and perform SQL queries to explore and analysis data by applying skills of Data Modeling, Data Engineer and Data Analysis.

Challenge
Object
Create a list of candidates for the mentorship program.

Deliverable Requirements:
Using the ERD you created in this module as a reference and your knowledge of SQL queries, create a Retirement Titles table that holds all the titles of current employees who were born between January 1, 1952 and December 31, 1955. Because some employees may have multiple titles in the database—for example, due to promotions—you’ll need to use the DISTINCT ON statement to create a table that contains the most recent title of each employee. Then, use the COUNT() function to create a final table that has the number of retirement-age employees by most recent job title.

A query is written and executed to create a Retirement Titles table for employees who are born between January 1, 1952 and December 31, 1955
The Retirement Titles table is exported as retirement_titles.csv
​A query is written and executed to create a Unique Titles table that contains the employee number, first and last name, and most recent title.
The Unique Titles table is exported as unique_titles.csv
A query is written and executed to create a Retiring Titles table that contains the number of titles filled by employees who are retiring.
The Retiring Titles table is exported as retiring_titles.csv
Results with detail analysis:
A query is written and executed to create a Retirement Titles table for employees who are born between January 1, 1952 and December 31, 1955.

the ERD demonstrates relationships between original 6 tables:
![EmployeeDB](https://user-images.githubusercontent.com/59430635/144792020-cd49cd07-0ece-450a-8812-0eaa1bfb498a.png)

Determining the number of individuals retiring


In conclusion, There are 41,380 records of individuals ready to retirement
## Deliverable 2: The Employees Eligible for the Mentorship Program
Deliverable Requirements:
Using the ERD you created in this module as a reference and your knowledge of SQL queries, create a mentorship-eligibility table that holds the current employees who were born between January 1, 1965 and December 31, 1965.

A query is written and executed to create a Mentorship Eligibility table for current employees who were born between January 1, 1965 and December 31, 1965.
The Mentorship Eligibility table is exported and saved as mentorship_eligibilty.csv
Results with detail analysis:
A query is written and executed to create a Mentorship Eligibility table for current employees who were born between January 1, 1965 and December 31, 1965.


The analysis should contain the following:
Overview of the analysis
Explain the purpose of this analysis.:

In this deliverable, Bobby was tasked to determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. Then, you’ll write a report that summarizes your analysis and helps prepare Bobby’s manager for the “silver tsunami” as many current employees reach retirement age.
## Deliverable 3: A written report on the employee database analysis

Results
Provide a bulleted list with four major points from the two analysis deliverables. 
Use images as support where needed:
![Screen Shot 2021-12-06 at 12 37 46 AM](https://user-images.githubusercontent.com/59430635/144793156-62858010-0695-4cc0-bb03-a44f4c02152f.png)

From the finding of the eligible retirees, High Percentage of the workforce could retire at any given time.
From the job titles of the eligible retirees, the breakdown is below.
32,452 Staff
29,415 Senior Engineer
14,221 Engineer
8,047 Senior Staff
4,502 Technique Leader
1,761 Assistant Engineer

Summary
Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami.":

1) How many roles will need to be filled as the "silver tsunami" begins to make an impact?.

90,398 roles are in urgent need to be filled out as soon as the workforce starts retiring at any given time.

2) Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

No, we have 1,940 employees who are eligible to participate in a mentorship program.
![Screen Shot 2021-12-06 at 12 37 26 AM](https://user-images.githubusercontent.com/59430635/144793080-95366b3f-26e7-4c62-9aad-56b172f0426e.png)
