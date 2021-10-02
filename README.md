# Surf's Up Challenge Analysis
## Project Overview

1. Explain the structures, interactions, and types of data of a provided set
2. Differentiate between SQLite and PostgreSQL databases
3. Use SQLAlchemy to connect to and query a SQLite database
4. Use statistics like minimum, maximum, and average to analyze data
5. Design a flask application using data
6. Run statistical data for requested months

## Resources
* Data source: challenge starter code, hawaii.sqlite
* Software: Python 3.7.6, Anaconda Navigator, Conda, Jupyter-Notebook, Pandas, Numpy, GitBash, VSCode 


## Overview of Analysis
W.Avy, an investor, is looking for information about weather trends in Hawaii before investing in a surf and ice cream shop. The following analysis takes a deepers look into the temperatures for June and December in order to get a snapshot of the weather during different times of the year. In order to analyze this data, SQLAlchemy was used to query data from an SQLite database and transformed into readable charts and graphs.

## Results 
*The average temperature in June is about 75 degrees. 

![June_stats](https://user-images.githubusercontent.com/88064181/135728043-97b04c04-ed7c-428e-9e61-1a47c702787b.png)

*The average temperature in December is about 71 degrees

![Dec_stats](https://user-images.githubusercontent.com/88064181/135728047-341e3606-fca0-44d7-9884-096df6d08b45.png)


*By graphing the two months, one can see that while June is an overall hotter month, the temperatures for both June and December typically stay between 70 and 80 degrees. December tends to trend on the slightly cooler side with some times seeing the low- to mid- 60 degrees while June tends to trend on the slightly warmer side seeing some times in the 80s. 

![june_temp_freq](https://user-images.githubusercontent.com/88064181/135728055-e8546e2d-d44d-482d-9619-1b6005978073.png)
![dec_temp_freq](https://user-images.githubusercontent.com/88064181/135728058-cb18131e-1438-4fb8-8828-a5ebf19d1978.png)


## Summary 

The data above indicates that the temperature in Hawaii does not fluctuate too much, and the seasons, while different, will all have temperatures that are pleasurable to surf in. W. Avy was also concerned about too many days being rained out for surfing. Additional queries were created to see if this would be an issue in June and December. As seen in the statistical charts below, both June and December see less than an inch of rain on average a day. December, when averaged out see .21 inches and June sees .13 inches. There are a few outliers that skew this data, where there is a rainer day vs the milder days, but overall there is little precipitation. Based on these queries, Hawaii seems like an ideal location to open a surf and ice cream shop. 

![dec_prcp](https://user-images.githubusercontent.com/88064181/135728068-4b2ecc75-f25f-4807-b770-38108ea1bc45.png)

![jun_prcp](https://user-images.githubusercontent.com/88064181/135728065-1ebf1fec-9db2-4ae9-bbf4-7522c8b496c0.png)
