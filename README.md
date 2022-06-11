# Surfs_Up

## Analysis

### Overview of the analysis: 
Using Python, Pandas functions and methods, and SQLAlchemy, we’ll filter the date column of the Measurements table in the `hawaii.sqlite` database to retrieve all the temperatures for the month of June. We'll then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics. Once our dataframe is created we are able to get our summary statistics by using the `df.describe()` code and method. 

### Results:

The data provided gave us insight that for the months of June and December, our location had a total temperatures of:

#### June
![June_Temps](https://github.com/vvinci21/surfs_up/blob/a529729721363cef7e81df617d5628db866cd1b8/Resources/June_Temps.png)

#### December
![December_Temps](https://github.com/vvinci21/surfs_up/blob/a529729721363cef7e81df617d5628db866cd1b8/Resources/December_Temps.png)

* June on average is almost 4 degrees warmer than December.
* However, the max temperature recorded in June was 85 which is only 2 degrees warmer than Decembers max of 83.
* The minimum in June is 64 while in December it is 59 which is significantly different.
* All of the quartiles are only differing by 3 or 4 degrees.

### Summary:

Based on our data analysis, we can conclude that even though the max and minimum temperatures differ, the temperatures are relatively similar in June and December. The quartiles are all relatively close within a few degrees of each other. Additionally we can query for precipitation amounts and the corresponding locations to determine optimal shop locations. These additional queries with the data we already have will help us determine the surf and ice cream shop is sustainable year-round as well as where to locate it. 
