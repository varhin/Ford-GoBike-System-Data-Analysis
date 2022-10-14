#  Ford GoBike System Data
## by Vanessa Arhin


## Dataset

This data set includes information about individual rides made in a bike-sharing 
system covering the greater San Francisco Bay area.I changed the datatype for 
some columns, dropped some columns that was not going to be needed and created 
new columns with the data in already existing columns. I changed the start_time
and end_time columns to a datatime datatype because I need to extract the day 
and hour to help with my analysis.


## Summary of Findings

The average duration of a trip is about 30 mins. Most trips are taken on Tuesdays, 
Wednesdays and Thursdays early mornings and late afternoons. Subscribers take more 
rides than customers. There are more subscribers than customers and they take more 
trips than customers as well. Customers tend to take more shorter trips.
The most popular start station at San Francisco Bay area is Market St at 10th St.
These will be explained much further in my explanatory presentation. 


## Key Insights for Presentation

My focus for the presentation is on what are the peak days and hours for the bike sharing 
system. I will introduce the day variable(for start time), followed by the hours in day, 
then plot the relationship between these two variables using a heat map.

Also, I will introduce user type variable as a single variable. Then I will compare user 
type with ride duration and also days in the week to determine what user uses the bike system
the most.
