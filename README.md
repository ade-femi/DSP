## HR Analytics Power BI Portfolio Project

## Project Overview

This data analysis and visualisation project based on hyptothetical scenario initiated by the HR department. The goal is to identify and gain insights into individuals with good health and low absenteeism for potential inclusion in a Healthy Bonus program.

A HR dataset that includes tables with absentee data, compensation details, and reasons for absence was utilised. The dataset covers information for 740 employees, providing insights into the reasons, duration, and frequency of their absences. It also includes various demographic, socio-economic, and health-related features, such as age, gender, education, marital status, children, pets, BMI, smoking, and drinking habits.

SQL is used to perform data manipulation and analysis tasks, creating database off joining employee data, absentee reasons and compensation tables and filtering for healthy workers and optimising queries. The project used Power BI to create a dashboard that shows various metrics and charts related to absenteeism, such as average hours absent, number of absentees, absenteeism by social drinkers, absenteeism by social smokers, absenteeism by BMI category, and absenteeism by month and day of the week. 

## Project Implementation
A database to store absenteeism data is created using SQL by joining uploaded CSV files of absentee data, reason for absence and compensation information. Healthy workers with low absenteeism, low BMI and are non-smokers were filtered using SQL queries. SQL queries were optimised by using indexes, subqueries, and CASE statment to improve the performance and readability of the queries. Power BI was connected to the database and the absenteeism data and SQL queries was imported to develop a dashboard for HR to understand absenteeism at work. 


## Project Dashboard
The project dashboard shows the following metrics and charts related to absenteeism at work:

**Average Hours Absent:** The average number of hours absent per employee.

**Total Hours Absent:** The total number of hours absent for all employees.

**Number of Absentees:** The number of employees who were absent at least once.

**Employee ID Dropdown Slicer:** A slicer that allows the user to filter the dashboard by employee ID.

**Doughnut Pie Chart Showing Absenteeism by Social Smoker:** A doughnut pie chart that shows the percentage of absenteeism by social smoker status.

**Doughnut Pie Chart Showing Absenteeism by Social Drinker:** A doughnut pie chart that shows the percentage of absenteeism by social drinker status.

**Doughnut Pie Chart Showing Absenteeism by BMI Category:** A doughnut pie chart that shows the percentage of absenteeism by BMI category (healthy, overweight, or obese).

**Doughnut Pie Chart Showing Absenteeism by No of Children:** A doughnut pie chart that shows the percentage of absenteeism by the number of children (0, 1, 2, 3, or 4).

**Line Chart Showing Sum of Absenteeism in Hours by Month Absent:** A line chart that shows the sum of absenteeism in hours by the month of absence (January to December).

**Line Chart Showing Sum of Absenteeism by Day of the Week:** A line chart that shows the sum of absenteeism by the day of the week (Monday to Friday).

**Filter of Seasons: Fall, Spring, Summer, Winter:** A filter that allows the user to filter the dashboard by the season of absence (fall, spring, summer, or winter).

**Plot of Average Transportation Expense by Work Load Average Day:** A scatter plot that shows the relationship between the average transportation expense and the workload average day for each employee.

**Slicer of Absentee Reasons:** A slicer that allows the user to filter the dashboard by the reason for absence.

**Narrative of the Whole Dashboard:** A Power Bi narrative feature that uses NLP to summarise the main findings and insights from the dashboard.

## Project Conclusion
This project demonstrates the use of Power BI and SQL for data analysis and visualisation of absenteeism at work. The project provides insights into the factors and patterns that influence absenteeism, such as social smokers, social drinkers, BMI category, number of children, month, day, season, and reason for absence. The project also provides solutions for the HR department to select healthy workers for their health program and to calculate wage increases for non-smokers. The project shows the effectiveness of Power BI and SQL in creating a dashboard that is interactive, informative, and user-friendly.
