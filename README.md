# PyBer_Analysis


## Challenge


##### Pyber Summary by City Type
<table border="1" class="dataframe" style="width:100%">
  <thead>
    <tr align= "center;">
      <th>City Type</th>
      <th>Total Rides</th>
      <th>Total Drivers</th>
      <th>Total Fares</th>
      <th>Average Fare per Ride</th>
      <th>Average Fare per Driver</th>
    </tr>
  </thead>
  <tbody>
    <tr align="right">
      <th>Rural</th>
      <td>125</td>
      <td>78</td>
      <td>$4,327.93</td>
      <td>$34.62</td>
      <td>$55.49</td>
    </tr>
    <tr align="right">
      <th>Suburban</th>
      <td>625</td>
      <td>490</td>
      <td>$19,356.33</td>
      <td>$30.97</td>
      <td>$39.50</td>
    </tr>
    <tr align="right">
      <th>Urban</th>
      <td>1,625</td>
      <td>2,405</td>
      <td>$39,854.38</td>
      <td>$24.53</td>
      <td>$16.57</td>
    </tr>
  </tbody>
</table>


##### Observations:
+ Urban cities make up a majority of the business, with 68% of rides and 63% of fares.
  + Urban ride activity is 13 times greater than in rural cities and 2.6 times more than suburban.
  + Total fares are higher by 9.2 times than rural and 2.1 times for suburban.
+ Urban driver count exceeds ride count by 780, which translates into an average number of rides per driver of 0.7.  Rural and suburban cities' ride counts exceed driver count, with average trips per driver at 1.6 and 1.3, respectively.  These differences in ratio to rides per driver explain the change we see in Average Fare per Ride and Average Fare per Driver by city type, with the average urban driver earning less than the average fare amount for the market.
+ There is slightly more than a $10 spread between the Average Fare per Ride between the urban and rural markets.  While the average distance of trips between the city types may be a contributing factor to the variance in Average Fare per Ride, the overabundance of drivers in Urban markets compared to the scarcity of drivers in rural and suburban cities is most likely a significant factor.
+ The more abundant supply of drivers and lower average fares may lead to higher customer satisfaction in the urban markets. Still, conversely, it may lead to lower driver satisfaction and potentially higher turnover.



##### Weekly Fares by Market



![](https://github.com/kenwelsh/PyBer_Analysis/blob/master/analysis/Fig8_Challenge.png "Total Fare by City Type Chart")


##### Observations:
+ Urban market total fares are running between $1,943 and $2,471 per week, with an overall average of $2,267.
+ The suburban cities' total fares are between $785 and $1,413 per week, with an overall average of $1,049.
+ Rural cities are between $96 and $501 per week, with an overall weekly average of $237.


##### Summary
The Urban markets represent the highest ride activity and total fares, but the abundance of drivers is contributing to an overall lower fare per trip.  With driver count exceeding ride volume in the urban cities, overall revenue per driver is significantly lower than we see in suburban and rural markets.  Based on the weekly data reflected in the Total Fare by City Chart, the average urban driver is earning between $0.81 and $1.03 in fares per week, or an overall weekly average of $0.94.  That compares to a minimum of $1.60, a maximum of $2.88, and a weekly average of $2.14 for suburban drivers.  Rural drivers are earning the highest weekly fares per driver, ranging from $1.23 to $6.43, with an overall average of $3.03.


It may be valuable to look at customer and driver satisfaction to see if there is any correlation between those measures and driver scarcity and average fare in a market.  Reducing driver saturation in a market may lead to higher average fares and overall revenue, leading to greater driver earnings and satisfaction without adversely impacting customer satisfaction.
