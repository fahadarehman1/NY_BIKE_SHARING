# NY Citibike with Tableau
UW Data Bootcamp - Module 14

- ### **Overview of the analysis:** 
  
  - The purpose of the analysis is to show that Ride sharing program in Des Moines, IOWA is a solid profitable business proposal based on the analysis done on New York data. We used Tableau to present our story and business case and used Python pandas library for column data type conversion. The analysis is also based on a single month data i.e. **August 2019**
  
  - Following set of new visualizations are created as part of the final analysis:
    - Length of time that bikes are checked out for all riders and genders
    - Number of bike trips for all riders and genders for each hour of each day of the week
    - Number of bike trips for each type of user and gender for each day of the week.
    - . . .
    
  - During the analysis we also found data discrepancy on the Gender Type classification column which will be covered later in the analysis
  
    
  
- ### **Findings:**

  - ![](/images/customer_demographics.PNG)

  The first dashboard tell us the important counts which are needed to compare the New York data with Des Moines data. We started with the count of trips taken in the month of August. Trips are further broken down by the gender(calculated field) and we can see that there's a 1:3 female/male ratio. We also added the breakdown on Customer Type, the subscriber as the name suggest are on monthly/annual contracts where as customer are the one renting the bikes for a one-time use. The last graph breakdown the monthly count by peak hours so any maintenance work, downtime etc. can be accounted and scheduled based on the data. From the bar graph above we can see that between 2-5am is the most optimal time for bike repairs and maintenance.  The other way to look at the bar graph is the need of customer associates during the peak time of the day. 

<img src="/images/trips_by_gender_weekday_per_hour.PNG" style="zoom:75%;" />

The above graphs narrative goes with the 'Peak Hour' bar graph as we can see on weekdays the peak hours are in the morning from 6-9am and 5-8pm for both the genders. Saturday schedule gets busy around 9am and its consistently busy till 7pm. Sunday is an off day as compare to Saturday

![user_trips_by_gender_by_weekday](/images/user_trips_by_gender_by_weekday.PNG)

The above analysis shows that we have more subscribers than regular customers

![checkout_times_by_user_by_gender](/images/checkout_times_by_user_by_gender.PNG)

Checkout time for each user and breakdown by gender. its safe to say that 3-6hours is the amount of time a user usually rents the bike.



### **Data Anomalies:**

![data_anomaly1](/images/data_anomaly1.PNG)

![data_anomaly2](/images/data_anomaly2.PNG)

### **Other graphs that can be created/tweaked:**

- ​	The 'August Peak Hours' graph can be configured for weekdays and weekend. 
- ​	Add a graph and the count of each starting location so more customer associated are available at those locations
- ​	Fix some data issues on birth year and gender_type(unkown) data or remove the birth year and gender_type from the analysis so data is not skewed and presented accurately.



### **Summary:** 

Des Moines population for year 2020 was 215,636 where as population for city of New York city is roughly 8.8million. On a yearly basis we have 66million people visiting New York post-covid numbers. The comparison is not going to be fair from lots of perspective i.e. city's landmark, weather, tourist count, paved vs unpaved bike routes, age group, scenic routes etc. A lot of data points needs to be compared in order to make a fair assessment. Also a city of smaller scale such as Madison, WI or Minneapolis, WI might be worth exploring.
