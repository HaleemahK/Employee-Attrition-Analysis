# Introduction

This project **Employee Attrition Analysis** report is designed to help HR team analyze factors influencing employee attrition using data analysis techniques.

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

-	What is the gender, race, and age distribution of employees across different business units? 
-	Which departments have the highest concentration of employees from specific demographic groups? 
-	What is the average employee tenure based on age groups and employee classification types? 
-	What percentage of employees have exited the company over the last year? 
-	What are the top reasons for employee exits (resignation, involuntary termination, retirement)? 
-	Which job titles and pay zones have the highest turnover rates? 
-	Which departments have the highest employee attrition rates? 
-	Are certain divisions experiencing more involuntary terminations than others? 
-	What is the average tenure per job function? 

# Dataset Overview

This dataset contains **3000 employees** it captures detailed informations like gender, race, marital description,age, job function and so on making it suitable for analysis

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

# Measures (DAX)
**Description**
  Contains calculated measures created using **DAX in power Pivot** to define key KPIs and evaluate employee performance. These measures form the backbone of the dashboard, providing insights into attrition rate, retention rate, reason for turnover.
  
**Fields**
  - Total number of employees
  - Tenure
  - Attrition rate
  - Retention rate
  - Average age(yrs)

**Purpose:**
Is helps HR team develop strategies to improve retention, optimize staffing, and enhance employee satisfaction.

# Data Analysis and Visualization

The dashboard is structured into two main pages, each focusing on Workforce demographic and diversity,Employee Attrition and Retention analysis,Performance and Job function and delivering insights for HR team and the companies directors.

## Page 1: Workforce demographic and diversity, Employee Attrition and Retention analysis 

**HR Goal:**
Analyze the worforce demographic( gender,race and race distribution), and the percentage rate for Employee attrition and retention over the years.
<img width="1317" height="506" alt="Screenshot Page 1  Employee Attrition Analysis" src="https://github.com/user-attachments/assets/b60a60c5-0a1a-4391-a696-aa483376c87e" />

# Key Metrics( Top of the page): Total headcount, Active Employee, Inactive Employee, Average Age, Attrition Rate, Retention Rate.

- **Total Headcount:** This represents the total number of employees
- **Active Employees:** The total number of employees still present in the organization.
- **Inactive Employees:** The total number of employees tat has exited the organization.
- **Avearge Age:** The average age for the employees
- **Attrition rate:** The  percentage of employees that left the organization.
- **Retention rate:** The percentage of employees that stayed with the organization.

This KPIs helps the HR team and the decision makers understand the dynamic of the workfore.

-----

## Visuals

- **Gender Distribution (Pie Chart):** It represents the gender distributions( Male, Female) making it easy to indentify distribution of gender in the organization.
- **Age Distribution (Bar Chart):** It represent the age groups( Under 25, 25-34, 35-44, 45-55, Above 55) making it easy to identify  various age groups.
- **Race Distribution (Coloumn Chart):** It represents different race( Asian, White, Black, Others, Hispanic) making it easy to identify various races.
- **Age Group & Employee Classification by Average Tenure ( Clustered Bar Chart):** It represnts various age groups and the classification of employees across the averge tenure.
- **Attrition Rate ( Line Chart):** It represents the percentage of employess that exited over the years.
- **Retention Rate (Line Chart):** It represents the percentage of employees that stayed over the years.

 ## Slicers: Gender, Age Group and Year

 The dashboard includes  **Gender, Year, Age Group** slicer that allows user to fliter and interact with the data

 This interactive fliters ensures that KPIs, charts and visuals adapt instantly giving the HR team a flexible view by narrowing the focus on specific year, age groups or gender.

  ----

  # Page Two: Performance and Job function analysis

  **HR Goal:**
  Analyze the  Job Performance and Job function 

  <img width="1312" height="539" alt="image" src="https://github.com/user-attachments/assets/65b0516a-04af-4f71-97d1-3a4d6b5fe6af" />

# Key Metrics( Top of the page): Total headcount, Active Employee, Inactive Employee, Average Age, Attrition Rate, Retention Rate.

- **Total Headcount:** This represents the total number of employees
- **Active Employees:** The total number of employees still present in the organization.
- **Inactive Employees:** The total number of employees tat has exited the organization.
- **Avearge Age:** The average age for the employees
- **Attrition rate:** The  percentage of employees that left the organization.
- **Retention rate:** The percentage of employees that stayed with the organization.

This KPIs helps the HR manager and the decision makers understand the dynamic of the workfore.

------

## Visuals

- **Employee Classification By Average Tenure (Bar Chart):** This represents Employee Classification(Full-time, Part-time and Temporary) by the average of the tenure year.
- **Top Termination Type (Column Chart):** This represents the various reason in which employee exited the organization.
- **Pay Zone By Average Employee Rating (Column Chart):** This represents various payzones by the average employee rating
- **Attrition Rate By Department (Bar Chart):** This represents various departments by the attrition rates, which is in percentage.
- **Employee Classification By Avg Employee Rating (Bar Chart):** This represents Employee Classification (Full-time, Part-time and Temporary) by the average employee rating.
- **Retention Rate By Department (Column Chart):** This represents various departments by the retention rates, which is in percentage.

----

 ## Slicers: Gender, Age Group and Year

 The dashboard includes  **Gender, Year, Age Group** slicer that allows user to fliter and interact with the data

 This interactive fliters ensures that KPIs, charts and visuals adapt instantly giving the HR team a flexible view by narrowing the focus on specific year, age groups or gender.

# Key Analysis Findings

The analysis of the employee attrition provided various insights into Workforce diversity and demographic,Employee retention and attrition, Job performance and function:

## 1. Workforce diversity and demographic:

- **Total Employees-** *3,000 Employees*
- **Active Employees-** *1,467 Employees(49%)*
- **Inactive Employees-** *1,533 Employees(51%)*
- **Gender Distribution-** *Female;1,682(56%) and Male;1,318(44%)*
- **Ethnic Diversity-** Across five categories, with Asian being the highest race 629 employees
- **Retention Rate-** *48.90%*
- **Attrition Rate-** *51.10%*
- The highest average tenure among employee is between age *25-34(3.19)*
  
# Insights

- The age distribution above 55years dominates the workforce thereby enabling high risk of attrition rate.
- The younger age group below age distribution 25-34 have higher tenure rate despite being underrepresented.
- The high rate of inactive employee suggests a look into.

## 2. Employee Retention & Attrition Analysis:

- There is an increase in attrition rate across the years(2018-2023).
- There is a decrease in retention rate across the years.
- Across department the executive office has the highest attrition rate with *79%*
- IT, Production and Sales have and average retention rate ranging from *48%-50%*
- The top exit reason is Unknown.
- Top division by involuntary termination is the field operations.
  
# Insights

- Due to “Unknown” being the highest termination reason there is a gap to identify the exact reason to high attrition rate.
- The high rate of attrition in the departments may be due to workload or role clarity.

## 3. Performance & Job function:

- **Average employee rating –** *2.97*
- Performance distribution for active employee
- **High-** *12.36%*
- **Medium-** *78.84%*
- **Low-** *8.79%*
- 
**Performance by contract type and pay zone**
  
- There is a consistent rating across fulltime, parttime and temporary staff.
  
# Insights
- With Medium being the highest performance rating reflects there is room for growth.
- The job function services has the highest job tenure by 6 years.
- Software engineering leads in high performance followed by sales while Admin office has low performances rating.
- High tenure in functional roles such as services and supports shows employees stability and engagement.
  
## Recomendations:

Based on the analyis, the following recommendations can help to improve retention, optimize staffing, and enhance employee satisfaction. 

- Bring in young talents/professionals and equip them quality skills which could help increase retention and productivity.
- Ask question from various department to know where there are loopholes/challenges and work towards creating solutions to them.
- Encourage employees by giving incentive to employees which would encourage them to work harder and increase productivity.  
- Employees with low performances rating should undergo coaching and mentorship which could help them improve.
- To reduce attrition rate, there should be focus on pay, career development, work life balance and creating a positive organizational culture.

# Limitations
 
This analysis is based on a single fictional dataset which may not fully reflect real-world employee behavior, organizational complexity, or external labor market influences, so findings should be interpreted as illustrative rather than operational.
  













