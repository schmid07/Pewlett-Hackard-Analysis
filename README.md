# Employees Analysis -- Overview
We've been tasked with determining the number of retiring employees per title and identifying employees who are eligible to participate in a mentorship program.  

## Resources
- Data Source: employees.csv; titles.csv; dept_emp.csv; 
- Software: SQL; PostgreSQL

## Summary
As shown in the table below, among our sample collected, both the average fare per ride and average fare per driver were less in Urban areas and most in Rural areas.  There is no adjustment for miles traveled in the data, so one possible explanation is that trip distance is lower in Urban areas, which would lead to a lower fare per ride.  

![png](Data/retirement_titles.png)

![png](Data/mentorship_eligibility.png)

## Recommendations
To address disparities in fares between rides, one recommendation is to charge different rates between Urban, Suburban, and Rural areas.  Another recommendation is to add an upfront fee that is contigent on the type of area.  A final recommendation is to tie rates to miles traveled so that the first mile is the most expensive, and gradually declines as vehicle miles increase.    
