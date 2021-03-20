# GoBike Dataset Investigation
## by Shuai Guo


## Dataset

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. This dataset can be downloaded in https://www.fordgobike.com/system-data


## Summary of Findings

- People use shared bikes for short-distance trips (less than 30 minutes).
- Many people ride for around 8 minutes.
- Autumn months see the most bike usage.
- Within a month, people use shared bike mostly during weekdays.
- Within a day, 8am and 17pm are the most busy time for using the shared bikes.
- Month has little impact on trip durations.
- Subscribers tend to ride shorter distance compared with customers.
- Stations nearby major transit stations and financial district are used the most during peak hours.


## Key Insights for Presentation

The presentation focuses on the following three aspects of bike usage:
1. Patterns of trip duration
  - by using histogram, we showed that most people ride for less than 30 minutes;
  - by using parallel boxplots, we showed that riding month has little impact on trip durations;
  - by using violin plot we showed that Subscribers tend to ride shorter distance compared with customers.
2. Patterns of Bike usage by month, day and hour
  - By using bar plots, we showed that autumn months, weekdays, at 8am and 17pm peak hours, people use shared bikes the most.
3. Patterns of station usage
  - By using scatter plot on top of a San Fransicso map, we showed that Stations nearby major transit stations and financial district are used the most during peak hours. This indicates that people tend to use shared bikes to bridge the gap between major publica transportation stations and their workplaces.

## List of resources
- https://seaborn.pydata.org/
- https://github.com/geopandas/contextily
- https://datascienceplus.com/exploring-san-francisco-bay-areas-bike-share-system/
(\* This blog post inspired the map+scatter plot to visualize the bike stations. The original blog employed R and Google map, while this project was realized via Python and OpenStreetMap.)
