# Project Overview
This sales analysis describes activities in a sales company including the profit, loss, sale trends, highest product sales and lowest product sales.
## Project title
Sales Analysis of products in Tesco
### Aims and objectives
- Highest significant sale trends
- Spot patterns affecting sales projections
- Provide strategic suggestions for future sales
- Improve sales outcome over time

### Data Source
The data used was collected from texco stores across london
### Tools used
Microsoft Excel Power Bi and Python
### Data cleaning/preparation
- An empty column was dropped
- NULL values was removed
- From the age column, the mean values were used to reduce the null values
- Non numerical values were removed from the sales column to allow aggregation of the sales colunm

### Exploratory Data Analysis
- The highest selling tesco store was identified
- The highest selling product was also identified
- The day with the highest/lowest sale was determined
- The age group with the highest/lowest purchase
- The gender with the lowest/highest purchase
- Poor/best performing sales Tesco store
### Data Analysis
This is an example code used in this project:
```
sales.drop('link', axix=1, inplace=True)
```

### Results
- Results showed that Tesco store in South London recorded the highest sales while the lowest sales was recorded in North London
- The day with the lowest sales is Monday while Sunday was the day with the highest sales.

