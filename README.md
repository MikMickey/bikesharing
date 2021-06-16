
# BikeSharing
Module_14
Tableau to analyze bikeshare data in NYC

## Resources
Data Source: Citi Bike Data, 201908-citibike-tripdata.csv.zip
Software: Python 3.8.5, Jupyter Notebook 6.3.0 and Tableau Public 2021.1.2


## Project Overview & Challenge
The purpose of this module is to analyze New York City Citi Bike sharing trip history data from August 2019. With the analization, we will see if bike rental business is worth investing in to different cities. One of the key factors we need to look at is tripduration. Finding out how long the trips are in the month of August will give us a good analysis on when the bikes are rented, how long they are rented and what times are the most popular times to rent a bike.  Prior to creating the visualizations, some of the data was cleaned using Jupyter Notebook and Pandas to change the column that records the trip duration in seconds to hours, minutes and seconds. Once this was completed new CSV file was uploaded to use for deliverable 2 plots


## Results:
7 different visualizations showing the total number of trips, the types of users and trip duration was presented using the Tableau ~ NYC Bike Sharing Analysis.

To see all of the visualizations please click the link below:
https://public.tableau.com/shared/5MX57H7M7?:display_count=n&:origin=viz_share_link




- August Peak Hours:

The Bar graph represents the peak hours for Citi Bikes trips. The x-axis shows the Number of Trips and y-axis the hour of the start-time. The chart shows that peak commuting hours are from 8-9am, 5-6pm and 6-7pm. 2-3am morning does not seem to have many trips taken.
![August Peark_Hours](https://user-images.githubusercontent.com/80075982/122303451-6e041e00-ceb8-11eb-8acd-831ea225dd7f.png)



- Trips by Weekday per Hour:

The chart shows the frequency of trips for each day of the week and time of day. The darker the color shows more trips taken during 5-7pm on a Thursday, which is also a popular time for most other weekdays. 
![Trips by Weekday per Hour](https://user-images.githubusercontent.com/80075982/122164910-4a939180-ce2c-11eb-8620-ed4988fb6370.png)


- Checkout Times for Users:

The line graph showing the Checkout times for users by minutes and hours. The y-axis shows the number of bikes checked out and the x-axis is the hours and minutes. Minute of the trip duration shows a sharp peak in the number of bikes checked out with a sharp decline down to less than 1,000 bikes checkouts out beyond an hour. 
![Checkout Times for Users](https://user-images.githubusercontent.com/80075982/122164902-47000a80-ce2c-11eb-8687-6cafcd235394.png)


- Gender Breakdown: (Gender Breakdown pie chart of number of Citibike users by gender )

The pie chart shows break down bike users by gender. A majority of Citi Bike users (65%) are male, with Females representing only 25% of citibike users and Unknown representing 10%.
![Gender Breakdown](https://user-images.githubusercontent.com/80075982/122164904-48313780-ce2c-11eb-99a4-522272888f54.png)


- Checkout Times by Gender:

The line graph that shows the Checkout Times by Gender. The number of bikes checkout out is displayed on the y-axis and the hours and minutes of the trip duration are displayed on the x-axis. At the trip duration mark of 5 minutes, there is a sharp increase in the number of bikes checked out by males. The peak trip duration for the majority of bikes checked out by females occurs around 7 minutes. There is a long tail of a limited number of bikes checked out by females for longer than an hour. As shown in the Gender Breakdown, many more males have checked out bikes than females or unknown. This visualization is filterable by gender and hour of trip duration.
![Checkout Times by Gender](https://user-images.githubusercontent.com/80075982/122164899-45cedd80-ce2c-11eb-9c89-e1be25a3e3da.png)


- Trips by Gender (Weekday per Hour)

The heatmap displays the Trips by Gender by Weekday per Hour. When trips occurred throughout each hour of the day (shown on the y-axis) for each day of the week (on the x-axis) split by each gender. Many more trips were taken by males compared to females and unknown and the peak times and days for males were during the work-week around 8am and 5-7pm. The peak times for females were around the same times and days, but to a much lesser extent. The trips by unknown gender are pretty much the same throughout the week, with a slight increase on weekend afternoons. The number of trips for the unknown gender are much less than males or females. 
![Trips by Gender (Weekday per Hour)](https://user-images.githubusercontent.com/80075982/122164908-49626480-ce2c-11eb-8514-a2770f1e28e0.png)


- User Trips by Gender by Weekday:

The chart shows the number of trips by type of user (Customer or Subscriber), as well as by the Weekday and Gender. The number of trips for customers are much less than the number of trips for subscribers. Amongst the customers, the gender hardly affects the number of trips and there is only a slight increase in the number of trips during the weekends. Amongst the subscribers, a majority of the trips are taken by males with the most popular day being Thursday. Amongst the subscribers, the unknown gender counts for very few of the trips and the trips by females are much less than those taken by men, but follow the same peaks in the days.
![UserTrips by Gender by Weekday](https://user-images.githubusercontent.com/80075982/122164916-4c5d5500-ce2c-11eb-84ca-f5483c9392e1.png)


## Summary
Based on the results and visualizations of the NYC Bike Sharing trip history data from August 2019, it seems that a majority of the trips are taken by males that are subscribers and most trips occur during commuting hours on weekdays, especially Thursdays. Most NYC Bike Sharing trips are under 10 minutes and hardly go past one hour. As the commuting times tend to be the most popular, repairs and maintenance can be done in the early hours of the morning when there are not many bikes in demand.

