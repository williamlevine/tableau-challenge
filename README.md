# Citi Bike Jersey City: Tableau Challenge

[Click here to navigate to the Tableau Public Workbook.](https://public.tableau.com/app/profile/william.levine/viz/CitiBikeProject_17308471024950/CitiBikeJerseyCityJanuaryvsJuly)

## Overview
This repository contains the source files used to build a Tableau Story for Citi Bike in Jersey City, New Jersey. The completed Tableau Story visualizes data about total distance ridden by Citi Bike customers in January of 2024 and in July of 2024, and tracks what proportion of rides were taken by members and by non-members during these months. The Story also shows which stations were most frequented in each month, and features an interactive map of all stations with their popularity indicated by size of the marker. The months of January and July were chosen as representative of the winter and summer seasons.

All source data is in the folder titled `Resources`, and the codebook used to clean the data is titled `cleaning.ipynb`.

A link to the Tableau Public Workbook can be found above, and in the `.twbx` file in this repository.

## Analysis
Dashboard 1 compares total distance covered by Citi Bike rides in the months of January and July of 2024 in Jersey City, New Jersey. It also looks at the percentages per day of rides taken by members versus nonmembers, or “casual” riders. The total distance data was calculated from the original data, which had coordinate information of the start and end of each ride. What can be seen immediately upon looking at the line charts is that the total distance covered per day in January has much more variation than in July; also, the total distance covered in January is much lower than in July. Both trends make sense when considering typical weather patterns in those months: perhaps fluctuations in temperature and precipitation come to bear on the trends we see in the line graphs. However, on further investigation, in both January and July, spikes in total distance ridden per day seem to have weekly peaks: in January, total distance peaks on Thursdays; in July, such a trend is less apparent, with peaks on various days of the week, but with small increases near weekends.
If we compare these charts to the bar graph showing the proportion of rides taken by members versus non-members, another insight can be gleaned: the proportion of casual riders peaks regularly on weekends, both in January and in July. When compared to the line graphs above, these increases in casual riders often aligns with an increase in overall total kilometers ridden. Both elements of this phenomenon could be used to help in marketing Citi Bike’s services if desired: for example, additional effort could be put in to advertising how the service is useful during the weekdays, or by offering perks to members who ride on weekdays to encourage repeated and regular use of the bikes.

Dashboard 2 compares the top 10 most popular destinations in January to those in July for Jersey City, New Jersey. Many of the destinations appear in both months, but in July, nearly all of the top 10 destinations are very close to the riverfront, whereas many in January are in downtown areas or near other major transit hubs. The South Waterfront Walkway station, for example, is a popular destination in July, and it is right next to a large park on the river. This information is crucial for marketing purposes as well as for logistics and coordination: knowing which stations are the most frequented in any given season is crucial in order to maintain them and ensure they always have enough bikes available for use.

The map visualizes the popularity of different Citi Bike stations in Jersey City, with larger dots representing more popular stations. The user can filter by month to see the changes in station popularity during different times of year. With this map, both in January and in July, it is apparent that stations near the river are more frequented than those more inland. This trend is elaborated when filtering by month: when changing to July from January, the stations near the river, especially those which are more northern, appear to grow in size. This aligns with the trend on the previous page: that stations near the river seem to be more popular in the summer time.