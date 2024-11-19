# Hospital-Emergency-Room-Visits-Dashboard

# Overview
This project provides a data analysis dashboard designed to offer insights into patient visits to the Emergency Room (ER). The dashboard includes interactive visualizations, time-based trends, and key metrics that help healthcare providers understand patient flow, patient satisfaction, demographics, referral patterns, and more. It is built using Power BI (or any other BI tool you used for visualization) and incorporates various measures to track the hospital's ER performance and operational efficiency.

# Key Features
1. Date Table and Time-Based Analysis
                                                                                                                              
      Date Column Creation: A date table is created using CALENDARAUTO() to provide a dynamic range for date-based analysis. 

      Additional time-related columns: Date, Month, MonthName, WeekType, and other time-related dimensions for comprehensive trend analysis.                                                

2.Key Metrics 

      Total Patient Visits: Measure showing the total count of ER visits for any selected time period.
                                                      
      Gender Breakdown: Displays the percentage of Male and Female patients visiting the ER.             

      Patient Satisfaction: Shows the average Satisfaction Rate (based on survey or feedback data).    

      Satisfaction and Non-Satisfaction Rate: Measures the percentage of patients satisfied and unsatisfied with the ER service.   

      Referral Breakdown: Indicates the percentage of patients who were referred vs. non-referred to the ER.       

      Staff Type Distribution: Breakdown of patients based on administration staff vs non-administration staff.                                          

3. Visualizations
                                                                                           
      Area Chart: Displays the monthly distribution of visits, with top visits recorded in August. 

      Line Chart: Visualizes year-wise visits to show trends over time.            

      Bar Chart: Displays age group distribution of patients visiting the ER.   

      Referral Distribution: Shows the total patients by department referral.   

      Column Chart: Analyzes the weektype distribution (e.g., weekdays vs weekends) of ER visits.                                                                      

4. Key Performance Indicators (KPIs)
                                                               
      Average Satisfaction Rate: A card showing the average satisfaction from patient feedback.

      Average Waiting Time: A card showing the average wait time in the ER.                

      Service Not Rated: A card indicating the percentage of patients whose satisfaction or service rating is not available.                                           

# Insights                                               
Based on the dashboard’s visualizations and measures, several key insights can be drawn:                                                            
                                                                                                                             
Monthly Visits:                                                                                                                                 
The month of August records the highest number of ER visits, as shown in the area chart. 

Year-wise Trends:                                                                                                                                            
  The line chart reveals a general increase or decrease in ER visits over the years, helping identify seasonal or long-term trends.    

Gender Breakdown:                                                                                                                                      
  The percentage of male and female patients can be observed, allowing you to identify if there are significant gender-based differences in ER visits.   

Age Group Distribution:                                                                                                                                                        
  The bar chart for age groups shows which age demographic is visiting the ER the most, which is useful for understanding which groups may need additional healthcare resources or outreach.

Referral Patterns:                                                                                                              
  The percentage of referred vs non-referred patients provides insights into whether the ER is being utilized for emergencies or for cases that could have been addressed in other care settings.

Patient Satisfaction:                                                                                                                                                
  The average satisfaction rate and the satisfaction vs non-satisfaction rates help assess the quality of service provided in the ER.      

Waiting Times:                                                                                                                                                                  
  The average waiting time card can help highlight potential issues related to ER efficiency, especially during peak times (e.g., weekends or certain months). 
  
Staff Distribution:                                                                    
  The breakdown of administrative staff vs non-administrative staff helps track the involvement of staff types in the ER and their potential impact on patient care.                              

# Tools and Technologies Used
Power BI Desktop                                                                                                                                          
DAX                                                                                                                                 
Power Query for data cleaning and transformation                                                                                                                                          

# Usage
The dashboard includes interactive slicers that allow you to filter the data by time (month, year, week), gender, referral status, and more.
Hover over the charts and visuals to see tooltips with additional information.
Use the line chart to observe trends in ER visits over the years.
The age group bar chart allows you to drill into different patient demographics.
Cards display key performance indicators like average satisfaction, average wait time, and service not rated.
