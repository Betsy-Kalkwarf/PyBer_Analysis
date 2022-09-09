# PyBer_Analysis

## Overview of the analysis: 
The purpose of the new analysis is to create a summary of the PyBer data by city type in a visually appealing way utilizing a dataframe. Once all the data can be seen in a table (dataframe), the data is then processed to show total weekly fares per city type. Using Pandas and Matplotlib, the data is used to create a line chart to show these sums.

## Results:
When looking at the PyBer data by city type summary dataframe, there are a lot of differences. The total amount of rides, drivers, and total fares correlate with the population density of the city type with urban areas having the largest and rural areas having the lowest. The average fare per ride and average fare per driver have an inverse trend, with the rural areas having the largest and urban areas having the lowest. This is probably because the rides are longer since destinations in rural areas are often more spread out than in urban areas. You can see the details in the dataframe below:
![alt text](“https://github.com/Betsy-Kalkwarf/PyBer_Analysis/blob/main/analysis/PyBer_Summary_df.png”)

When looking at the PyBer weekly total fare sum in the line chart, the peaks and valleys for each city type are somewhat related, with the biggest peak after mid-February. The fare sums are always highest for the urban city type followed by the suburban city type. The rural city type always has the lowest sum, which is to be expected after viewing the dataframe showing the much lower total rides count. See the line chart below:
![alt text](“https://github.com/Betsy-Kalkwarf/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png”)

## Summary:
After looking through the data summary, I suggest the following moves by PyBer:
Let rural drivers know they won’t have a lot of rides, but the rides they get will be longer and have larger fares than in suburban or urban areas. Make sure they are okay with long lulls in activities and longer rides.
There are too many urban drivers. In fact, there are more drivers (2,405) than total rides (1,625) in urban cities. I would recommend hiring less drivers to keep the drivers you have happy to continue working for PyBer.
I would suggest advertising PyBer more in suburban and rural areas to increase the volume of PyBer activity.
