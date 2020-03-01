# Data-Visualization
# About the dataset 
You can find the dataset in the flights.zip folder. It is recommended to extract the dataset from this folder to parent directory before running the code. 
This dataset was gathered from RITA and contains a list of 583,985 flights that departed and arrived in the month of January, 2019 with many variables of interest like - departure time, arrival time, flight operator, delay reasons/times (NAS, security, carrier, etc.) and many more.

# About the analysis and visualization
I wanted to present the analysis in a way to focus on reasoning behind the flight delays, identify the worst performing carriers (in terms of maximum delayed flights) and identify the relationship between departure and arrival delays for all delayed flights.
I start my exploration with comparing average departure and arrival delays for each hour of departure time to analyze the best time for customers to catch a flight. 
Further, assuming that a flight is delayed if the actual arrival time is greater than the scheduled arrival time, I filter out the flight operators which have higher than the average number of delayed flights. I consider them as the worst performing operators to compare and reason the average departure and arrival time delays. 
Next, I use the filtered data (containing only delayed flight records), to analyze the correlation between departure and arrival delays, and further break it down to flight operator level, to make sure that the general correlation is applicable to each flight operator as well.

# Summary
1.Chicago had the highest average departure and arrival delay time. <br>
2.Phoenix, Philadelphia, and Minneapolis had the least average arrival delays. <br>
3.No flight delays were observed between 4AM and 9AM. <br>
4.Flight operators that had highest number of delays are:: WN - Southwest Airlines, OO - SkyWest Airlines, AA - American Airlines, DL - Delta Airlines, UA - United Airlines. <br>
5.B6 (or JetBlue) had the highest average departure and arrival delays because of late aircraft and/or carrier operations. DL (or Delta) and WN (or Southwest) have high average delays but low average arrival delays. UA (or United Airlines) is the most affected by National Air System performance which is the major reason for its flight delays. <br>
6.The first day of the week (Monday) has the highest average departure and arrival delays, majority of which can reasoned in terms of higher average late aircraft delays and delays caused by National Air System.<br>
