# NYC Citi Bike-Sharing Analysis
[View the story on Tableau](https://public.tableau.com/views/NYCBikeSharingChallenge_16723687524140/NYCBikeChallenge?:language=en-US&:display_count=n&:origin=viz_share_link)

## Objective 
For this Challenge we are analyzing the NYC Citi bike sharing program to create compelling visualizations of the data for investors considering a similar program in Des Moines. 

## Analysis
We are using Pandas first to transform the data, Tableau to create visualizations, and storyboards within Tableau to present to the investors. 
### Data Source NYC Citi Bike August 2019 Ride Data
![Link to Citi Bike Data Source](https://ride.citibikenyc.com/system-data)

In August 2019 over 2.3 million bikes were used in the NYC Citi Bike sharing program. Of those 2.3 million rides, 1.9 were used by subscribers that regular rent the bikes. The following analysis breaks down these users and visualizes their age, gender, trip locations, duractions, and weekdays. The program appears to be popular among locals using the bikes to get to and from work, or around, while avoiding rush hour car traffic. I've concluded this assumption from the heatmaps, and time of rentals. 

### Cover Page for Tableau Story 
This page shows us a snapshot of the NYC Citi Bike Share Program users and locations. We can see there were over 2 million rides in August of 2019. Younger customers on average use bikes for longer. Male riders are a dominant category. Most popular locations are in mid to lower Manhattan. 
![image1](https://github.com/DartElina/Bike-Sharing-/blob/9affcd027a6a6dc979de81bfc458bfd23c9b5fa4/Images/story_cover.png)
### Start and End Locations for Rides
This visualization illustrates our most popular locations for starting and ending a ride. Since most popular locations are south of central park in Manhattan, one could assume that tourists are using the service. 
![image2](https://github.com/DartElina/Bike-Sharing-/blob/9affcd027a6a6dc979de81bfc458bfd23c9b5fa4/Images/start_end_location.png)
### Trip Duration 
This visualiztion illustrates the trip durations. Most rides are typically an hour or less. 
![image3](https://github.com/DartElina/Bike-Sharing-/blob/9affcd027a6a6dc979de81bfc458bfd23c9b5fa4/Images/tripduration.png)
### Trip Duration by Gender 
This visualization shows us how much morepopular this service is for men over women, as well as the duration of trips.
![image4](https://github.com/DartElina/Bike-Sharing-/blob/9affcd027a6a6dc979de81bfc458bfd23c9b5fa4/Images/Gender_tripduration.png)
### Heatmap Day and Time for rides
This visualization illustrates the most popular times for rides. 
![image5](https://github.com/DartElina/Bike-Sharing-/blob/9affcd027a6a6dc979de81bfc458bfd23c9b5fa4/Images/Weekday_heatmap.png)
### Heatmap showing most poplar days and times by gender
This visualization shows us that men and women use the service similarly. Using bikes is most popular on the weekends and at rush hours. 
![image6](https://github.com/DartElina/Bike-Sharing-/blob/9affcd027a6a6dc979de81bfc458bfd23c9b5fa4/Images/gender_heatmap_weekday.png)
### Number of Rides, Customer/Subscriber Split, and Heatmap showing users and most popular days to ride
This visualization shows us how different types of users show different patterns of use. 
![image7](https://github.com/DartElina/Bike-Sharing-/blob/9affcd027a6a6dc979de81bfc458bfd23c9b5fa4/Images/customer_subscriber.png)

## Results 
At first we may have concluded that tourists were using the service frequently, but upon deeper analysis it seems the service could be most popular for avoiding traffic, and for leisure. Men are the most common users, and rentals are most used for rides in the 20 minute range. Locals and subscribers use the service most frequently. 

Investors may want to consider, is Des Moines a city with a distinct city center, and extended hours with intense traffic? Locals may find bike rides to be an effective tool for avoiding congested roads. This service is most commonly used by subscribers, locals that use the service regularly. 

I would recommend creating a trip duration line graph comparing subscribers and customers to see if duration is different for riders that don't use regularly. Also a map showing most popular locations on the weekends. These additional visualizations may help us to more deeply understand our customers and how they use our bikes. This can be used to identify our target customer in Des Moines.

I would also reccomend an analysis of Des Moines Traffic, Population, and Concentration of the city center, to help shape the target customer profile. 

