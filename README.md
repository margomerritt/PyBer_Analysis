# PyBer Analysis
## Overview of Project
### Purpose
The purpose of this project is to perform an exploratory analysis on data for Pyber, a Python-based ridesharing app company. The goal is to produce visualizations and analysis that will help Pyber improve access to ridesharing services and determine afforadibility for underserved neighborhoods. This project utilizes Pandas libraries, Jupyter Notebook, and Matplotlib to produce these visualizations. 

The dataset was provided in two large CSV files: city_data.csv and ride_data.csv. The file city_data.csv had three columns of data: the city name, the driver count, and the type of city (Urban, Suburban, or Rural). The file ride_data.csv had four columns of data: the city name, the date, the fare amount, and the ride id number. The city_data.csv file had 120 rows of entries in the dataset while the ride_data.csv file had 2375 entries. 
### Resources 
* Data Source: city_data.csv, ride_data.csv
* Software: Python 3.9.12, Jupyter Notebook 6.4.8, Matplotlib 3.5.1, Pandas 1.4.2
## Results
### Deliverable 1
In Deliverable 1 we produced a ride-sharing summary DataFrame by city type. This chart has the type of city as the index. The three types of cities are Urban, Suburban, and Rural. Five columns of data are displayed in this chart: Total Rides, Total Drivers, Total Fares, Average Fare per Ride, and Average Fare per Driver. 

![Screen Shot 2022-11-04 at 3 51 36 PM](https://user-images.githubusercontent.com/111299372/200063240-c6e0ab9f-ffe0-4677-850b-2307e950b3c2.png)

From this chart we see that urban city type has the highest total rides at 1625. The suburban city type has a total of 625 total rides while the rural areas have the least amount of total drivers at 125. Since there is a higher demand for rides in urban areas it makes sense that urban areas have the highest driver count at 2405. Rural areas have the least amount of drivers at a count of 78 total drivers. The same logic applies to rrban city type having the highest total fare amount at $39854.38. 

The highest average fare per ride is $34.62 for the rural city type. There is less demand in rural areas so this could lead to a higher fee compared to suburban and urban areas. Rides in rural areas also travel a further distance to get to their destination point compared to suburban and urban rides. A longer drive will result in a higher fare for the rural city type. Suburban areas have an average of a $30.97 fare per ride. Urban areas have the cheapest average fare per ride at $24.52. 

Because the rural rides have a higher average fare per ride this results in a higher average fare per driver. Since Rural areas have the highest average fare per driver they also have the highest average fare per driver at $55.48. Suburban areas have an average fare per driver of $39.5 since there driving distance is less than rural areas but more than urban areas. Urban areas have the least average fare per driver at $16.57. 

### Deliverable 2
In Deliverable 2 we produced a multiple-line chart of total fares for each city type. This graph was filtered to display data between the dates of 01/01/2019 and 04/28/2019. The x-axis displays the months January, February, March, and April. The y-axis displays the fare in USD. The graph displays three lines. One for each city type: Urban, Suburban, and Rural. 

![PyBer_fare_summary](https://user-images.githubusercontent.com/111299372/200067229-ba55d471-2e47-4a22-8274-035515b647a2.png)

From the multiple-line chart we see that urban rides had the highest total fare for the months displayed. Suburban areas had the second highest total fares and the rural areas had the lowest total fares. Thus we can conclude that urban areas are the most profitable for ride-sharing services while rural areas are the least profitable. 
## Summary
The visualizations produced in Deliverable 1 and 2 can be used to help improve access to ridesharing services and to determine affordability for underserved neighborhoods. From this analysis we see that rural areas are underserved neighborhoods. Rural areas only had 125 total rides, but they only had 78 total drivers to service these rural areas. Having less drivers than total rides seems to be a disadvantage. The urban areas have 780 more drivers than total rides making it more accessible for urban areas than for rural or suburban areas. One step to take to increase accessibility of ridesharing is to offer more drivers in these underserved communities. 

From the multiple-line chart in Deliverable 2 we see that there is a peak in total fares for all three city types towards the end of February. During this time there appears to be a peak in the need and used of ridesharing. Another way to make ridesharing more affordable for underserved communities is to offer a discount during peak times when ridesharing is needed the most. From the data we see that rural areas had the least amount of total rides. This could be contributed to the fact that rural areas have the highest average fare per ride out of all three city types. One way to encourage more rural riders is to work on decreasing the cost. There are several ways to do this depending on how the fare rate is already set up. Offering a discount rate after a certain mileage will encourage rural riders to use ridesharing services since their trips often cover longer distances.






