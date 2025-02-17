
## Hospital Emergency Room Analysis

### Table of Contents  

[Project Overview](#1) 

[Data](#2) 

[ Visualization](#5) 

[Key Insights](#6) 


[Recommandations](#8)

<a name="1"/>
<a name="2"/>


<a name="5"/>
<a name="6"/>

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
  


Data is cleaned and a calculated field is defined in order to group patients accross different groups as ‘0–18,’ ‘19–30,’ ‘31–65,’  and ’66 and above.’

## Visualization

The following Emergency Room wait time dashboard avalaible  [here](https://public.tableau.com/app/profile/ines.mbonda/viz/HospitalEmergencyRoomDashboard_17396810521090/Dashboard1) is important to monitor ER wait times in order to:

 - Reduce congestion

 - Improve patient satisfaction

 - Optimize staffing levels

 - Provide data-driven decision-making


![Alt text](Dahboard1.png)


Below is an overview of essential components of the dashboard:

1. **Total Number of Patients**: This metric indicates the overall patient volume within the ER over a specified period. This important in resource planning and identifying trends.

2. **Patient Demographics**:

     - **Gender Distribution**: Visualizing the proportion of male, female, and non-conforming gender patients aids in tailoring patient care services appropriately.

     -  **Age Distribution**: Categorizing patients into age groups (e.g., 0–18, 19–30, 31–65, 66 and above) provides insights into the predominant age brackets utilizing ER services.
   -    **Age Distribution**: Categorizing patients into age groups (e.g., 0–18, 19–30, 31–65, 66 and above) provides insights into the predominant age brackets utilizing ER services.

  -   **Race/Ethnicity**: The racial and ethnic composition of patients can inform culturally competent care practices.

3. **Average Patient Wait Time**: Monitoring the average duration patients spend waiting before receiving care is crucial for assessing the efficiency of the ER.

4. **Patient Satisfaction Scores**: analyzing satisfaction ratings (on a scale of 0–10) helps gauge the quality of care from the patient's perspective. Identifying periods with lower satisfaction can prompt targeted improvements.

6. **Wait Time Analysis by Weekday and Hour**: Utilizing heatmaps to display average wait times across different days and hours can highlight peak periods.

7. **Patient Volume by Department Referral**: Analyzing which departments most frequently refer patients to the ER can identify areas with higher demand.

8. **Trends Over Time**: trends in patient visits, wait times, and satisfaction scores can reveal patterns, such as seasonal fluctuations or the impact of specific interventions.

9. **Key Performance Indicators (KPIs)**: Incorporating KPIs like the total number of patients, average wait time, and average satisfaction score into the dashboard provides a quick snapshot of ER performance.


## Key Insights

🔍 The Emergency room had 9,216 patients visits and the overall Average Satisfaction Score was 5.47 out of 10. 

🔍 During patient visits, the waiting time before a patient could see a practitioner was 35 minutes on average.

🔍 General Practice has the highest number of referrals (1,840), while the Renal department has the lowest (86)

🔍 The white race visited the hospital more which further indicate that the male gender visited the hospital more often.

## Recommandations

✅ Resource Allocation: Deploy additional staff during identified peak hours and days to reduce wait times and prevent staff burnout.

✅Process Improvement: Streamline workflows in departments with high referral rates to enhance patient throughput.

✅ Patient Experience Initiatives: Improving long wait times could enhance patient satisfaction.
