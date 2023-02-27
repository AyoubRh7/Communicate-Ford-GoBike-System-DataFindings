# Exploring the Factors that Affect the Duration of Ford Bike Trips.
## by Ayoub RHOUTTAISS


## Dataset

The 2019 Ford bike ride dataset is a comprehensive collection of information on over 183215 bike rides taken using Ford bikes. This dataset holds a wealth of information and is comprised of 16 distinct columns, each providing valuable insights into various aspects of the bike rides. The data contained in this dataset was carefully collected and curated, making it a valuable resource for anyone looking to gain a deeper understanding of the Ford bike ride experience. With this dataset, we are able to delve into the details of each bike ride, from :
* start_time: The time the ride started
* end_time: The time the ride ended
* duration_sec: The length of the ride in seconds
* start_station_id: The id of the station where the ride began
* end_station_id: The id of the station where the ride ended
* start_station_name: The id of the station where the ride began
* end_station_name: The name of the station where the ride ended
* start_station_latitude: The GPS coordinates of the start station
* end_station_latitude: The GPS coordinates of the end station
* bike_id: The id of the bike used for the ride
* user_type: The type of user who rented the bike 
* member_gender: The gender of the user who rented the bike
* member_age: The age of the user who rented the bike

#### Data wrangling steps:
* Remove the record with critical missing values in the "start_station_id".
* Convert the "start_station_id" and "end_station_id" columns to integer data type.
* Convert the "start_time" and "end_time" columns to datetime data type.
* create a new column "member_age"  by subtracting the values in the "member_birth_year"   column from the current year 2023.

## Summary of Findings

The 2019 Ford bike ride dataset analysis revealed that trip duration is concentrated between 1 and 200 minutes, with men being the largest group of riders. Young people between the ages of 20 and 40 are the most represented age group and tend to take the longest trips. Customers also tend to take longer trips compared to subscribers. The analysis showed a clear correlation between age and trip duration, with younger people taking the longest trips. Females and customers tend to take the longest trips, but the disparity in the number of rides taken by males and females makes it difficult to draw a definite conclusion about trip duration differences between the two genders. However, the data suggests that youngs, females and customers are the demographic groups primarily responsible for taking long trips.

## Key Insights for Presentation

- The distribuation of trips duartion.
- The correlation between trip duartion and membre age.
- The correlation between trip duartion and membre gender. 
- The correlation between trip duartion and user type.