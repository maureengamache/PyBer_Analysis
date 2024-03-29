## PyBer_Analysis

## Project Overview
V. Isualize has given you and Omar a brand-new assignment. Using your Python skills and knowledge of Pandas, you’ll create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type. Finally, you’ll submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

## Resources
* Data Source: city_data.csv, ride_data.csv

* Software: Python 3.10.6, Visual Studio Code, Jupyter Lab

## Analysis and Results
Overall, the urban cities have the most rides, while the rural cities have the least rides. Additionally, the urban cities have the most drivers, while the rural cities have the least drivers. Total revenue (fares) is the highest in the urban cities and the lowest in the rural citites. However, when looking at the average fare per ride and the average fare per dirver the rural cities have a higher per ride fare and per driver fare, than the urban cities. Suburban cities are steadily in the "middle" for all catergories of interest, falling between urban and rural citites for total rides, drivers, and fares; and between rural and urban cities, for average fare per ride and average fare per driver (see *figure 1* below). 

When analyzing total fare by city type (see *figure 2* below), the same results were noted for the urban cities, having the highest total fare week by week from January to April, followed by the suburban cities and the rural cities having the lowest fares by city type week by week from January to April. Upon review of the line graph, it is noted that the fares are the highest in rural cities at the beginning of April. The fares in suburban cities are highest at the end of Feburary, and the fares in urban cities are the highest end of February and the beginning of March. Conversely, the lowest fares by city type week by week from January to April, are January, for both urban and rural cities, and March for suburban cities. 

### Ride-sharing data summary (*Figure 1*) 

![PyBer Summary DataFrame](https://github.com/maureengamache/PyBer_Analysis/blob/main/PyBer%20Summary%20DataFrame.png)

### Ride-sharing line graph (*Figure 2*) 

![Total Fare by City Type](https://github.com/maureengamache/PyBer_Analysis/blob/main/Total%20Fare%20by%20City%20Type.png)

## Summary:
Given the results and analysis above, there are three recommendations that I would suggest to the CEO of PyBer. First, assuming that demand for rides is constant across the three types of cities, in the month of January, I would redistribute drivers from the urban cities to suburban cities, or provide incentives for drivers to accept fares in the suburban citites in order to maximize revenue. Second, at the end of March and beginning of April, I would reallotcate or incentivize drivers to accept fares in rural cities rather than suburban cities. Finally, at the beginning of March, I would reallocate or incentivize drivers to  accept fares in urban cities rather than suburban cities. By making these adjustments, profits will increase overall for PyBer.
