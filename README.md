## Principles-of-Urban-Informatics-Project

## Bike Infrastructure Accessibility and Safety in NYC

Please find the paper for the project [here](https://github.com/ajay1808/Principles-of-Urban-Informatics-Project/blob/main/PUI%20Final%20Paper.pdf)


The research aims to explore the current accessibility of bike-friendly infrastructure in NYC and its distribution among different communities. Additionally, the study will investigate the relationship between bike-friendly infrastructure and bike accidents in the city.

### Data Preparation:

[Accident Data](https://github.com/ajay1808/Principles-of-Urban-Informatics-Project/blob/main/Accident%20Data%20Prep.ipynb): Finding the count of docks in each zipcode of NYC. This yields the following this [dataset](https://github.com/ajay1808/Principles-of-Urban-Informatics-Project/blob/main/Accidents_Normalized_Zipcodes.csv)

[Citibike](https://github.com/ajay1808/Principles-of-Urban-Informatics-Project/blob/main/Citibike_Infrastructure.ipynb):Finding the count of citibike in each zipcode of NYC. This count is normalized by the Citibike Ridership count for each zipcode. [output](https://github.com/ajay1808/Principles-of-Urban-Informatics-Project/blob/main/citibike_merge.csv)

[Bike Infrastructure](https://github.com/ajay1808/Principles-of-Urban-Informatics-Project/blob/main/NYC%20Bike%20Infrastructure%20Density.ipynb): This calculates the bike infrastructure by dividing the length of bike lanes by the length of roads. [Output](https://github.com/ajay1808/Principles-of-Urban-Informatics-Project/blob/main/Bike%20Infrastructure%20Density.csv)

[Income](https://github.com/ajay1808/Principles-of-Urban-Informatics-Project/blob/main/Zipcode_NYC_prep.ipynb): Mean income of each Zipcode. [Output](https://github.com/ajay1808/Principles-of-Urban-Informatics-Project/blob/main/NYC_Income.csv)


### Data Compilation

All the above datasets were merged to compare the statistics in each zipcode. Yielding this [output](https://github.com/ajay1808/Principles-of-Urban-Informatics-Project/blob/main/Features_Zipcode_Final.csv)

### Regression Models

[Accidents vs bike infrastructure](https://github.com/ajay1808/Principles-of-Urban-Informatics-Project/blob/main/Accidents%20vs%20Bike%20Infrastructure.ipynb)

[Demographic vs Bike Lane Density](https://github.com/ajay1808/Principles-of-Urban-Informatics-Project/blob/main/Demographic%20vs%20Bike%20Lane%20Density_2.ipynb)
