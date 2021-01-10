# NYC Bike Share Analysis

## Overview of Project

This project uses Tableau for visualizing NYC Bike Share analysis. Travelers use bikes to explore historic landmarks like Central Park, the Statue of Liberty, and the Empire State Building. There is the potential to start a similar bike-share business in Des Moines, Lowa This study is focused on investors interested in investing in a similar business model focused on Des Moines, Iowa.The first step is to figure out how the bike-share business works in New York City.Second, create a proposal on how it might work in Des Moines.

To conduct the analysis we use the NYC Citi Bike dataset. The data set contains trip details for August 2019 which is the busiest period of the year.To solidify the business proposal, one of the key stakeholders would like to see the following in the bike trip analysis:

- The number of bike trips for all riders and genders for each hour of each day of the week.
- The length of time that bikes are checked out for all riders and genders.
- The number of bike trips for each type of user and gender for each day of the week
 The final visualization results are shown as a Tableau story. Python script is written to convert integer time duration to DateTime datatype.
 
The Propose of this project is to explore Citibike data, create visualizations, and create a Tableau story that will be used to show investors that a bike-sharing program in Des Moines is a solid business prospect

## Results

### Overview of Citi Bike Data 

- 2,344,224 Total number of Rides in August.
- 1,900,356 were Subsriber Users and 443,865 were Customer Users.
- 1,530,272 were Males, 588,431 were Females and 225,521 were Unknown users.
- Peak Trip start time in August was 5 pm.
- Lowest Trip hours were betwwen 1am-5am

### Checkout Times for Users

- 4 to 6 hours was the peak duration bikes were checked out.

### Checkout Times by Gender

- 4 to 6 hours was the peak duration bikes were checked out.
- 4 to 6 hours was the peak duration bikes were checked out for Males
- 5 to 7 hours was the peak duration bikes were checked out for Females

![Checkout Times for Users by gender.png](https://github.com/smj452/Bikesharing/blob/main/Resources/Checkout%20Times%20for%20Users%20by%20gender.png)


### Trips by Weekday Per Hour
![Trips by Weekday per Hour.png](https://github.com/smj452/Bikesharing/blob/main/Resources/Trips%20by%20Weekday%20per%20Hour.png)

- Weekdays have a higher stop-time from 7 am to 10 am and 5 pm to 7 pm.

### Trips by Gender

![Trips by Gender (Weekday per Hour).png](https://github.com/smj452/Bikesharing/blob/main/Resources/Trips%20by%20Gender%20(Weekday%20per%20Hour).png)

- Weekdays have a higher stop-time from 7 am to 10 am and 5 pm to 7 pm for Male riders
- Weekdays have a higher stop-time from 8 am to 10 am and 5 pm to 7 pm for Female riders

### Bike Trips By Gender And User Type
![Bike Trips By Gender And User Type.png](https://github.com/smj452/Bikesharing/blob/main/Resources/Bike%20Trips%20By%20Gender%20And%20User%20Type.png)

- Male and Female Subscriber riders peak is during the weekdays
- Male and Female Customer riders peak is during the weekends 

### Top Locations

![Top Starting and Ending Locations.png](https://github.com/smj452/Bikesharing/blob/main/Resources/Top%20Starting%20and%20Ending%20Locations.png)
Top Starting and Ending Locations are marked by Large dark circles.

[Link to Story](https://us-west-2b.online.tableau.com/#/site/shanu/views/DesMoinesBikeShare/DesMoinesBikeShare?:iid=3)

## Summary

Based on thwe above analysis we can conclude that:
- The highest number of male and female customers use the bike-share services during the weekends.
- Checkout times are higly variable for male and female riders.

## Two additional visualizations reccomendation

- The average distance traveled for all riders by gender for each week by creating calculated fields.
- The average distance traveled for all riders by user type.
