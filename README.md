# Pewlett-Hackard-Analysis

## Project Overview:

The goal of this project was to help Pewlett Hackard, a company that has been around for a long time, to assess what employees are approaching retirement along with assessing what positions will be opening in the next few years. In this challenge I helped to determine the number of retiring employess by title along with determing the number of employees that were eligible for the mentorship program that Pewlett Hackard is launching. The criteria that we used to determine who was retiring shortly was based upon birth date years that ranged from 1952 - 1955.

## Resources:

**Data Sources (Folders):** [Data](https://github.com/matthubb17/Pewlett-Hackard-Analysis/tree/main/Data)

**Challenge File:** [Challenge File](https://github.com/matthubb17/Pewlett-Hackard-Analysis/blob/main/Queries/Employee_Database_challenge.sql)

**Software:** Python 3.9.7, SQL, PostgreSQL, pgAdmin4

## Results:

  - As we can see from the chart below, there is a large number of employees that are eligable for retirement. We can see that over 32,000 staff are eligable along with over 8,000 senior staff.

![Retiring Titles Screenshot](https://github.com/matthubb17/Pewlett-Hackard-Analysis/blob/main/Data/Retiring%20Titles%20Screenshot.png)

  - In addition to the staff and senior staff, we also can see that Pewlett Hackard is also going to see over 29,000 senior engineers and over 14,000 engineers.
  - Pewlett Hackard will want to focus on relacing this large percentage of their workforce in the coming years.
  - By focusing on all of these positions that will be opening, Pewlett Hackard will avoid not being prepared for this large turnover in employees.

## Summary:

  - How many roles will need to be filled as the "silver tsunami" begins to make an impact?
    -  Looking at the [retiring_titles](https://github.com/matthubb17/Pewlett-Hackard-Analysis/blob/main/Data/retiring_titles.csv) csv there will be over 72,000 positions that will become available within the next couple of years.

  - Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
    - No there is not enough retirement ready employees to participate in the mentorship program. When looking at the [mentorship_eligibility](https://github.com/matthubb17/Pewlett-Hackard-Analysis/blob/main/Data/mentorship_eligibilty.csv) csv we can see that we only have over 1,500 employees that are eligable.

- Recommended additional queries or tables:
  - I would recommend that Pewlett Hackard dig a bit deeper into the retirement_titles chart that we created. One way that they could get some more information would be to include additional columns within the table such as adding the departments that the titles fall under for more clarity when assessing the postions.
  - I would also recommend that the company consider what postions are the most important to their continued success. By adding a column that represents how senior a position is it will help the recruiting team to prioritize the most important positions.


