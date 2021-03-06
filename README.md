# bikesharing

## Overview of the Analysis
>The purpose of this analysis was to pull data from a New York City bike sharing company and present a summary using Tableau to convince investors that a bike-sharing program in Des Moines is a solid business proposal.

>For this analysis I created a set of visualizations to:
>1. Show the length of time that bikes are checked out for all riders and genders
>2. Show the number of bike trips for all riders and genders for each hour of each day of the week
>3. Show the number of bike trips for each type of user and gender for each day of the week.
>4. Show the number of rides per user type.
>5. Show the peak times of the day for bike usage.

## Results
### All data shown in the graphs below are from August 2019 usage data.

![](Resources/Customers.png)
>The chart above shows the breakdown of the 2 user types: Customer(non-subscriber) and Subscriber(annual subscription user)

![](Resources/August_peak_hours.png)
>The graph above shows the usage in number of rides for each given hour during the day.

![](Resources/Checkout_times.png)
>The graph above represents the amount of time checked out per each ride.

![](Resources/Checkout_times_gender.png)
>The graph above reveals the amount of time checked out per each ride broken down by gender.

![](Resources/Trips_weekday_hour.png)
>The heatmap above indicates the times of day by weekday that each trip was taken. The greener the block, the higher number of rides.

![](Resources/Trips_weekday_hour_gender.png)
>The heatmap above is similar to the previous one, except it is filterable by gender of the rider. The more orange the block, the higher number of rides that hour/day.

![](Resources/Trips_weekday_hour_gender_user.png)
>This final heatmap reports the number of riders per day of the week broken down by both customer typer and gender. The deeper the blue, the higher the number of rides.

## Summary
### The link below will take you to the various analysis graphs that were created and the final Storyboard.
[link to dashboard](https://public.tableau.com/profile/jeff3975#!/vizhome/JSischo_CitiBike_Challenge/CheckoutTimesforUsers "link to dashboard")

When looking at the data from the NYC bikesharing data, we can get a high level sense of what type of user we can target in Des Moines. Some of the compelling data gives us the following conclusions and possible assumptions:
- The breakdown of user type is overwhelmingly in favor of the subscriber, about 81%. This would seem to indicate that the majority of the users are not tourists and most likely residents of NYC.
- The peak hours of usage are 5-7 PM and 8 AM. Again indicating that maybe the main user is someone who works in the area of the bike rental as those are typical work day commutes. This is further reinforced by the graph that represents the various length of times that each ride took. The overwhelming majority of rides were between 1 and 24 minutes. Most likely a short commute to work and back. Add into this the graph that shows us the Trips by Weekday in heatmap fashion. This heatmap indicates that the most popular days of the week and times of the day for a ride are Monday through Friday during the morning around 8 AM and in the evening between 5 and 7 PM.
- We can also tell from the NYC data that the vast majority of trips are performed by male riders. The three graphs that give us a breakdown of different indicators by gender show us that almost 74% of riders are male. All of the previous trends are follwed when looking at the data by gender, weekdays and work times are the most popular and the majority of users, both male and female are subscribers. 
- There are a number of further analyses that could be completed to help further the investors knowledge to better inform their decisions, a couple that I would recommend are:
  - A breakdown of the length of each trip by the type of customer.
  - A map analysis of the most popular pick up and drop off locations for each ride. 

The conclusion to draw from this data when determining the succes of opening a similar service in Des Moines, IA would be to run a breakdown of the working population in Des Moines. They would potentially need a large population of potential riders in a small radius in downtown Des Moines. They would want a largely male population and would need a large number of potential users to sign up for annual subscriptions. 
