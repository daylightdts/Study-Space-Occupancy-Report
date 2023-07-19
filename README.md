# Space Occupancy: Analyze Peak Occupancy of Learning Space
![intro](https://github.com/daylightdts/Study-Space-Occupancy-Report/assets/134946052/da9c1788-ea4f-478d-a8b9-f31ecea5051d)

## Introduction

This project aims to uncover one (1) month user trends of a student learning space and ensure efficient resource allocation. Analyzing bookings, check-in and time data aims to uncover and extract valuable insights that will ultimately enhance the student experience and contribute to better facility utilization.



## Dataset Summary
![fields preview](https://github.com/daylightdts/Study-Space-Occupancy-Report/assets/134946052/57b27145-547a-4bb9-8c91-816b50a96aa6)

***Disclaimer:*** *This is a mock dataset generated online and does not represent any company, institution, or country.
We hereby make some assumptions since the dataset isn't complete.*


### Assumptions:

a) Each student is allowed 2 hours maximum at the space per day.

b) Checkings and checkouts are exactly on the hour.

c) The space is open from 8 am to 10 pm.



***Since there's no checkout time we need to validate the dataset.***

a) All check-ins at 20:00 must have 2 hours maximum time spent.

b) Checkings with missing or null values must have 0 hours as time spent.




## Skills/ Concepts Demonstrated

***Excel Power Query:***

Data importation from CSV

Data cleaning

Creating additional fields from columns

Loading the data back to the Excel table


***Excel Pivot Charts***

Visualization of the data to answer the problem statements



### ***Final table fields***
![Required Fields](https://github.com/daylightdts/Study-Space-Occupancy-Report/assets/134946052/80a048a9-ebbe-4e8a-9db6-fbb454133f8a)



## Problem Statement

What is the occupancy by day of the week?

What is the hourly occupancy distribution?

What is the average time spent by students?

## Occupancy Report
**Occupancy by Day of the Week**
![Occupancy by day](https://github.com/daylightdts/Study-Space-Occupancy-Report/assets/134946052/c95e3a91-d6fa-40e8-8139-9bebb234c295)

**Analysis:**

The -Occupancy by Day of the Week- report provides the total number of bookings and check-ins that are active for each day of the week in the reporting period. This can help you get a sense of occupancy and check-in totals for each day.
Based on the report Mondays have the highest occupancy followed by Fridays and Wednesdays. The least occupancy and if a student is thinking of a day where the space isn't crowded they should find Wednesdays suitable.

**Hourly Occupancy Distribution**
![Occupancy by the hour-1](https://github.com/daylightdts/Study-Space-Occupancy-Report/assets/134946052/d4e65e8d-0a4d-489d-ba90-3d3907e23fb6)

**Analysis:**

The Occupancy by Hour of the Day report provides the total number of check-ins for each hour of each day in the reporting period. This can help get a sense of occupancy and check-in totals for specific hours of the day. Students can use this insight to decide peak periods and which hours have the least occupancy. Based on the report, on the least occupied day which is Wednesday between 14:00 to 16:00 has the least occupancy of all. On busy days like Mondays a student looking to use the space for a minimum of an hour should consider attending at 10:00 or 17:00.


**Average Time Spent by Day**
![Time spent by occupants by day](https://github.com/daylightdts/Study-Space-Occupancy-Report/assets/134946052/f40bb27b-9825-46b6-9455-afc0e696e80a)

**Analysis:**
The average occupancy by day report provides the average time spent (in minutes) by occupants for each day in the reporting period. 
This provides insight into how much time is spent by occupants on the average at the space.
From the report occupants spend more time on and Fridays, this may be as a result and although Mondays have more occupancy than Fridays both days are on par wuth average time spent.
We see that on Wednesdays students spend more time at the space than on Tuesdays and Thursdays which have higher occupancy numbers.


