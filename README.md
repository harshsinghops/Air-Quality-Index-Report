# Air Quality Index Report

https://app.powerbi.com/reportEmbed?reportId=1072b14d-6bca-48d5-a3e0-fe3da48c12f7&autoAuth=true&ctid=0ee9b5f9-52b3-4351-8198-c4804cd66b68
## Overview
This Power BI report is created to illustrate the air quality of cities based on various parameters, highlighting the most and least polluted cities.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under 'Data' preview section, check "Column Distribution", "Column Quality" & "Column Profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : Removed the 'Source Name' column as it was unnecessary.
- Step 5 : Applied the 'Use First Row as Headers' setting.
- Step 6 : Used the 'Remove Blank Values' option by selecting all columns.

- Step 7 : Created a page in the report view with the details mentioned below:

  (a) Inserted a 'Text Box' to create the heading for the report titled "Air Qualty Report".
  
  (b) Inserted a 'Donut Chart' using 'City' and the 'Average of AQI' metrics. Applied a 'Top N' filter to the visual.

  (c) Created multiple cards to showcase the averages of PM2.5, NO2, CO, and SO2.

  (d) Created a 'Map' using 'City' and the 'Average of AQI'.

  (e) Used a 'Stacked Bar Chart' with 'City' and 'Average of AQI' to showcase the least polluted cities.

  (f) Inserted a 'Line Chart' using 'Date' and 'Average of AQI' to showcase the AQI trend.

  (g) Created a 'City' based 'Slicer'.
  
Snapshot of the report :

![Image](https://github.com/user-attachments/assets/201338a8-8d10-4594-8102-c68affb9ddc7)

 - Step 8 : The report was then published to Power BI Service.

Snapshot of the Dashboard :
 
![Image](https://github.com/user-attachments/assets/2eeca477-4484-4d5d-bb8d-f6c561bf8151)
