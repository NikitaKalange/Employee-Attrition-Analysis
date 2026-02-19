# Employee-Attrition-Analysis

Project Overview - 
This project focuses on analyzing employee attrition data using Microsoft Excel.

Dataset Information - 
The dataset includes employee-related details such as:
Employee Number, Department, Job Role, Gender, Age, CF_age band, YearsAtCompany, Performance Rating, Job Satisfaction, CF_current Employee (1 = Current, 0 = Ex-Employee)
From this dataset, I created a derived column:
Attrition_Flag
(1 = Ex-Employee, 0 = Current Employee)

Steps Performed in This Project - 

1. Data Transformation
  Created Attrition_Flag column from CF_current Employee
  Created Tenure_Group using YearsAtCompany
2. KPI Calculation
  Total Employees
  Total Attrition
  Attrition Rate %
3. Pivot Table Analysis
  Created pivot tables to analyze attrition by:
    Department, Job Role, Age Band, Gender, Tenure Group, Job Satisfaction
4. Dashboard Creation
   Built an Excel dashboard with:
     KPI Cards
     Bar Charts
     Column Charts
     Pie Chart

Dashboard Overview

The dashboard includes:
  Total Employees: 2925
  Total Attrition: 473
  Attrition Rate: 16.17%


Key Analysis & Insights - 

--> The organization has an attrition rate of 16.17%										
---> The R&D department has the highest number of exits(264), followed by Sales dept(185) , significantly contributing 										
to overall attrition.										
--> Employees in the 25-34 age group show the highest attrition, indicating early to mid career professionals are more 										
likely to leave.										
--> Employees with 1-3 years of tenure have the highest number(214) of attrition that means employees are leaving										
after initial experience gain.										
--> Employees with job satisfaction rating of 3 show the highest number of exits (144), followed by those  										
with a rating of 1.										
