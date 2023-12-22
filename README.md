# HospitalityDomain
Data Analysis of Hotel bookings located in different cities.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Recommendations](#recommendations)

### Project Overview
This data analysis project aims to provide valuable insight into the bookings of various hotels located in four different cities over a period of three months. By analyzing various aspects of the booking data, I seek to indentify the booking patterns for diffeent types of room and location, and examine particular hotel to  make data driven recommendations.


![image](https://github.com/Harshkumarspatel/HospitalityDomain/assets/151779392/1c1064f8-7b53-4cc9-8768-b71706cfefcc)



### Data Sources
There are five different csv files used. Which contain detail of every bookings by various platforms, room types, hotels and dates.

### Tools
- Excel - for data cleaning
- PowerBI - for data analysis and to create report 

### Data Cleaning
In the initial data preparation phase following tasks were performed:
1. Data loading and Inspection
2. Handling missing values
3. Data cleaning and formatting

### Exploratory Data Analysis
EDA involved exploring sales data to answer following questions:
- Which days of the week shows higher booking compared to others?
- Which type of rooms have high frequency of booking?
- Which booking platform gives highest booking?
- What is the booking trend over the weeks?

### Data Analysis
Using Power Query in PowerBI some columns generated to create measures, after that data modelling was performed between the tables.

To generate different KPIs, DAX measures were created in PowerBI as shown below:

1) RevPAR = DIVIDE([Revenue],[Total Capacity],0)
2) ADR = DIVIDE([Revenue],[Total bookings],0)
3) DSRN = DIVIDE([Total Capacity],[No of days],0)

ADR-Average Daily rate | RevPAR-Revenue Per Available Room | DSRN-Daily Sellable Room Nights

### Results

1. During the weekend time the hotel booking shows higher occupancy and RevPAR than weekdays.

![image](https://github.com/Harshkumarspatel/HospitalityDomain/assets/151779392/28176e6c-bea2-47d8-bf6b-28f73ed3745c)



2. Almost all platforms have same booking realisation but ADR is higher for offline direct booking.

![image](https://github.com/Harshkumarspatel/HospitalityDomain/assets/151779392/07aec61a-061c-40c8-91d7-0281689b07d0)



3. Revenue from luxury category (62%) is more than business category(38%).

![image](https://github.com/Harshkumarspatel/HospitalityDomain/assets/151779392/3a5ed10c-90ff-428f-89ee-7e77d1674da0)



### Recommendations
Based on the analysis, I recommend following actions:
- Although the occupancy increase during weekends by around 7% compared to weekdays, the ADR is not increased much. So, hotels can focus on price hike during weekends or can increase available rooms during that time.
- ADR is comparatively low when booking is done through online platforms than direct offline. So, It is possible because these platforms are giving more discounts the customers which can be reduce.
- Hotels in the city like delhi not able to generate even 50% of the mumbai city, so the focus should be to attract more customers in these kind of area.
