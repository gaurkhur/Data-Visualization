# Data-Visualization
# About the dataset 
You can find the dataset in the flights.zip folder. It is recommended to extract the dataset from this folder to parent directory before running the code. 
This dataset was gathered from RITA and contains a list of 583,985 flights that departed and arrived in the month of January, 2019 with many variables of interest like - departure time, arrival time, flight operator, delay reasons/times (NAS, security, carrier, etc.) and many more.

# About the analysis and visualization
I wanted to present the analysis in a way to focus on reasoning behind the flight delays, identify the worst performing carriers (in terms of maximum delayed flights) and identify the relationship between departure and arrival delays for all delayed flights.
I start my exploration with comparing average departure and arrival delays for each hour of departure time to analyze the best time for customers to catch a flight. 
Further, assuming that a flight is delayed if the actual arrival time is greater than the scheduled arrival time, I filter out the flight operators which have higher than the average number of delayed flights. I consider them as the worst performing operators to compare and reason the average departure and arrival time delays. 
Next, I use the filtered data (containing only delayed flight records), to analyze the correlation between departure and arrival delays, and further break it down to flight operator level, to make sure that the general correlation is applicable to each flight operator as well.

