# HR Analytics Dashboard

Welcome to the HR Analytics Dashboard project! This repository showcases an interactive Power BI dashboard designed to help organizations better understand employee attrition, workforce demographics, and related HR trends.


## Problem Statement

Employee attrition is one of the biggest challenges for HR departments. Understanding **who is leaving, why, and from where** is key to improving employee retention and satisfaction.

The goal of this dashboard is to:
- Analyze attrition patterns across demographics, departments, and salary brackets
- Provide a high-level and granular view of workforce composition
- Support data-driven HR decisions for talent retention


## Demo of the dashboard:

### Level 1: 
Slicers and date filters are given using which we can filter the visuals based on

	- Department
	- Gender	

### Level 2: 
Card visuals, column charts, pie charts, and line charts are used to show detailed trends.

##### 6 card visuals shows

	-Count of Employee
	-Attrition
	-Attrition Rate
	-Average Age
	-Average Salary
	-Average Years
 
 ##### Column chart shows

 	-Attrition By Age

  ##### Pie chart shows

  	-Attrition By Education

   ##### Line chart shows

   	-Attrition by Years At company

### Level 3: 
The Table visual displays attrition rates segmented by job role and job satisfaction levels, helping to identify patterns between employee satisfaction and turnover.

## Preparation of dataset:

- The transformation and data cleaning is done in Power Query and then the data is loaded.
- Fields included: Age, Gender, Education, Job Role, Department, Monthly Income, Years at Company, and Attrition flag.

## Cleaning & Transformation:

- Removed nulls and duplicates
- Grouped salary into ranges (e.g., Upto 5K, 5K–10K, etc.)
- Mapped age into age groups (e.g., 18–25, 26–35, etc.)
- Used Power BI DAX for calculated metrics like Attrition Rate, Average Tenure, etc.


## Report Snapshot (Power BI Desktop)
 
  ![Snap_Percentage](https://github.com/user-attachments/assets/b7cd9452-24ee-42ee-a587-470f17e351fb)


- Snap of slicers used, through which the user can filter the report.

   ![Snap_Percentage](https://github.com/user-attachments/assets/903d019d-0029-43ea-b005-c0e21ebef49d)

- Snap of date filters used, through which the user can filter the report.

   ![Snap_Percentage](https://github.com/user-attachments/assets/9761135c-8667-4ca3-975c-01ea1472f24e)


- Card visuals represented the Revenue, RevPAR, DSRN, Occupancy %, etc.

  ![Snap_Count](https://github.com/user-attachments/assets/915a1108-4bde-4be0-9b09-3fb584fe3465)

 
- A column chart was used to represent the Realisation % vs ADR by booking platform.

  ![Snap_Count](https://github.com/user-attachments/assets/084beabf-a408-4a62-87f0-18d8f013c4c0) 


- A line chart was used to represent the trends by key matrix like RevPAR, ADR, and Occupancy for every week.               

  ![Snap_Count](https://github.com/user-attachments/assets/e75dbd07-f853-4ec6-ab1c-a989f7745f64) 


- A pie chart represents the revenue by room category (Luxury or Business).

  ![Snap_Count](https://github.com/user-attachments/assets/95f65d95-25b8-49c4-88f9-2c4c7811db45) 


- A Table chart was used to represent booking and revenue details based on weekdays and weekends.

  ![Snap_Count](https://github.com/user-attachments/assets/41c7ff49-ed73-4a73-80e5-b8cab601b068)


- Another Table chart was used to represent each property detail which is useful to make decisions based on property.

  ![Snap_Count](https://github.com/user-attachments/assets/9c6b01ce-e0a1-499b-a27f-c224e635f972)



## Analysis and Result:

By analyzing the data it was found that we have to take the following steps:

	- By analyzing the dashboard we can have an idea of demand and supply of rooms and make the prices dynamic accordingly.
	- Different promotions and coupons should be applied on various channels.
	- We can check the property details and occupancy % for each property and make changes to grab more bookings.
	- For each hotel, we can get the idea that it's using flat or dynamic pricing based on weekdays and weekends.
