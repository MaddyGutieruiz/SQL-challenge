# SQL-Challenge
## Background
It’s been two weeks since you were hired as a new data engineer at Pewlett Hackard (a fictional company). Your first major task is to do a research project about people whom the company employed during the 1980s and 1990s. All that remains of the employee database from that period are six CSV files.

For this project, you’ll design the tables to hold the data from the CSV files, import the CSV files into a SQL database, and then answer questions about the data. That is, you’ll perform data modeling, data engineering, and data analysis, respectively.

## Before You Begin
1. Create a new repository for this project called sql-challenge. Do not add this assignment to an existing repository.

2. Clone the new repository to your computer.

3. Inside your local Git repository, create a directory for this Challenge. Use a folder name that corresponds to the Challenge, such as EmployeeSQL.

4. Note that you’ll add your files to this folder and push the changes to GitHub.

## Files
Download the following files to help you get started:

Module 9 Challenge filesLinks to an external site.

## Instructions
This Challenge is divided into three parts: data modeling, data engineering, and data analysis.

## Data Modeling
Inspect the CSV files, and then sketch an Entity Relationship Diagram of the tables. To create the sketch, feel free to use a tool like QuickDBDLinks to an external site..

## Data Engineering
1. Use the provided information to create a table schema for each of the six CSV files. Be sure to do the following:

- Remember to specify the data types, primary keys, foreign keys, and other constraints.

- For the primary keys, verify that the column is unique. Otherwise, create a composite keyLinks to an external site., which takes two primary keys to uniquely identify a row.

- Be sure to create the tables in the correct order to handle the foreign keys.

2. Import each CSV file into its corresponding SQL table.

## Data Analysis
1. List the employee number, last name, first name, sex, and salary of each employee.

2. List the first name, last name, and hire date for the employees who were hired in 1986.

3. List the manager of each department along with their department number, department name, employee number, last name, and first name.

4. List the department number for each employee along with that employee’s employee number, last name, first name, and department name.

5. List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

6. List each employee in the Sales department, including their employee number, last name, and first name.

7. List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

8. List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).


## Results

### Data Modeling
![SQL_Data modeling](https://github.com/MaddyGutieruiz/SQL-challenge/blob/main/SQL_Data%20modeling.png)

Figure 1 is the sketch of the Entity Relationship Diagram of the tables using QuickDBD.

### Data Engineering

See SQL_Data_Engineering.sql file for answer.

https://github.com/MaddyGutieruiz/SQL-challenge/blob/main/SQL_Data_Engineering.sql

### Data Analysis

SQL code for the Data Analysis questions can he found here: https://github.com/MaddyGutieruiz/SQL-challenge/blob/main/SQL_Data_Analysis_Code.sql

1. List the employee number, last name, first name, sex, and salary of each employee.

    - Answers to data analysis question one can be found here: https://github.com/MaddyGutieruiz/SQL-challenge/blob/main/SQL_Data_Analysis_Q1.csv

2. List the first name, last name, and hire date for the employees who were hired in 1986.

    - Answers to data analysis question two can be found here: https://github.com/MaddyGutieruiz/SQL-challenge/blob/main/SQL_Data_Analysis_Q2.csv

3. List the manager of each department along with their department number, department name, employee number, last name, and first name.

    - Answers to data analysis question three can be found here: https://github.com/MaddyGutieruiz/SQL-challenge/blob/main/SQL_Data_Analysis_Q3.csv
    
4. List the department number for each employee along with that employee’s employee number, last name, first name, and department name.
    
    - Answers to data analysis question Four can be found here: https://github.com/MaddyGutieruiz/SQL-challenge/blob/main/SQL_Data_Analysis_Q4.csv

5. List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

    - Answers to data analysis question Five can be found here: https://github.com/MaddyGutieruiz/SQL-challenge/blob/main/SQL_Data_Analysis_Q5.csv

6. List each employee in the Sales department, including their employee number, last name, and first name.

    - Answers to data analysis question Six can be found here: https://github.com/MaddyGutieruiz/SQL-challenge/blob/main/SQL_Data_Analysis_Q6.csv

7. List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

    - Answers to data analysis question Seven can be found here: https://github.com/MaddyGutieruiz/SQL-challenge/blob/main/SQL_Data_Analysis_Q7.csv

8. List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

    - Answers to data analysis question Eight can be found here: https://github.com/MaddyGutieruiz/SQL-challenge/blob/main/SQL_Data_Analysis_Q8.csv
        
