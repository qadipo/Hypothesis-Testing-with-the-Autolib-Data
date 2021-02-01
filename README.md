# Hypothesis Testing with the Autolib data

## Introduction
The aim of this notebook is to demostate hypothesis testing process in a data science project.  

## Formulation of the Hypotheses
**Null Hypothesis:** The average number of Bluecars picked during the weekday in city of **Seine-Saint-Denis** is equal to the ones picked the city of **Val-de_Marne**

  Ho : μ1 = μ2 (μ1 is mean for Seine-Saint-Denis and μ2 is mean Val-de_Marne)

**Alternate Hypothesis:** The average number of Bluecars picked during the weekday from Seine-Saint-Denis is NOT equal to the ones picked from Val-de_Marne

  Ha : μ1 ≠ μ2

## Data Description
The data used for this study was taken from Autolib. Autolib was an electric car sharing service company in France that was operational between 2011 and 2018. The company had three types of electric cars i.e Bluecars, Utilib cars and Utilib 1.4 cars. Blue cars were most popularly used. These cars were available across various cities and postal codes in France and renters could pick up cars in one station then drop them off at a different station that was closer to their destination.
Below is a description of the columns of the data:
  1. Postal code -	postal code of the area (in Paris)
  2. date - date of the row aggregation
  3. n_daily_data_points	- number of daily data poinst that were available for aggregation, that day
  4. dayOfWeek -	identifier of weekday (0: Monday -> 6: Sunday)
  5. day_type -	weekday or weekend
  6. BlueCars_taken_sum -	Number of bluecars taken that date in that area
  7. BlueCars_returned_sum	- Number of bluecars returned that date in that area
  8. Utilib_taken_sum -	Number of Utilib taken that date in that area
  9. Utilib_returned_sum -	Number of Utilib returned that date in that area
  10. Utilib_14_taken_sum	- Number of Utilib 1.4 taken that date in that area
  11. Utilib_14_returned_sum	-  Number of Utilib 1.4 returned that date in that area
  12. Slots_freed_sum	- Number of recharging slots released that date in that area
  13. Slots_taken_sum	- Number of rechargign slots taken that date in that area
