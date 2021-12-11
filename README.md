# Team 3: Options Strategies

## Project structure:

### Notebooks:
- This directory contains all of the jupyter notebooks we used in this project. There is one notebook each for the Covered Call, Married Puts, and Synthetic Long strategies, along with a 'historical returns' notebook used to calculate the returns gained from holding each of the stocks we have data on.

### Input data:
- The input data for the notebooks are in the 'data' directory. The 'data/price_data' directory contains the price of the stocks we selected for the last 5 years. The 'data/options_data' directory has the put and call data for each of the final stocks we decided to analyze in the project. There is one call file and one put file for each month ranging from November 2019 - October 2021.

### Output data:
- For the 'historical_returns' notebook, the results are in the 'data/historical_returns directory'. The results appear as csv files that contain data points for each month that are later used to create graphics.   
- When the notebooks for each of the strategies are run the output go into the data/outputs directory, which each strategy getting their own folder in there. Each strategy folder contains output csv files for the final four stocks we decided to use for the project (AMD, F, GM, and MSFT). Each row besides the header in each of those output csv files represents a data point used in our output graphics (which are in the 'graphs' directory of each strategy directory). For every stock, a line chart comparing the preformance of implementing the strategy vs holding a long position and a table are made.

