# **Nationwide CDC Vaccine Data Summary**
This data comes from the [CDC's vaccine data tracker](https://covid.cdc.gov/covid-data-tracker/#vaccinations), with additional population data from the U.S. Census. Please note that the data may differ from local numbers due to lags and differences in reporting.

This dataset has 3 spreadsheets:


* **historical\_cdc\_vac\_pops.csv:**  This sheet shows every day and every state for which we have vaccine data available. Please note that the CDC does not update data on weekends or holidays. (For example, dates Jan. 15, 16, 17, 18 have the same data because the last time the CDC updated was on Friday, Jan. 15, did not update on the weekend or the holiday, and then updated again on Jan 19.)
* **last\_week\_cdc\_vaccine\_rankings.csv:** This sheet is a subset of the **historical\_cdc\_vac\_pops.csv** showing only the data from seven days prior to the most recent data available. This sheet also has added rankings for the percent of distributed doses that have been administered, the percent of the over 16 population that has gotten the first dose, and the percent of the over 16 population that has gotten the second dose.
* **todays\_cdc\_vaccine\_rankings.csv:** This sheet is also a subset of the **historical\_cdc\_vac\_pops.csv** showing only the data for the most recent date available. This sheet also has added rankings for the percent of distributed doses that have been administered, the percent of the over 16 population that has gotten the first dose, and the percent of the over 16 population that has gotten the second dose.

Note: If a ranking has a ".5" on the end of it, that means it is tied with another state for that metric. So, if Texas and Virgina both have a ranking of "10.5," they are tied for 10th place.
