# Exploration of Ford GoBike System Data
## by Muhammad Moustafa


## Dataset

> The dataset consists of 183412 record and 16 columns.
Out of these 16 columnsm nine are numerical, two are datetime, four are object and one is boolean type.
The columns can be grouped into four main categories

- trip related
    - duration_sec
    - start_time/end_time
- station replated
    - start_station_id/end_station_id
    - start_station_name/end_station_name
    - start/end_station_latitude/longitude
- bike replated:
    - bike_id
    - bike_share_for_all_trip
- user related:
    - user_type: whether the user is customer or subsriber
    - member_birth_year
    - member_gender


## Summary of Findings

- Most data are below 2k with a peak around 400, The analysis should focus in this portion
- Most values of age is less than 70 with peak around 30
- Same stations are frequent as start and end stations
- Subscriber are more probable than customers
- Male are more probable than females and others
- The least days with bike trips are the weekend days
- As for hours, There are 2 peaks at 8 and 17, "the start and the end hours of work day". 
- Both short and long trips are most frequently made by bikers between 25 and 35
- All genders have nearly the same duration distribution with peak between 250 and 750 secnds
- The median value for female is slightly higher than male and other
- We can see that on average that customers do longer trips than subscribers
- Most long trips are done on weekends
- Most long trips are done between 11 and 17, There are nearly no long trips done between 0 and 6
- The same stations are associated with longer/shorter trip whether as start or end destination 
- Customers do longer trips than subscribers, Females do longer trips than males and other
- Older males do longer trips than females
- It seems those who are at working age are doing most of the trips
- Older people do bike trips at the morning more than any othet time


## Key Insights for Presentation

> I have invistigated Start time, Age, Gender and user_type to see how they affect the trip duration. 
Start time: doesn't affect trip duration
Age: The mean of all ages is almost the same, yet there are 2 peaks at lower and higher ages. As geeting older, femlae do longer trips than males
Gender: In general, Female do longer trips
User type: Customer do longer trips than Subscribers
