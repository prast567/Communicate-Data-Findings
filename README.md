# Communicate-Data-Findings

# Ford GoBike System Exploration
## by Prashant Kumar


## Dataset

There are 210563 trips in the dataset with 16 features(duration_sec,start_time, end_time, start_station_id,start_station_name, start_station_latitude,start_station_longitude, end_station_id, end_station_name,end_station_latitude, end_station_longitude, bike_id,user_type, member_birth_year, member_gender,bike_share_for_all_trip.The datatypes for diffrent columns are int,float or object.Most the columns does not contain any null value except for member birth year and member_gender.

The dataset can be found from:-https://www.lyft.com/bikes/bay-wheels/system-data

## Summary of Findings


In the exploration, I found that there was a strong relationship between the
number of rides and gender,user_type,age etc. There is significant relationship 
between number of rides and age when age.Young people are more likely to take rides. I found a
somewhat surprising result initially when the people of age around 20 are taking comparatively lesser rides.

Outside of the main variables of interest, I could also see that the number of rides also depends on several other factors such as day of the week.On days such as thirsdays and fridays people are seen to be taking more rides where as on weekends this number is comparatavely low.

From the exploration I can conclude that
- we can conclude that the minimum age for renting the bike is 18 yeras.
- 75% of people taking ride are below 40 years of age
- Maximum peole taking ride are around 18 to 30 years of age.
- Maximum trips on an average have a duration of around 450 to 550 sec
- We can see that on thusday and fri we have maximum trips and is minimum on sunday.
- Male takes maximum trips then female then others.In fact others are taking very less rides.
- Subscribers takes way more rides than normal consumers.
- Bike stations are normally centralized in 3 co-ordinates ie at co-ordinates (37.,-121.9),(37.8,-122.4),(37.8,-122.3)



## Key Insights for Presentation

For the presentation, I focus on just the influence of the user_type,gender,age
on the number of rides . I start by introducing the age variable to see the distribution of age.
The a see the duration of the trip for most of the rides using histogram.The I check to what is the affect of user_type on the number of rides.I also try to analyse wheter gender also affect the number of rides.

Afterwards, I start focussing on other factors such as day of the week i.e on which day of the week people are taking maximum rides.Which user_type is taking more ride on a particular day of the week.

I've made sure to use poper color palettes for each plot to make sure it is clear and more informative.

