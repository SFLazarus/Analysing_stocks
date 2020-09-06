# Data_Explorer
This project is part of Data Science Course

# Problem Statement
#### Traveling the world on a mission to discover new data
1. Set up a data science project structure in a new git repository in your GitHub account
2. Install Jupyter notebook prerequisites (Anaconda, Python, etc.)
3. Select an industry
4. Select two to three public data sets from that industry
5. Load the data sets into panda data frames following the 10 minutes to pandas guide
6. Formulate one or two ideas on how the data sets could be combined to establish additional value using exploratory data analysis
7. Transform the data sets into a single data set while following data preparation processes to clean and transform features (use pandas documentation for help)
8. Document your process and results
9. Commit your notebook, source code, visualizations and other supporting files to the git repository in GitHub

---
# What it does?
- Compares Bank of America Corp's stock and Wells Fargo & Co's stock in terms of day to day Closing price and Volume from 3/1/1973 to 4/1/2020.
- We combined data sets of both stocks.
- Analyzed resultant data. 

# Dataset used
- Stocks data is taken from https://www.kaggle.com/jacksoncrow/stock-market-dataset. 
##### Data Structure of BOA.csv and WFC.csv:
1. Date - specifies trading date
2. Open - opening price
3. High - maximum price during the day
4. Low - minimum price during the day
5. Close - close price adjusted for splits
6. Adj Close - adjusted close price adjusted for both dividends and splits.
7. Volume - the number of shares that changed hands during a given day

# Data Transformation
- Retrieved data from csv files
- Both stock data sets are loaded in to data frames.
- Changed column names and outer-merged them on Date attribute.

# Analysis
- After combining both data sets, we generate result_data.csv 
- we then visualise the change in closing price and volume of trades.
-![](https://github.com/SFLazarus/Data_Explorer/blob/master/Reports/Closing_Prices_Comparision.png)
- The all-time high Bank Of America stock closing price was 54.90 on November 20, 2006.
- The all-time high Wells Fargo stock closing price was 65.93 on January 26, 2018.
- We can clearly see price drop for both stocks during the 2007-2008 Global Financial Crisis and then they have recovered but again during 2020 stock market crash, both had a huge dip.
-![](https://github.com/SFLazarus/Data_Explorer/blob/master/Reports/Volume_Comparision.png)
- Stock volume is a measure of the number of stock shares that have been exchanged or traded within a specific period of time(usually daily). It's essentially how much buying and selling was going on within that period of time.
- When trading volume is higher, you'll have an easier time buying and selling large or small quantities of stock, because other traders are in the market, waiting to fulfill the other side of your trade.
- After the 2007-2008 Global Financial Crisis, consistently volume of Bank of America's stock was very high compared to that of Wells Fargo's but, we can see that Bank of America's stock closing price didn't improve as much as Wells Fargos stock did.

---

# Project Structure:
### Readme.md
- Project description
### Data
- Contains raw data and also processed data(final data)
### Notebooks
- Jupyter Notebook for Exploratory data analysis and Visualization.
### Reports
- Visualizations in png format images 
- Plot- Closing Prices Comparision
- Plot- Volume Comparision
### Requirements.txt
- Info about Tools, frameworks and libraries required to reproduce the work flow
