# Google Data Analytics Capstone
## Emergency Resource Allocation Analysis & Dashboard Creation: Completed as a Case Study for the Google Data Analytics Capstone

### Summary
Hospital administrators need to monitor ICU & inpatient occupancy, and emergency department (ED) traffic, to ensure adequate resource allocation and timely responses to surges in patient volume. The goal of this analysis is to create a dashboard that helps identify critical capacity issues by hospital and region. The data analyst is completing this business task and objective as part of a portfolio project and the Google Data Analytics Capstone. The imaginary hospital system's name is Regional Cidade Hospital for future reference.

### Insights
* Some hospitals report ICU occupancy consistently over 100%, pointing to either chronic capacity issues or underreported bed availability
* ED visits vary significantly by hospital, with some facilities handling high volumes regularly
* Time-based occupancy trends suggest periods of increased strain — potentially tied to seasonal or regional health events
* Mapping hospitals provides a geographic lens to identify clusters of high demand  


## Case Study

#### Ask  
***Business Task (Deliverable):***  
Hospital administrators need to monitor ICU & inpatient occupancy, and emergency department (ED) traffic, to ensure adequate resource allocation and timely responses to surges in patient volume. The goal of this analysis is to create a dashboard that helps identify critical capacity issues by hospital and region.

***Key Stakeholders:***
* Hospital Administrators
* Various Department Heads
* Emergency Dept Head
* Intensive Care Unit Head
* Operating Room Head
* Inpatient Care Dept Head

#### Prepare    
***Data Source Description (Deliverable):***  
You are a junior data analyst in the beginning days of your probationary period. For your first task/project, the hospital system requires you to use external data to complete the analysis. A public dataset from the website HealthData.gov provided by the US Dept. of Health & Human Services. This large dataset contains data for the hospital system you’re working for. The dataset will be filtered for all hospitals in the Ascension system and used as the imaginary system Regional Cidade Hospital system.

The dataset was downloaded/accessed as a csv file and cleaned with R. from the cleaned dataset, a new csv file was written in R and exported to Tableau for further analysis and presentation of findings— dashboard creation.

Public Dataset:
HealthData.gov’s COVID-19 Reported Patient Impact and Hospital Capacity by Facility — RAW 
Last Updated July 3, 2025
Provided by: US Dept of Health & Human Services
Cleaned and manipulated in R script and written to new csv file (rgn_cidade_data.csv)

#### Process  
***Documentation of Data Manipulation (Deliverable):***
Documentation of Data Manipulation:
* Dataset cleaned in R, null values removed, columns created and removed, occupancy rate calculation.
* new csv file written from cleaned / analyzed dataset.
* full dcoumentation of cleaning/manipulation perfomed and documented in R script with comments

#### Analyze  
***Summary of Analysis (Deliverable):***  
Using public hospital-reported data from the U.S. Department of Health & Human Services, I cleaned and analyzed hospital occupancy and ED visit data using R and Tableau. I developed an interactive dashboard that allows users to:
* Monitor average ICU and Inpatient occupancy rates
* Explore ED visit patterns across the country
* Identify overburdened hospitals over time
* Filter trends and KPIs by individual hospital for deeper exploration

The dashboard assists with quick situational awareness for healthcare industry decision-makers by combining geographic mapping, trend lines, and valuable key metrics.

#### Share  
***Tableau Dashboard Created (Deliverable):***  
  Notes for Presentation:
  * some hospitals consistently report ICU occupancy > 100%
    * suggests chronic overcapacity or data reporting issues
    * facilities likely experiencing operational strain
    * urgent attention and/or resource reallocation
  * ED visits vary much by hospital
    * useful for initial look into ed strain
    * further searching necessary
    * look for clusters of red, find regions with possible strain
  * occupancy data suggests periods of increased strain (duh)
    * many reasons: health pandemic/endemics, or local/regional health events
  * inpatient occupancy data was partially cleaned for high volume of null values
    * some hospitals and time periods may still be underrepresented
    * limited reliability
      * long-term trend analysis
      * hospital-to-hospital comparisons

#### Act  
***Top-Level Insights from Analysis:*** 
* Some hospitals report ICU occupancy consistently over 100%, pointing to either chronic capacity issues or underreported bed availability
* ED visits vary significantly by hospital, with some facilities handling high volumes regularly
* Time-based occupancy trends suggest periods of increased strain — potentially tied to seasonal or regional health events
* Mapping hospitals provides a geographic lens to identify clusters of high demand  
***Limitations:***  
* Incomplete or null inpatient occupancy data in many rows may affect long-term accuracy  
***Additional Deliverables for Further Exploration:***
* A forecasting model: historical occupancy -> predictive analysis -> upcoming surges (by hospital)
* real-time monitoring: connect to live organization / internal data to dynamically update data and get live insights
