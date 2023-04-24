# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
1.Request,Collect and explore data from citybikes of Chicago city.
2.Request,Collect and explore data from Foursquare API of all POI(Point of intrest) in 1000m radius of Bike Stations of city Chicago.
3.Request,Collect and explore data from YELP API of all POI(Point of intrest) in 1000m radius of Bike Stations of city Chicago.
4.Join data you resived from all three API and crate Database in sqlite3.
5.Build a regression model using Python’s `statsmodels` module that demonstrates a relationship between the number of bikes and the characteristics of the POIs. 
## Process
step 1 : Request and collect data from all three API as requirment of project.
step 2 : Remove duplicates and validate data.
step 3 : Combine data as required and join information recived from all the APIs and create DataFrame and database.
step 4 : Build regration Model for finding relation between number of bikes available and characteristics of the POIs in that location.
step 5 : Review all data,regretion model and created database to collect information.

## Results
(fill in what you found about the comparative quality of API coverage in your chosen area and the results of your model.)
result 1 : Chicago has more than 1000 bike stations around city.
result 2 : Mostly more than two of bike station share the area around 1000m radius.
result 3 : I choose three POI Restaurants, bar and Art&Entertainment.Many of POI has more than one bike station in radius of 1000m.
result 4 : Number of available bikes is between 2 to 15 for most POI areas.
result 5 : POI counts and rating does impact the number of bikes.
result 6 : Increase in rating has positive impact on number of bikes.

## Challenges 
1. Requesting data to APIs with perticular params.
2. Choose city with lot of bike stations hence recive large number of
data with lot of duplicates.
3. Forgot to  give unique id column to YELP and Foursqure APIs so got stuck in joining data hence restart all process.
4. Hard to understand requirment of question.


## Future Goals
1. Look all parts of project understand flow and requirments then start.
2. Request for data with all required params carefully.
3. Observe,understand and explore all the aspects of data recived before performing EDA.