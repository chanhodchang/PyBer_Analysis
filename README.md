# PyBer_Analysis
Using Juypter Notebook to analyze ride-sharing data

## Project Overview
The lead data analyst for the company PyBer requested a presentation for trends in PyBer's ride-sharing data. Three different charts were created.

1. Create a bubble chart that showcases the average fare versus the total number of rides with bubble size based on the total number of drivers for each city type, including urban, suburban, and rural.
2. Create a bubble chart that showcases the average fare versus the total number of rides with bubble size based on the total number of drivers for three city types.
3. Determine the mean, median, and mode for the following:
  - The total number of rides for each city type.
  - The average fares for each city type.
  - The total number of drivers for each city type.
4. Create box-and-whisker plots that visualize each of the following to determine if there are any outliers:
  - The number of rides for each city type.
  - The fares for each city type.
  - The number of drivers for each city type.
5. Create a pie chart that visualizes each of the following data for each city type:
  - The percent of total fares.
  - The percent of total rides.
  - The percent of total drivers.
  
## Resources
- Data Source: city_data.csv, PyBer_ride_data.csv, ride_data.csv
- Software: Python 3.6.1, conda 4.7.12, matplotlib 3.1.1

## Summary
The analysis of the ride share data show that:
- There are more total number rides in the Urban cities
- The average fare is higher in the Rural cites
- Looking at the Ride Count Data, Urban cities has the largest array in number of rides.
- The summary dataframe below shows the total rides, drivers, and fares per city type.
- The summary also shows the average fare per ride and average fare per driver for each city type.

|          | Total Rides | Total Drivers | Total Fares | Average Fare per Ride | Average Fare per Driver |
|----------|-------------|---------------|-------------|-----------------------|-------------------------|
| Rural    | 125         | 78            | $4,327.93   | $34.62                | $55.49                  |
| Suburban | 625         | 490           | $19,356.33  | $30.97                | $39.50                  |
| Urban    | 1,625       | 2,405         | $39,854.38  | $24.53                | $16.57                  |

- The multiple line graph shows the total amount of fares from January to April for each city type. 
- The average total fare for Rural cities is below $500
- The average total fare for Urban cities starts around $1500 to and fluctuating between $2000 and $2500
- The average total fare for Suburban cities had a slight spike in late February and April to $1500
