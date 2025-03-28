#  Analyzing Bikeshare Trends and Usage Patterns (2015–2017)

This data science project explores the trends and usage patterns of New York City's Citi Bike system from 2015 to 2017. The analysis provides insights into urban mobility and the evolving role of bikeshare systems in city transportation as they grow in popularity.

## Motivation & Objectives

**Motivation:**  
Urban mobility is rapidly evolving, and bikeshare systems like Citi Bike play a key role in sustainable, convenient transportation. I wanted to dive into the data to understand how usage patterns have changed over time, and how the bikeshare system could be potentially optimized.

**Objectives:**
- Analyze growth in ridership and usage trends.
- Identify peak usage times and popular routes.
- Explore the impact of external factors on bikeshare patterns.
- Present clear, visual insights that can inform urban planning and transportation strategies.

----

**Dataset Details:**
This data comes from user Nikhil Akki on Kaggle, who transformed a regular open data release from the NYC Citi Bike's website.
It can be found [here.](https://www.kaggle.com/datasets/akkithetechie/new-york-city-bike-share-dataset/data?select=NYC-BikeShare-2015-2017-combined.csv)
# Breakdown of the datasets columns: 
* Trip Duration: numerical column, represents the length of the riders' trip in seconds.
* Start time: text column that contains the year, month, day, and time that the user began their ride.
* Stop time: text column that contains the year, month, day, and time that the user completed their ride.
* Start Station ID: numerical, contains a unique 4 digit number that identifies where the user began their trip.
* Start Station Name: text, gives the name of the location that the user began their trip. Tied to Start/End Station ID.
* Start Station Latitude: numeric, gives us the latitude that the user began their trip.
* Start Station Longitude: numeric, gives us the longitude that the user ended their trip.
* End Station ID: numerical, contains a unique 4 digit number that identifies where the user began their trip. IDs are Shared with Start Station ID.
* End Station Name: text, tells us the location where the user ended their trip.
*End Station Latitude: numeric, tells us the latitude that the user ended their trip.
* End Station Longitude: numeric, tells us the longitude that the user ended their trip.
* Bike ID: numeric, unique set of numbers that identifies the specific bike used.
* User type: categorical, Customer indicates a 24 hour or 3 day pass user, while Subscriber indicates an annual member.
* Birth Year: numeric, gives us the year that the rider was born in.
* Gender: categorical, tells us the gender of the rider. 0=unknown, 1=male, and 2=female.
* Trip_Duration_in_min: numeric, tells us how many minutes the user rode for in a given trip. (Not as precise as the Trip Duration column)

