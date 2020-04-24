# Surfs Up
Analysis of Oahu weather

## Project Overview

Investors of the Surfs Up icecream shop have asked for additional weather analysis for June and December to ensure that there are enough customers between seasons to sustain the business throughout the year. This analysis can be easily completed using two different methods, both of which will be used to ensure the analysis is thorough.
- First Method:
  - Query Measurements.date and Measurements.prcp objects.
  - Use extract function to get the precipitation data for June across all years.
  - Store the results in a Python list.
  - Convert the results list to a Pandas DataFrame.
  - Use Pandas .describe() function for obtain summary statistics.
- Second Method:
  - Query Measurements.date and Measurements.prcp objects.
  - Store results for every date into results list.
  - Convert results list to a Pandas DataFrame.
  - Convert date column to datetime datatype.
  - Use Pandas loc attribute get the precipitation results for December.
  
## Resources
- Data Source: hawaii.sqlite
- Database: SQLite 3.31
- Languages: Python 3.7.6
- Software: Jupyter Lab 1.2.6, SQLAlchemy 1.3

## Summary

- The analysis of Oahu weather between 2010 and 2017 has revealed the following insights: 
  - The mean daily precipitation in June is 0.14 cm which is 0.08 cm less than December at 0.22 cm.
  - The standard deviation for precipitation in June is 0.34 cm which is 0.2 cm less than December at 0.54 cm.
  - The median daily precipitation for June is 0.02 cm which is 0.01 cm less that December at 0.03 cm.
- These data show that December's precipitation is relatively significant. Not only is the amount of precipitation higher for December as indicated by the mean value, the weather is also more unpredictable as indicated by the standard deviation.

June Summary Statistics:
 
![june](img/june.png = 20x100)

 
In order to provide the investors with the most complete analysis possible, the following reccomendations are being made:

- Further analysis to examine precipitation elsewhere in the world. With this limited analysis it is clear that December has more precipitation relative to June, however, it does not necessarily mean December has particularly high precipitation. 
- Analysis of the precipitation patterns in the other ten months of the year.
- Further analysis to examine the temperatures thoughout the year. This will help build a more complete revenue projection for each month.
- Analysis of local companies competing in the same market to identify whether the area can support another ice cream vendor.

  
