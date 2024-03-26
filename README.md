## Summary of the Housing Market Analysis Project

This document outlines a final project focused on analyzing the  impact of social and economic factors on the United States housing market from 2018 to 2023. 

**Data and Methodology:**

* The analysis is based on a dataset containing monthly data for factors like birth rates, death rates, inflation rates, unemployment rates, number of new listings, days-to-pending (time to receive an offer), sale-to-list price ratio, etc.
* The data was preprocessed to address missing values and redundancies.
* Linear regressions were employed to examine the relationships between various factors and target variables (number of new listings and sale-to-list price ratio).
* Sliding window validation was used to assess the appropriateness of linear regression models.

**Key Findings:**

* A positive correlation exists between the number of births and new listings, suggesting families with newborns are more likely to move. 
* There's a negative correlation between days-to-pending and sale-to-list price ratio, indicating houses on the market longer are sold for a lower price compared to the listing price.
* The number of new listings seems to be generally decreasing over the years, possibly due to factors beyond the scope of the data (e.g., COVID-19).
* The sale-to-list price ratio fluctuates over time, with a significant increase observed during 2021 and 2022.

**Limitations:**

* The dataset covers a relatively short period (2018-2023). 
* The analysis might be affected by multicollinearity (intercorrelation between independent variables).
* Certain factors like inflation rate and unemployment rate have limitations in their current form (e.g., not transformed for better modelling).

**Tools and libraries::**

* pandas
* numpy
* seaborn
* matplotlib
* and more
