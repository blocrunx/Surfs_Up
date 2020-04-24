# Surfs Up
Analysis of Oahu weather

## Project Overview

Investors of the Surfs Up icecream shop have asked for additional weather analysis for June and December to ensure that there are enough customers between seasons to sustain the business throughout the year. This analysis can be easily completed using two different methods, both of which we will use to ensure we do a thorough job.
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
  
  
