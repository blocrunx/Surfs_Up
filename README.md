# Surfs Up
Analysis of Oahu weather

## Project Overview

Investors of the Surfs Up ice cream shop have asked for additional weather analysis for June and December to ensure that there are enough customers between seasons to sustain the business throughout the year. This analysis can be easily completed using two different methods, both of which will be used to ensure thorough analysis.
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
 
<img src="https://github.com/blocrunx/Surfs_Up/blob/master/img/june.png" width="100" height="200" />

December Summary Statistics:

<img src="https://github.com/blocrunx/Surfs_Up/blob/master/img/dec.png" width="100" height="200" />
 
In order to provide the investors with the most complete analysis possible, the following recommendations are being made:

- Further analysis to examine precipitation elsewhere in the world. December has more precipitation relative to June, however, it is not clear whether December has particularly high precipitation.
- Analysis of the precipitation patterns for the other ten months of the year.
- Further analysis to examine the temperatures throughout the year will help build a more complete monthly revenue projection.
- Analysis of local companies competing in the same market to identify whether the area can support another ice cream vendor.

  
