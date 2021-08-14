# bikesharing

# Overview of the analysis
In this project we wanted to analyze the citibike data from August 2019 in NYC to try and decide if a similar bike-sharing program could be a good fit for Des Moines, Iowa. Des Moines is obviously very different than the massive city of New York, but we can still present information from this dataset that would be relevant to any city.
 - What types of people use bike-share programs
 - What parts of the urban sprawl see the highest concentration of bike-share usage
 - What times of the day are bikes used the most or least
 - How often the bikes in the program are used

# Results
For this project we created a plethora of different vessels to display our data to the investors
![user breakdown](https://user-images.githubusercontent.com/82848585/129114101-45cc16ed-2da1-403a-b1a7-f88b7b5a72b7.png)
For our user breakdown we were able to deduce that most of our users are subscribers, which means they are a reliable source of income because they are using the bike sharing program as an integral part of their life for transportation. Interestingly, most of the users (almost 75%!) are male, this could be a key factor to take into consideration if an advertising campaign is ever taken on to promote the potential program. 
![Ride Starting Locations](https://user-images.githubusercontent.com/82848585/129114236-17725c32-7252-4b4f-96d1-32a063913fb7.png)
![Ride Ending Locations](https://user-images.githubusercontent.com/82848585/129114408-c741ff9e-29d4-4904-aa3f-f64394421c40.png)
For locations where our riders start and end we created two separate maps. The size of the circles and the darkness of the red/green indicate the concentration of pickups/dropoffs.For both maps the bulk of pickups/dropoffs are originating in the commercial center of the city, and then are dispersed smaller as it gets farther away from this center. From this we can deduce that efforts for a Des Moines bike sharing program should be centered around the most dense parts of the city to attract potential subscribers. 
![usagehours](https://user-images.githubusercontent.com/82848585/129449077-f2e169cc-bbfd-43ef-b687-914768dd8edf.png)
This horizontal bar graph shows us the number of bike rides for each hour of the day during August. Peak usage is expectedly during the morning hours when people are going to work and during the afternoon when workers are going home. One of the questions we had was when would be a good time to make repairs and that is during the early morning hours of 2-5 AM.
![averagetripbyage](https://user-images.githubusercontent.com/82848585/129449136-30ffe617-520a-483a-a908-99d6e930915e.png)
This vertical bar chart shows us some interesting statistics about our age demographics, in that bike sharing programs attract all ages. Also, we can see that on average the older users are taking shorter bike rides than the younger users.  
![numberoftripsperbike](https://user-images.githubusercontent.com/82848585/129449198-94880ab7-62fe-49ca-a50b-48ee4612a425.png)
This heatmap we created shows us what percentage of the bikes in the NY program are getting heavy usage. In green we see the bikes which get the lowest level of usage, close to 50% of the fleet, whereas the other 50% comprised on the yellow and red shades will require more frequent maintenance. 
![ridelength](https://user-images.githubusercontent.com/82848585/129449222-7148bae7-a819-4ba4-a80d-968ae801ade6.png)
This graph shows us the trip durations logged for the bikesharing program. The most important piece of information we can see is that the majority of our riders are only using the bikes for under an hour, in fact our highest usage markers indicate that most of the users aren't even riding for longer than 30 minutes. 
![ridelengthgender](https://user-images.githubusercontent.com/82848585/129449240-c0f4f6dd-0a26-45ee-8e79-c61679b0429e.png)
This graph is the same as above except with the lines split up by gender. We can see that the males are the overwhelming user group. The times taken on the trip do not differ by age in any significant way. 
![hourlyweekdayusage](https://user-images.githubusercontent.com/82848585/129449262-55e9e8f9-6ae3-4c3b-b173-6eb02275ca39.png)
This heatmap reinforces our previous data indicating that most of the users are using the service to commute to and from their job within the city during the morning and afternoon rush hour during the week. The weekend we can see this usage concentration spread out over the day as the users are enjoying the freedom of an open schedule to engage in all of their activities. 
![biketripsgender](https://user-images.githubusercontent.com/82848585/129449364-3f2e8471-ee2b-4deb-96d6-941076949c8a.png)
This heatmap only serves to reinforce how much of the NY userbase is made up of the male gender. It could be worth looking into why this is and how the bike sharing services might attract more female identifying users. 


# Summary
Bike sharing services seem very popular for the urban professional who doesn't want to deal with the automobile traffic that jams up high concentration downtown areas. While it will be important to advertise to male users to build up a reliable subscriber userbase in Des Moines we need to do more research as to why the bike sharing service in NY wasn't attracting as many female users. There are a few additonal areas we can look into for analysis.
 - We need to dive deeper into the trip start/end locations during the morning and afternoon rush hour times, more specifically on the downtown area. It would be imperative in a Des Moines location to set up convenient spots in the business/commercial sector downtown to cater to the potential audience. 
 - The data we had for this project was from August only. It would be important before fully committing to a bike sharing program in Des Moines to understand how the winter months would affect potential revenue streams. 

The Tableau story that we created for this project can be seen [here](https://public.tableau.com/app/profile/alexander.brown1088/viz/NYCCitiBike_16287211921270/NYCCitiBikeAnalysis).
