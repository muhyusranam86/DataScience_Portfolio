# Project Goal
You're working as an analyst for Zuber, a new ride-sharing company that's launching in Chicago. Find patterns in the available information. Understand passenger preferences and the impact of external factors on rides. Study a database, analyze data from competitors, and test a hypothesis about the impact of weather on ride frequency.

## Test the hypothesis:
"The average duration of rides from the Loop to O'Hare International Airport changes on rainy Saturdays." Decide where to set the significance level (alpha) on your own. Explain:
* how you formed the null and alternative hypotheses
* what criterion you used to test the hypotheses and why

## Description of the data
A database with info on taxi rides in Chicago:
### neighborhoods table: data on city neighborhoods
* name: name of the neighborhood
* neighborhood_id: neighborhood code
* cabs table: data on taxis
* cab_id: vehicle code
* vehicle_id: the vehicle's technical ID
* company_name: the company that owns the vehicle
### trips table: data on rides
* trip_id: ride code
* cab_id: code of the vehicle operating the ride
* start_ts: date and time of the beginning of the ride (time rounded to the hour)
* end_ts: date and time of the end of the ride (time rounded to the hour)
* duration_seconds: ride duration in seconds
* distance_miles: ride distance in miles
* pickup_location_id: pickup neighborhood code
* dropoff_location_id: dropoff neighborhood code
* weather_records table: data on weather
* record_id: weather record code
* ts: record date and time (time rounded to the hour)
* temperature: temperature when the record was taken
* description: brief description of weather conditions, e.g. "light rain" or "scattered clouds"
### project_sql_result_01.csv. It contains the following data:
* company_name: taxi company name
* trips_amount: the number of rides for each taxi company on November 15-16, 2017.
### project_sql_result_04.csv. It contains the following data:
* dropoff_location_name: Chicago neighborhoods where rides ended
* average_trips: the average number of rides that ended in each neighborhood in November 2017.

# Libraries Used
* Pandas
* Matplotlib.pyplot
* seaborn
* scipy.stats
* numpy
* plotly
