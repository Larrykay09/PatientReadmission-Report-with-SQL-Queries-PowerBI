# PatientReadmission-Report-with-SQL-Queries-PowerBI
## Overview
The repository contains sql queries and power BI documentation for analyzing patient readmission rate dataset. The dataset includes information about patient diagnosis, length of stay days, chronic conditions, discharge type, medication count, follow up scheduled, insurance type, readmitted within 30 days and risk score.

## Project Objectives

The primary goal of this project is to reduce 30-day patient readmission rates, optimize hospital resources, and lower operational costs. 

As a Data Analyst, my specific objectives are to:
* **Analyze Patient Data:** Explore and clean historical patient datasets to uncover trends and patterns.
* **Identify Risk Factors:** Determine the key drivers and characteristics that put patients at a high risk of readmission.
* **Develop Predictive Insights:** Highlight the specific patient segments that require the most attention.
* **Provide Actionable Recommendations:** Deliver data-driven insights to help healthcare providers implement proactive post-discharge intervention strategies.

 ## Data Source
  The dataset was provided by mentor during mentorship program

## Preparation Tools
* Microsoft SQL: Database, Table, Queries
* PowerBI: Dashboard Creation, Report

## Files
- **Dataset.xlsx:** Raw dataset used to build database and PowerBI dashboard.
- **SQL_queries.sql:** Contains SQL queries used to analyze the dataset and answer specific business questions.
- **PowerBI_dashboard.pbx:** contains interactive dashboard to answer business questions.
- **README.md:** This file, provides an overview of the repository and instructions for accessing and using SQL queries and powerBI interactive dashboard.

  Click 👉🏼 [here](https://drive.google.com/drive/folders/1rd2MU_z4Fbi7TqcofVHmacXj9wOgAkSe?usp=sharing) 👈🏼 to see these files

  ## SQL Queries:
  
1. Which diagnosis has the highest 30-day readmission rate?
    - Query to find the diagnosis that has the highest rate of readmission.
2. How does the length of stay affect the likelihood of readmission?
    - Query to find the length of stay that affects the likelihood of readmission.
3. Which patient characteristics are most associated with readmission?
    - Query to find the characteristics most associated with readmission.
4. Does scheduling follow-up appointments reduce readmission rates?
    - Query to find if scheduled follow-up appointments reduce the rate of readmission.
5. Which patient groups should be prioritized for proactive intervention before discharge?
    - Query to find which patient groups need to be prioritized for proactive intervention before discharge.

 
  ## Instructions

   Clone or download this repository to your local machine.
  
   Open the SQL_Queries.sql file to view the SQL queries.
  
  Execute the SQL queries in your preferred SQL database management system (e.g, MSSQL, MYSQL Workbench, SQLite).

  Review the results and analysis provided by each query.

  Open the PowerBI.pbx to view the dashboard

  ## Insights
  * 381 (76.2%) are classified as high-risk patients.

* Average length of stay is 10.62 days.

* Patients had an average risk score of 73.92.

* The average number of prior visits is 5.21.

* The 30-day readmission rate is 67.4%.

* The follow-up compliance rate shows that 48.4% of patients had scheduled follow-up appointments compared with 51.6% who did not.

* Analysis by age group revealed that patients aged around 10 years and 90 years had comparatively lower readmission rates.

* Patients with a greater number of chronic conditions generally experienced higher readmission rates.

* Kidney disease was identified as the leading diagnosis associated with readmissions, followed by Pneumonia.

## Recommedations
* Implement targeted care management programs for high-risk patients, particularly the 381 patients identified as high risk.

* Strengthen discharge planning by introducing standardized discharge protocols, medication reconciliation, and patient education before discharge.

* Improve follow-up compliance by ensuring that follow-up appointments are scheduled before patients leave the hospital and by implementing reminder systems.

* Develop specialized intervention programs for patients diagnosed with kidney disease and pneumonia, as these conditions contribute most significantly to readmissions.

* Introduce case management and transitional care programs for patients with multiple chronic conditions to reduce the likelihood of recurrent admissions.

* Conduct further investigation into the factors driving readmissions among patients with fewer chronic conditions, as their elevated readmission rates suggest the presence of additional risk factors not captured in the current analysis.

  ## Dashboard
  <img width="623" height="329" alt="image" src="https://github.com/user-attachments/assets/ed34f49d-1c71-4bf0-82e3-c68a668a3d16" />


  ## Author

  [Kabiru Ewuola](https://www.linkedin.com/in/kabiruewuola/)
  
  Email: ewuolakabiru@gmail.com
      
