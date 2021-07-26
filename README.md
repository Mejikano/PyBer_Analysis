# PyBer Analysis

### Resources
- Data source: city_data.csv and ride_data.csv
- Software: Python 3.7.10, Jupyter Notebook 6.3.0


## Overview

The leader of a ride-sharing company valued at $2.3 billion (Pyber) wants to analyze their rides performance and identify where more help and/or resources are required to continue improving the business profitability and understand how each city type performs and business actions to be taken for sustaining and growing the business. 



## Results

Below statements highlight the main differences for the city type analysis.

Based on the following City Summary table.

![Summary Table - City Type](https://github.com/Mejikano/PyBer_Analysis/blob/main/analysis/Summary_dataframe.png)


These are the main highlights

- Urban, the offer is greater than the demand. According to the analysis Urban type has  2,405 Drivers (offer) vs a 1,625 Total rides (demand)

- According to the 4 months analysis rides per driver ration are too low:
    Rural 1.6 rides per driver
    Suburban 1.3 rides per driver
    Urban 0.67 rides per driver

- Average fare per ride seems to be standard (~ 5 fare avg difference for Urban, Suburban and Rural ) but driver´s fare average is quite different: Rural 1.4 times greater than Suburban, Suburban 2.4 times greater than Urban and Suburban and Rural 3.4 times greater than Urban 

Based on the following Total fare by City Type Chart.

![Total Fare - City Type](https://github.com/Mejikano/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)


These are the main highlights

- The maximum Total Fare per City Type may have different seasonality,  although the three city types fares increase the last week of February; in April Rural reaches its Total Fare peak, Suburban drops and Urban slightly increases but it does not reach the maximum totals. Further seasonality analysis might be required.


## Summary 

Business Recommendation (assuming that the analyzed data is correct/accurate)

- Re-assess the business model, the number of rides per driver does not correspond to a sustainable ride-sharing as the number of rides are very low regardless of the driver profitability:  **drivers do not perform more than 1.6 rides in 4 months**

- Re-balance the number of drivers vs rides ratio, specially for the Urban City Types where offer is greater than the demand. This would increase drivers profitability (Fare per Driver) and keep the same competitive fare per ride average. Drivers profitability should be part of Pyber´s best interests as well, keeping happy drivers may improve ride services and increase customer satisfaction which eventually could derive into **more rides or beating the competition**. 

- For Rural City Types I would recommend to reduce the fare per ride average this could keep the average fare per driver competitive (close to Suburban or even a little bit higher due to rural infrastructure and more frequent vehicle maintenance) and increase the number of rides. As a side note, usually rural areas customers have less income than bigger cities customers (Urban or Suburban)





