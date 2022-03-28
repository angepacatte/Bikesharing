# Bikesharing

## Overview

The project was a statistical analysis of city bike sharing data for the month of August in New York City.  There were many fields in the data including day of the week, time of day, gender, and location where the ride started and the ride ended.  The information is helpful in determining when the largest volume of bikes need to be available, when bikes can be repaired, and where the majority of the bikes need to be located among other details.

The original data was transformed so that the timeduration was changed to a date and time.  This was performed in Jupyter Notebook with pandas.  The next 3 images show the steps taken to convert the data and put it into a new csv file.

![image](https://user-images.githubusercontent.com/85581208/151676304-96e427b6-1606-4bdd-92fa-3e655fdb7e18.png)


![image](https://user-images.githubusercontent.com/85581208/151676310-b2811f8b-f872-4c39-9856-bfdf9862acf4.png)


![image](https://user-images.githubusercontent.com/85581208/151676318-43847d6a-00e4-4e34-a1e8-8b616ecb7808.png)




## Results

Link to Tableau Story:  https://public.tableau.com/app/profile/angela.pacatte/viz/CitiBikeChallenge_16431688739080/Story1?publish=yes

This is a bar chart showing the peak hours of bike rental.  The rental numbers peak 7-9 AM and 4-7 PM.

![image](https://user-images.githubusercontent.com/85581208/151676435-74a8b2f2-715d-47c4-9811-9bfb31ccd9f1.png)


The second visual is a line graph showing a trip duration. The majority are 20 minutes and under.


![image](https://user-images.githubusercontent.com/85581208/151676118-995e1c32-70cc-4419-bdd7-26ab8d874711.png)


The third visual is a heatmap with the hours of the day on the y axis and the days of the week on the x axis.  Heavy traffic times appear to be around 8 AM Monday-Friday and around 5-6 PM Monday-Friday. Thursday seems to be the highest traffic day at 8 AM and 5 PM.  Saturday and Sunday appears to be busy all day from 9AM-6PM.

![image](https://user-images.githubusercontent.com/85581208/151676220-984713fe-39fd-4164-8427-60a2c7260253.png)

The fourth image is a line graph showing trip duration broken down by gender.There is not much difference in tripduration.  The detail most noted is there are many more males that use the bikes.
![image](https://user-images.githubusercontent.com/85581208/151676583-ea150467-eff9-419f-9ea3-b3a017352b2c.png)

The 5th image is another heatmap showing bike usage for days of the week and what hours broken up by gender.  Females tend to use the bikes more on the weekend.  Men use them highly all week with peaks in the morning and afternoon.  

![image](https://user-images.githubusercontent.com/85581208/151676626-6abc9b56-8b24-4dc0-b051-00b0839e5391.png)


The visual has dots showing where most trips start.  There are definitely higher concentrations in the main part of the city and then one area north.


![image](https://user-images.githubusercontent.com/85581208/151676711-6ca87da9-ea95-481c-9953-34f584991a07.png)

The last image is a heatmap breaking down by usertype and gender. Female customers appear to have the highest usage on Saturday.  Female subscribers do not have much usage.  Male subscribers have the highest use with Thursday having the largest amount of traffic.  Although lots of use the other days of the week.

![image](https://user-images.githubusercontent.com/85581208/151676759-b9078592-e704-4f9e-a692-9c7a531ee8a8.png)

## Summary

In summary, males use the bike the most over females.  The highest traffic times appear to be in the morning and later afternoon.  This correlates with commutes to work and home from work.  The weekends appear to have steady usage all day.  To do further analysis, a break down of where women/men are starting their trips.  Another area to look into could be where trips are starting and ending on the weekend.


