# Employees Analysis -- Overview
We've been tasked with determining the number of retiring employees per title and identifying current employees who are eligible to participate in a mentorship program.  

## Resources
- Data Source: employees.csv; titles.csv; dept_emp.csv; 
- Software: SQL; PostgreSQL

## Part 1 Summary
The first part of the analysis is to create a retirement table that holds all of the titles of current employees who were born between January 1, 1952 and December 31, 1955.  The second table removes instances where an employee may have multiple titles in the database so that the final table only contains the most recent title of each employee.  The final table shows the number of retirement-age employees by their most recent job title.  

![png](Data/retirement_titles.png)

![png](Data/unique_titles.png)

![png](Data/retiring_titles.png)

## Part 2 Summary
In the second part of the analysis, we identified current employees who were born between January 1, 1965 and December 31, 1965.  The result is a table of employees who would be eligible to be a mentor at the company.   

![png](Data/mentorship_eligibility.png)

## Results

In looking at the tables, we can draw the following conclusions:
- The Part 1 summary shows that there will likely be a huge wave of retirements over the next few years.  
- Among current employees, employees in Senior Engineer and Senior staff positions will be the most likely to retire.
- While there are several senior level positions that will be need to be filled, only 2 manager positions will need to be filled.  
- There will be approximately 1,500 employees who could potentially assume mentorship type roles.  


 
