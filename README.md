# Seattle-Airbnb-Data-Analysis-2016
Data Analysis of 1M+ Seattle Airbnb records in 2016 to find pricing trends and booking patterns with python and using excel for data recording.

# Tools used
- Python
- Pandas
- Matplotlib
- Seaborn
# Analysis Done
- Avg prices from month to month
- Price disributution
- Room availability across months
- Avg price based on day of the week
# Data Summary
- Total records: 1,385,934
- Avg nightly price: $137.95
- Median price: $109.00
- Highest price: $1650.00
- Lowest Price: $10.00
- Availability rate: 67.0%
# Key Findings
- Prices are lowest around January, averaging around $120 a night and continues to climb to a peak average of a little over $150 in July. Price then continues to decline again, with a small increase in December.
- Based on the distribution, most places are within the $10 to $250 range, however, there does seem to be a very good amount of outliers towards the higher side, likely luxury Airbnb's which cost upwards of $1650. Most of the outliers range from $300 to $750.
- Availability is generally consistent over each month with about a 67% overall availability. January has the least available while December has the most.
- Avg price is very consistent across each day of the week with an average low on mondays of $136 and a peak on saturdays of $142.
# Notes
- Unavailable nights had no listed price, so kept a copy dataframe when removing nulls.
- Jan 2017 was excluded as data in the set was not complete.
# Dataset
https://www.kaggle.com/datasets/airbnb/seattle?select=calendar.csv 
