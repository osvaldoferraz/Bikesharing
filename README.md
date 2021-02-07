# Des Moines BikeSharing Program

## Overview

There is some interest in opening a bussiness of Bike Sharing in Des Moines in the likes of the New York City Bike-Sharing Program (Citi Bike NYC).
The purpose of this panel is to bring up some data form the Citi Bike NYC in order to analyse the feasibility of opening a similar business in Des Moines.

## Results

Some important aspects of the business, regardless of where it will be located, will be pointed out below.

The universe of people using the bike sharing in NY in the month of August was of 2,344,224. August is one of the busiest months in the program, hence why it was chosen as our model.

### Gender
A breakdown in gender can help us understand what is the predominante user of the program, and also to give us insights in how to expand the program to other genders.
In NY, the vast majority of users are male, followed by females, and a small portion of unknown gender.

![Screen Shot 2021-02-07 at 2 39 59 PM](https://user-images.githubusercontent.com/72593264/107158860-5b9a3680-6952-11eb-9cef-15b7f01d82df.png)

### Average trip time by Gender

The average trip time will help understand how many times a bike can be used per day.
The average trip is around 5 to 7 minutes accross genders. Most of the rides will take les than 20 minutes, and a very few rides take longer than 40 minutes.

![Screen Shot 2021-02-07 at 2 53 24 PM](https://user-images.githubusercontent.com/72593264/107159220-3f979480-6954-11eb-8e01-4bd853254299.png)

### Trips by Weekday by Gender and by User category

It is importante to know what days of the week has more traffic. Also it is important to understand the customer base usage. The bike shareing service can be usad as a standalone pay-per-use service, or it can be subscribed.
The heatmap belows shows that
- the service is used more by subscribers in everysense (gender and weekdays).
- it also shows that most users use it during workdays (mon-fri).
- for some reason, wednesdays rides are not as high than the wother workdays.

![Screen Shot 2021-02-07 at 3 18 39 PM](https://user-images.githubusercontent.com/72593264/107159770-c5690f00-6957-11eb-9e34-f02e98d9c835.png)

### Trips by Weekday per Hour

Knowing the busiest hours of the day will paint the customer profile and also help schedule bikes maintenance more effectivelly.
The next heat map makes clear that the busiest hours are exactly the comute hours to work. So the basic bike sharing customer in NY is the everyday comuter that chooses to use a bike instead of a car or public transportation to comute  to work. A slightly less usage can be seeing during weekends, more in the afternoon, probably directed for leisure.

![Screen Shot 2021-02-07 at 3 22 29 PM](https://user-images.githubusercontent.com/72593264/107159862-4cb68280-6958-11eb-8d4f-eea2cc471218.png)

### Trips by Gender by Weekday by Hour

To refine our cross data gender analysis, it is also important to know in a hour per weekday basis how is the bike sharing user sorted by gender.
The heat map below shows that there is not a significant diference in usage between genders, apart from the quantity - most female users also use the service to comunte to work, with a slightly less usage in weekends, probably for leisure.

![Screen Shot 2021-02-07 at 3 36 00 PM](https://user-images.githubusercontent.com/72593264/107160164-2f82b380-695a-11eb-9115-420bb040db52.png)

### Bike sharing usage accors NY City

To get a glance on how spread this system can be, below is a map of Manhattan and neighborhoods and the points where bikes were checked in/out, including how many bikes per each point.
It can be seen that the program is heavily used and spread throughtout the entire island.
Intersteing to note that the center of Manhattan is where we can see more of the service being used, which reinforces the notion of comute use.

![Screen Shot 2021-02-07 at 3 45 21 PM](https://user-images.githubusercontent.com/72593264/107160383-7f15af00-695b-11eb-8d29-0d30c1a7fc3f.png)

## Summary

In conclusion, the bike sharing system in New York is:
- heavily used, with a customer base of more than 2 million rides per month in the high season.
- It is predominatly used by males.
- It is used most for short duration rides, between 5-7 minutes.
- Peak usage is in the early morning and early evening during workdays, and weekend afternoons.
- it is clear that most people tend to use the system to comute to work, and for leisure during weekends.
- usage among genders is similar (to comute during workdays and weekend leisure).
- geography is to be taken in account when planning the stations: commercial and work centres tend to have more traffic.

### Suggestions fo future analysis

- It can be usefull to have more data and visualizations regarding the fare system: customers and subscriptions historically in New York, and also comparing with other bike sharing programs in the US.
- Also a visualization on bike maintenance costs and maintenance duration.

## Tableau Link
All these visualizations are avaliable in a more interactive way in my [Tableau Dasboard (click here to see)](https://public.tableau.com/profile/osvaldo4632#!/vizhome/Tableau_16127366967310/NYCCitiBikeSharingStory).
