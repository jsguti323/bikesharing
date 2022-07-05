# CitiBike Trip Data Analysis

## Overview
Our goal is to open a bike sharing app in our hometown of Des Moines, Iowa. The inspiration of the project comes from the New York based bike sharing app, CitiBike. For us to determine whether or not our bike sharing app will work in Des Moines, Iowa, we must first try to understand how it works in New York City. We have taken a look at CitiBike ride data in the month of August, as August is a peak summer month and rides typically increase in number in the summer months. Once we analyze this data, we can determine which data is relevant to Des Moines and make a pitch.

## Results

### Checkout Times by User
![checkout times by user](https://user-images.githubusercontent.com/99751636/172027683-b73798aa-af3c-4a30-8bc9-cb489af34252.png)

* Most rides do not last longer than an hour.
* The five minute mark is the most frequently appearing trip duration.

### Checkout Times by Gender
![checkout times by gender](https://user-images.githubusercontent.com/99751636/172027700-7afde1fe-f143-42fa-a4cd-4a730c2878bf.png)

* The majority of users are male.
* The trends of the dataset for each gender are relatively similar.

### Trips by Weekday
![trips by weekday](https://user-images.githubusercontent.com/99751636/172027730-80de0344-0968-419c-a074-e0e9f460279a.png)

* Monday - Friday: preak times are seen from 7am-10am and 5pm-8pm
* Saturday-Sunday: there is no single high peak for these days, but rather a steady level of activity from 10am-8pm

### Trips by Gender (Weekday per Hour)
![trips by gender(weekday per hour)](https://user-images.githubusercontent.com/99751636/172027739-2b53ef49-6113-489c-8f78-de30cbd46986.png)

* The trends discovered in our "Trips by Weekday" analysis hold true for all genders.
* Again, we see that while trends are true, there are significantly more male users than there are users of any other gender.

### Trips by Gender by Weekday
![trips by gender by weekday](https://user-images.githubusercontent.com/99751636/172027750-481d4984-8819-4866-86f4-ed49d77fc79d.png)

* The majority of users are male subscribers.
* There is more activity on weekdays than there is on weekends.
* There are more subscribers than there are customers.

### Number of Rides by Gender
![number of rides by gender](https://user-images.githubusercontent.com/99751636/172027760-c674cbd1-26fb-4e21-83d9-91e057f146c4.png)

* There are significantly more male users than there are users of any other gender.

### Bike Utilization
![bike utilization](https://user-images.githubusercontent.com/99751636/172027768-02c95ccb-8110-4f61-8258-846c02b6ffd6.png)

* Measuring how many minutes each bike was used in the month of August.
  * The smaller and more blue the circle, the fewer minutes that bike has logged.
    * These rides gravitate toward the center of our chart.
  * The bigger and more dark red the circle, the more minutes that bike has logged.
    * These rides spread toward the outside of our chart.
* We can filter our chart by Bike ID and Trip Duration.


## Summary
While the results do not outright suggest that a bike ride sharing app in Des Moines, Iowa would be unsuccessful, the findings of this project also do not inspire very much confidence otherwise. The majority of the users are male subscribers and peak usage hours coincides with peak commuting hours in New York City. The fact that most users have deemed this service necessary to their daily lives that they have become regular subscribers, coupled with the fact that most rides occur during peak commuting times suggests that the majority of users use Citibike to commute to and from work. CitiBike owes a lot of it's success to working commuters in urban areas, a subpopulation that, by volume, is very common in New York City, but not so much in Des Moines. Therefore, we do not have enough data to suggest that a bike ride sharing app similar to CitiBike would be successful in Des Moines, Iowa, but that does not suggest that the data is not out there somewhere.

**** Suggestions
* Visualization of start and stop stations during peak usage hours. This could help answer our question of if most users are working commuters. 
* Visualization of ride count versus user age. We could look at the most frequently occuring demogrpahics amongst users and see how they compare to the demographics of Des Moines.


### Link to Tableau Story
[NYC CitiBike Analysis](https://public.tableau.com/app/profile/john.gutierrez7405/viz/NYCCitibikeAnalysis_16543770843820/NYCCitibikeAnalysis)
