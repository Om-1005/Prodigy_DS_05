# PRODIGY_DS_05
# TASK: 
Analyze traffic accident data to identify patterns related to road conditions, weather, and time of day. Visualize accident hotspots and contributing factors.
# About the Dataset
This <a href="https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents">dataset</a> covers car accidents in 49 states of the USA from February 2016 to March 2023. It includes around 7.7 million accident records collected from various sources like transportation departments, law enforcement, cameras, and traffic sensors.
| # | Attribute             | Description                                                                                               |
|---|-----------------------|-----------------------------------------------------------------------------------------------------------|
| 1 | ID                    | This is a unique identifier of the accident record.                                                        |
| 2 | Severity              | Shows the severity of the accident, a number between 1 and 4, where 1 indicates the least impact on traffic and 4 indicates a significant impact on traffic. |
| 3 | Start_Time            | Shows start time of the accident in local time zone.                                                       |
| 4 | End_Time              | Shows end time of the accident in local time zone. End time here refers to when the impact of accident on traffic flow was dismissed. |
| 5 | Start_Lat             | Shows latitude in GPS coordinate of the start point.                                                       |
| 6 | Start_Lng             | Shows longitude in GPS coordinate of the start point.                                                      |
| 7 | End_Lat               | Shows latitude in GPS coordinate of the end point. (Nullable)                                              |
| 8 | End_Lng               | Shows longitude in GPS coordinate of the end point. (Nullable)                                             |
| 9 | Distance(mi)          | The length of the road extent affected by the accident.                                                    |
|10 | Description           | Shows natural language description of the accident.                                                         |
|11 | Number                | Shows the street number in address field. (Nullable)                                                        |
|12 | Street                | Shows the street name in address field. (Nullable)                                                          |
|13 | Side                  | Shows the relative side of the street (Right/Left) in address field. (Nullable)                            |
|14 | City                  | Shows the city in address field. (Nullable)                                                                 |
|15 | County                | Shows the county in address field. (Nullable)                                                               |
|16 | State                 | Shows the state in address field. (Nullable)                                                                |
|17 | Zipcode               | Shows the zipcode in address field. (Nullable)                                                              |
|18 | Country               | Shows the country in address field. (Nullable)                                                              |
|19 | Timezone              | Shows timezone based on the location of the accident (eastern, central, etc.). (Nullable)                   |
|20 | Airport_Code          | Denotes an airport-based weather station which is the closest one to location of the accident. (Nullable)   |
|21 | Weather_Timestamp     | Shows the time-stamp of weather observation record (in local time). (Nullable)                              |
|22 | Temperature(F)        | Shows the temperature (in Fahrenheit). (Nullable)                                                           |
|23 | Wind_Chill(F)         | Shows the wind chill (in Fahrenheit). (Nullable)                                                            |
|24 | Humidity(%)           | Shows the humidity (in percentage). (Nullable)                                                              |
|25 | Pressure(in)          | Shows the air pressure (in inches). (Nullable)                                                              |
|26 | Visibility(mi)        | Shows visibility (in miles). (Nullable)                                                                     |
|27 | Wind_Direction        | Shows wind direction. (Nullable)                                                                            |
|28 | Wind_Speed(mph)       | Shows wind speed (in miles per hour). (Nullable)                                                            |
|29 | Precipitation(in)     | Shows precipitation amount in inches, if there is any. (Nullable)                                          |
|30 | Weather_Condition     | Shows the weather condition (rain, snow, thunderstorm, fog, etc.) (Nullable)                                |
|31 | Amenity               | A POI annotation which indicates presence of amenity in a nearby location.                                  |
|32 | Bump                  | A POI annotation which indicates presence of speed bump or hump in a nearby location.                        |
|33 | Crossing              | A POI annotation which indicates presence of crossing in a nearby location.                                 |
|34 | Give_Way              | A POI annotation which indicates presence of give_way in a nearby location.                                  |
|35 | Junction              | A POI annotation which indicates presence of junction in a nearby location.                                  |
|36 | No_Exit               | A POI annotation which indicates presence of no_exit in a nearby location.                                   |
|37 | Railway               | A POI annotation which indicates presence of railway in a nearby location.                                   |
|38 | Roundabout            | A POI annotation which indicates presence of roundabout in a nearby location.                                |
|39 | Station               | A POI annotation which indicates presence of station in a nearby location.                                   |
|40 | Stop                  | A POI annotation which indicates presence of stop in a nearby location.                                      |
|41 | Traffic_Calming       | A POI annotation which indicates presence of traffic_calming in a nearby location.                           |
|42 | Traffic_Signal        | A POI annotation which indicates presence of traffic_signal in a nearby loction.                             |
|43 | Turning_Loop          | A POI annotation which indicates presence of turning_loop in a nearby location.                             |
|44 | Sunrise_Sunset        | Shows the period of day (i.e. day or night) based on sunrise/sunset. (Nullable)                             |
|45 | Civil_Twilight        | Shows the period of day (i.e. day or night) based on civil twilight. (Nullable)                             |
|46 | Nautical_Twilight     | Shows the period of day (i.e. day or night) based on nautical twilight. (Nullable)                          |
|47 | Astronomical_Twilight | Shows the period of day (i.e. day or night) based on astronomical twilight. (Nullable)                      |

# Findings from Analysis
=====================================================

### Our comprehensive analysis of accident data has uncovered several crucial patterns and trends:

* **Miami**: Highest accident rate, likely due to high population density and traffic volume.
* **Star Junction and Stromsburg**: Lower accident rates due to smaller size and lower traffic.
* **California**: Most accidents, reflecting large population and extensive road network.
* **South Dakota**: Fewest accidents, likely due to lower population density and traffic volume.

### Accident Characteristics

* **Severity**: Majority of accidents fall into severity level 2, indicating high number of non-fatal incidents.
* **Weather**: Fair weather conditions prevalent during accidents, implying factors like driver behavior and traffic congestion may play more significant role than weather in accident causation.
* **Time of Day**: Morning rush hour appears to be most accident-prone time of day, possibly due to increased traffic congestion.

This analysis provides valuable insights for policymakers and urban planners to inform strategies to improve road safety.
## Contact Information

- Email 📧: omtamkhane97@gmail.com
