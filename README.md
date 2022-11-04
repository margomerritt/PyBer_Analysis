# PyBer Analysis
## Overview of Project
### Purpose
The purpose of this project is to perform an exploratory analysis on data for Pyber, a Python-based ridesharing app company. The goal is to produce visualizations and analysis that will help Pyber improve access to ridesharing services and determine afforadibility for underserved neighborhoods. This project utilizes Pandas libraries, Jupyter Notebook, and Matplotlib to produce these visualizations. 

The dataset was provided in two large CSV files: city_data.csv and ride_data.csv. The file city_data.csv had three columns of data: the city name, the driver count, and the type of city (Urban, Suburban, or Rural). The file ride_data.csv had four columns of data: the city name, the date, the fare amount, and the ride id number. The city_data.csv file had 120 rows of entries in the dataset while the ride_data.csv file had 2375 entries. 
### Resources 
* Data Source: city_data.csv, ride_data.csv
* Software: Python 3.9.12, Jupyter Notebook 6.4.8, Matplotlib 3.5.1, Pandas 1.4.2
## Results
In Deliverable 1 we produced a ride-sharing summary DataFrame by city type. This chart has the type of city as the index. The three types of cities are Urban, Suburban, and Rural. Five columns of data are displayed in this chart: Total Rides, Total Drivers, Total Fares, Average Fare per Ride, and Average Fare per Driver. 

![Screen Shot 2022-11-04 at 3 51 36 PM](https://user-images.githubusercontent.com/111299372/200063240-c6e0ab9f-ffe0-4677-850b-2307e950b3c2.png)

From this chart we see that Urban city type had the highest total rides at 1625. The Suburban city type has a total of 625 total rides while the Rural areas have the least amount of total drivers at 125. Since there is a higher demand for rides in urban areas it makes sense that urban areas have the highest driver count at 2405. Rural areas have the least amount of drivers at a count of 78 total drivers. The same logic applies to Urban city type having the highest total fare amount at 39854.38 dollars. 

The highest average fare per ride is 34.62 dollars for the Rural city type. There is less demand in Rural areas so this could lead to a higher fee compared to suburban and urban areas. Rides in rural areas also travel a further distance to get to their destination point compared to Suburban and Urban rides. A longer drive will result in a higher fare. 



## Summary
