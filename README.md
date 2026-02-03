# Introduction

This project **Employee Attrition Analysis** report is designed to help HR analyze factors influencing employee attrition using data analysis techniques.

The report explores:
- Workforce Demographics & Diversity
- Employee Retention & Attrition
- Job Performance & Job function

It purpose is to uncover insights in Employee Retention and Workforce Optimization Problem


# Problem Statement
The company is experiencing workforce attrition, with employees leaving due to resignations, retirements, and involuntary terminations. HR needs to analyse key factors affecting employee retention and workforce stability. By understanding trends in employee tenure, termination reasons, performance ratings, and pay zones, HR can develop strategies to improve retention, optimize staffing, and enhance employee satisfaction. 

This project addresses this challenges by transforming raw retail transaction records into meaningful insights through the use of **Excel** and **Power Query**, the analysis highlights workforce demograpics, diversity, employee retention, employee attrition, Job performance and job function.

# Key Posing Business Questions

To maximize strategic values, this analysis was framed from the perspective of Human resource managers.

•	What is the gender, race, and age distribution of employees across different business units? 
•	Which departments have the highest concentration of employees from specific demographic groups? 
•	What is the average employee tenure based on age groups and employee classification types? 
•	What percentage of employees have exited the company over the last year? 
•	What are the top reasons for employee exits (resignation, involuntary termination, retirement)? 
•	Which job titles and pay zones have the highest turnover rates? 
•	Which departments have the highest employee attrition rates? 
•	Are certain divisions experiencing more involuntary terminations than others? 
•	What is the average tenure per job function? 

# Dataset Overview

This dataset contains **3000 employees details** it captures detailed informations like gender, race, marital description,age, job function and so on making it suitable for analysis

- **Employee ID** -Unique identifer for each employee
- **Full name** - Name of employee
- **Start date** - The date the employee started working in the company
- **Exit date** - The date the employee exited the company
- **Job Title**- The title of the job role
- **Business unit** - The bussiness unit in the the job title falls in
- **Employee status** - The status of the employee (e.g Active,Terminated,Exit)
- **Employee type** - This shows if the employee is a full-time, part-time or temporary type
- **Job description** - The job role
- **Gender** - Specific gender of each employee
- **Race** - The ethnical race of each employee
- **Marital desciption** - The marital status of each employee

# Data Preparation
To ensure accuracy and usuability, the dataset undewent a series of **cleaning and tranformation steps** before analysis. This process was carried into **Excel** and **Power Query** focusing on recovering inconsistencies, deriving new fields and preparing the data for visualization.

### Key Steps taken
- Extracted date component(Year)
- Created columns to identify years in which employees were active( from the year 2018 to date)
- Calculated key measures(KPIs) including Attrition rate, Retention rate, Age and Tenure
- Created a column to identify Employee status, grouping them into Active, Terminated, Exit.
- Created a column to group the age distribution
- Created a column to calculate the age from the DOB column given
- Created a column to group performance rating.
- Loaded the cleaned dataset into **Excel** for pivot chart modeling.

  #Measures (DAX)
**Description**
  Contains calculated measures created using ** DAX in power Pivot** to define key KPIs and evaluate employee performance. These measures form the backbone of the dashboard, providing insights into attrition rate, retention rate, reason for turnover.
  
**Fields**
  - Total number of employees
  - Tenure
  - Attrition rate
  - Retention rate
  - Average age(yrs)

**Purpose:**
Is helps HR develop strategies to improve retention, optimize staffing, and enhance employee satisfaction.

#Data Analysis and Visualization

The dashboard is structured into two main pages, each focusing on Workforce demographic and diversity,Employee Attrition and Retention analysis,Performance and Job function and delivering insights for HR managers and the companies directors.

## Page 1: Workforce demographic and diversity, Employee Attrition and Retention analysis 

**HR Goal:**
Analyze the worforce demographic( gender,race and race distribution), and the percentage rate for Employee attrition and retention over the years.
<img width="1317" height="506" alt="Screenshot Page 1  Employee Attrition Analysis" src="https://github.com/user-attachments/assets/b60a60c5-0a1a-4391-a696-aa483376c87e" />



