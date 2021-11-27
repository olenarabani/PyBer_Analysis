# PyBer_Analysis
# Overview 
 Using Python skills and knowledge of Pandas, need to create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, need to create a multiple-line graph that shows the total weekly fares for each city type. Finally, I’ll submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.
# Results
## 1. The total number of rides for each city type is retrieved.
## 2. The sum of the fares for each city type is retrieved.
## 3. The average fare per ride for each city type is calculated.
## 4. A PyBer summary DataFrame is created.
## 5. The PyBer summary DataFrame is formatted as shown in the example.
## 6. A DataFrame was created using the groupby() function on the "type" and "date" columns, and the sum() method is applied on the "fare" column to show the total fare amount for each date and time.
## 7. A DataFrame was created using the pivot() function where the index is the "date," the columns are the city "type," and the values are the "fare."
## 8. A DataFrame was created using the loc method on the date range: 2019-01-01 through 2019-04-29.

From the summary data frame, we can see that there is a trend between how populated a city is and the total number of rides, which directly affects the total number of drivers, total fare, and both averages. Although the total number of rides, drivers and fares decrease as the cities become farther from urbanized areas, the average fare per ride and per driver seems to increase. This can be explained by the accessibility of PyBer rides and drivers in rural areas. Less drivers in rural areas will may lead to a higher average fare per ride and driver, as prices increase when supply is low.

The number of rides seem peak at the end of February and fluctuates during the month of March. All the graphs tend to follow the same trend throughout these months, except for the trend in suburban cities, where we see a sharper increase during the month of April.

# Summary
 The total fare by city type  - increase during the month of April in suburban cities, the company should research as to what causes this increase,  because the total fare decreases for other types of cities.
 Average fare per ride and driver is higher when there are less drivers. Know this information, the company can influence ride-share prices by limiting or increasing the number of drivers during a certain time to achieve its profit goal.
The company may  to allocate more drivers to rural areas to optimize its profits. Because, the average fare per ride shows a gradual increase from more populated cites to less populated cities. However, the average fare per drive increases drastically when following the same trend. So, the number of drivers may be  lower than expected. 
