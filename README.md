# PyBer_Analysis

## Overview of the PyBer Analysis
This analysis was performed to determine relationships between three types of cities (Urban, Suburban and Rural) and the number of drivers and riders, as well as the total weekly fares for each city type. In additon, the average fare per ride and the average fare per driver for each city type were determined.


### Resources
Data source: city_data.csv and ride_data.csv    

Software: Python 3.7.13, Pandas libraries, the Jupyter Notebook and Matplotlib 


## PyBer Analysis Results
The main goal of this analysis was to determine the hidden information in the city rides for three different types of cities: Urban, Suburban and and the Rural.  The goal was achieved by extracting the following information: 


### Average Fare per Ride and the Average Fare per Driver
As the first step, the total number of rides, fares and drivers was determined for each city type. Then the average fare per ride and the average fare per driver were computed by taking the ratio between total fare and total rides and also between total fare and total drivers. The summary table is shown below.

  ![Summary_table](https://user-images.githubusercontent.com/112113327/195687515-c5296e7c-1a41-4556-b0ca-af22b0a96ced.png)

According to the preceding table, it can be observed that there are 12 times more drivers in urban cities than the rural cities. On the other hand, the average fare per driver in rural cities is about 3 times more than that of urban cities. Also, the average fare per ride is more expensive in Rural cities than that of Urban and Suburban cities.  


### Weekly Total Fare for each City Type
As the second step, the total fare for each city type was considered. Then, the "resample" function was used to determine the weekly fare for each city type. The weekly fares from January, 2019 to April 2019 were considered for each city type and plot the following line graph to visualize the information.

  ![PyBer_fare_summary](https://user-images.githubusercontent.com/112113327/195691444-08c531e8-3523-4cd8-91d2-e48b165c12dc.png)

From the preceding graph, it can be observed that the weekly fare in urban cities are very high compared to the rural cities. The total fares in suburban cities are higher than rural cities, but less than the urban cities. Another interesting to see here is that the total fares in urban and suburban cities decreased in January, but it increased in rural cities.


## PyBer Analysis Summary
According to the information extracted from the two data sets, there are more drivers in urban cities than in suburban and rural cities. This leads to the low average fare for the drivers in urban cities than the drivers in suburban and rural cites. On the other hand, the riders in urban cities get better rates due to higher number of drivers. Also, this may be due to short distances, but there is no data to compare the distances. In the graph of the "total fare by city type", the total fare for urban and suburban cities are lower at the begining of the uear. This may be due to seasonal effecs. Finally, the suburban cities are better for riders compared to the riders in rural cities and also better for drivers compated to the drivers in urban cities.
