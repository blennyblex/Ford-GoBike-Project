# Part I - Ford GoBike System Data Exploration
## by Blessing Egharevba


## Dataset

The data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.
There are 183,411 individual rides in the dataset, with 16 features ('duration_sec', 'start_time', 'end_time', 'start_station_id', 'start_station_name', 'start_station_latitude', 'start_station_longitude', 'end_station_id', 'end_station_name', 'end_station_latitude', 'end_station_longitude', 'bike_id', 'user_type', 'member_birth_year', 'member_gender', 'bike_share_for_all_trip'). Some of the variables ate numeric, some string. It can also be noted that some of the variables were formatted wrongly (eg, start_time and end_time formated as string instead of datetime). Data Wrangling was performed to improve the dataset usability.


## Summary of Findings

In the exploration, i found out that majority of riders age fall between 20 and 40years of age, with ages above 100years (which could be consider as outliers).Most Rides occured during the weekdays, and least rides on weekends, which had the highest average duration of rides in secs. Though, thurday had the highest number of rides, and the least on Saturday. Also, most rides took place between early morning and Evening, bust mostly at morning, with the least being Early Morning. Afternoon had the highest average ride taken and morning with the least average duration. Furthermore, the last day of the month had the highest number of rides taken. Though a well established pattern cannot be observed, apart from the fact that weekends had the least trips.
Checking for the riders type and gender, Subscribers had the lowest average trip taken in secs, even though they had the highest distribution of riders, with Male having the lowest average trip taken by secs.

Customers had avearge duration increasing as the days of the week increases, going over 1000secs with increasing quartile, while subscribers had avg duration all falling below 1000secs in all days in the recorded month.

Specifying for just the days of the week showed there was increase in the duration with increase in the days, but drilling down to the days in the month showed the specific days that had higher median duration.

I also discovered that there is no correlation between age and duration spend, plotting by Gender.

Females riders had the least average ride at Night and the longest ride early morning, taking above 1000secs.
Male riders have an almost equal number of average duration ride throughout the time period, but having morning as the least duration, butle had more rides in the morning compared to afternoons.
Other gender had their least duration in the evening and the highest early morning.<br>

Male riders had the least duration of ride in every possible feature specified (either by weekday or period or day of the month). Specifying for just the days of the week showed there was increase in the duration with increase in the days, but drilling down to the days in the month showed the specific days that had higher median duration, as well as drilling down to the time of the day showed that females has the highest average rides in the morning, which is almost like the least for Male riders

Though it can be suprisingly noted that there is no correlation between age and durations of rides, working on just the male and female gender

## Key Insights for Presentation

For the presentation, i will be focusing on the least average time it takes to complete rides, depending on both gender and user type, how long on a majority, a ride is supposed to be for. 
I will also be focusing on the influence of age on the duration taken in seconds, as well as the expected age of riders. 
I will also be focusing on when most trips are taken in terms of days of the week, days throughout the month and time of the day. 