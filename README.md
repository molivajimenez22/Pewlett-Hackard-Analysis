# Pewlett Hackard Analysis

## Overview of the Analysis
Pewlett Hackard is a large company with several thousand employees. As baby bloomers start retiring, PH is preparing to administer retirement packages to eligible employees and planning recruitment for positions that will need to be filled in the near future.

For this analysis, we had six CSV files to review and combine using SQL- relational databases (PostgressSQL). The results provided PH with the informatio needed to plan accordingly.

## Results

There are 3 key datapoints highlighted below:

1. Number of Employees Retiring by Title
2. Forecast of the types of roles PH will need to hire in the near future
3. List of Employees Eligible for the Mentorship Program

### Employees Retiring by Title

#### Employees Retiring by Title
The first step was to compile a list of employees who are eligible for retirement. This was done by filtering the data to employees born between January 1952 to December 1955
<p align="center" width="100%">
    <img width="66%" src="https://github.com/molivajimenez22/Pewlett-Hackard-Analysis/blob/main/Resources/Retiring_emp_by_title.png">

 [Complete Raw Data - Employees Retiring by Title](https://github.com/molivajimenez22/Pewlett-Hackard-Analysis/blob/main/Data/retirement_titles.csv)
 
 #### Employees Retiring by Title (no duplicates)
  
 <p align="center" width="100%">
    <img width="66%" src="https://github.com/molivajimenez22/Pewlett-Hackard-Analysis/blob/main/Resources/Unique_Titles.png">
   
  [Complete Raw Data - Employees Retirning by Title (no duplicates)](https://github.com/molivajimenez22/Pewlett-Hackard-Analysis/blob/main/Data/unique_titles.csv)

#### Title and Count of those retiring 
   
 <p align="center" width="100%">
    <img width="40%" src="https://github.com/molivajimenez22/Pewlett-Hackard-Analysis/blob/main/Resources/retiring_titles.png">
   
#### Resources

[Entity Relationship Diagrams (ERDs)](https://github.com/molivajimenez22/Pewlett-Hackard-Analysis/blob/main/Resources/EmployeeDB.png) - an ERD captured primary keys, foreign keys and data types for each column. Having an ERD map out the data made it easier when creating the same tables in the database. 
     
[Database Schemas (Tables)](https://github.com/molivajimenez22/Pewlett-Hackard-Analysis/blob/main/Resources/schema.sql) - this is the reference code used to create tables in the database.
     
[Database Queries](https://github.com/molivajimenez22/Pewlett-Hackard-Analysis/blob/main/Queries/queries.sql) - this is the reference code used to combine, count, test the database.
