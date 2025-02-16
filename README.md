
## Hospital Emergency Room Analysis

### Table of Contents  

[Project Overview](#1) 

[Data](#2) 

[Business Case](#3) 


[ Visualization](#5) 

[Key Insights](#6) 

[Summary of Visualizations & Key Findings](#7)

[Recommandations](#8)

<a name="1"/>
<a name="2"/>
<a name="3"/>

<a name="5"/>
<a name="6"/>
<a name="7"/>
<a name="8"/>

## Project Overview
In this project,  we will be examining the efficiency and effectiveness of a hospital emergency room. 
The  goal is to enhance the quality of care provided in the emergency room and ensure that patients receive timely and appropriate treatment.
## Data 

The dataset used in this project is available for download [[here](https://docs.google.com/spreadsheets/d/1neSPTn65RZVu2Bi5b0ljJaOJMqq5O_k_XgjYR2A2YXw/edit?gid=0#gid=0)].

The dataset contains 9,216 entries and 11 columns. Below is a breakdown of its structure:

Columns and Data Types

 - date (object) - Timestamp of ER visit.
   
  - patient_id (object) - Unique patient identifier.
    
  - patient_gender (object) - Gender of the patient (M/F).
  
 - patient_age (int64) - Age of the patient.
 
 - patient_sat_score (float64) - Satisfaction score (missing for many entries).
 
 - patient_first_inital (object) - First initial of the patient’s name.
 
 - patient_last_name (object) - Last name of the patient.
 
 - patient_race (object) - Race of the patient.
 
 - patient_admin_flag (bool) - Whether the patient was admitted (True/False).
 
 - patient_waittime (int64) - Time spent waiting in minutes.
 
 - department_referral (object) - Department the patient was referred to.
  

## Business Case

A summary of essential metrics:

 -  Average Wait Time (Overall): 
   
  - Median Wait Time
    
 -  Longest & Shortest Wait Time  
   
 -  Percentage of Patients Admitted by department
   
 -  Satisfaction Score vs. Wait Times

## Visualization

The dashboard avalaible [here](https://public.tableau.com/app/profile/ines.mbonda/viz/HospitalEmergencyRoomDashboard_17396810521090/Dashboard1) include the following key visualizations and metrics to monitor ER wait times.

 - Key performance Indicators (Avg. wait time per minute)

 - Wait time distribution 

 - Wait time by weekday

 - Satisfaction vs. wait time 

## Key Insights

The Emergency room had 9,216 patients visits and the overall Average Satisfaction Score was 5.47 out of 10. 
During patient visits, the waiting time before a patient could see a practitioner was 35 minutes on average.

ER wait time dashboard can help hospitals:

 - Reduce congestion

 - Improve patient satisfaction

 - Optimize staffing levels

 - Provide data-driven decision-making

## Summary of Visualizations &  Findings

1. **Wait Time per weekday ** 

Displays how patient wait times are spread across weekday.

🔍  The histogram is skewed right, a large portion of patients experience long wait times.

2. **Wait Time by Department ** 

Compares wait times across different departments.

🔍 Certain departments have significantly longer wait times than others.

3. **Wait Time Trend Over Time (Line Chart)** 

Shows daily trends in wait times over time.

🔍 Increasing trends indicate growing patient load or operational issues.

4. **Satisfaction vs. Wait Time ** 

🔍 satisfaction decreases as wait time increases, it emphasizes the need for improvements.

## Recommandations

✅   Departments with high wait times should be optimized.

 ✅  Identifying peak wait time trends can help with staffing adjustments.

✅  Improving long wait times could enhance patient satisfaction.
