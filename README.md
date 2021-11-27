# PyBer Ride-Sharing Analysis

## Overview
PyBer Ride-sharing has requested an analysis of their 2019 ride-sharing data. This analysis requires:
- A summary DataFrame that includes
  - total rides,
  - total drivers,
  - total fares,
  - average rides, fares and drivers by city types
- Graphs to visualize the data
- A report that provides recommendations to the CEO on how the data might assist in decision-making.

## Resources
The analysis is built using Python in Jupyter Notebook. Three data files are provided for the analysis, and are located in the <a href="https://https://github.com/TeresaWehmeier/PyBer_Analysis/tree/main/Resources/">Resources folder</a>. MATPLOTLIB module is used to develop the graphs.

## Results
PyBer Ride-Share serves 120 cities, 55% of which are urban, while 30% are suburban and the remaining 15% are rural cities. There are 2375 rides recorded between 1/1/2019 and 5/28/2019. As expected, urban cities deliver the most rides, 1625 according to the data, or 68% of all rides. Urban cities also employee the highest number of drivers with 2405 (80%) of the 2973 employed by PyBer working within urban areas. The scatterplot below shows the ride-share distribution based on city type and number of rides, with circle size correlating to driver number per city.

### Scatterplot Describing Rides by City Type

<img src ="analysis/Fig1.png" width="50%" height="30%">

However, as the table below suggests, driver supply in urban cities exceeds current demand for rides in these cities.

### DataFrame Summary Table by City Type

<img src ="analysis/pyber_data_summary_table.png" width="60%" height="40%">

As we look at distribution of drivers, rides and fares by city types in a simple pie chart below, it is clear that ride and fare distributions for urban areas are well below driver distribution.

<img src = "analysis/Fig7.png" width="27%" height="30%">   <img src = "analysis/Fig5.png" width="25%" height="20%">   <img src = "analysis/Fig6.png" width="25%" height="20%">

Describe differences in ride-sharing data including total rides, fares and drivers. Avg fare per ride and driver, and total fare by city type.

## Summary
Statement summarizing three business recommendations to the CEO for addressing any disparities among the city types.
