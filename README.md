# Data Analysis and Hypothesis Testing with Pandas

The notebooks are the assignments I did for the [Data Science course by University of Michigan on Coursera] (https://www.coursera.org/learn/python-data-analysis). 

*Assignment 3* is focused on data cleaning and manipulation for analysis. 

- Data Cleaning
  - Three csv/Excel files on the energy, GDP and energy technology journal contributions of different countries are read in, formatted and then merged into a single DataFrame on the top 15 countries by Scimagojr Rank from 2006 to 2015.  
  
- Data Manipulation
  - Population and the number of citable documents per person fo each country are estimated. The features are aggregated by the continent.

*Assignment 4* is to test the hypothesis that the housing prices in US college towns are less impacted by economic recessions than in other cities. 

- Data Gathering: 
  - Housing Pricing Data for the US from Zillow
  - University Town lists in the US from Wikipedia
  - GDP from Bureau of Economic Analysis, US Department of Commerce
- Data Cleaning: 
  - Created a DataFrame of towns and the states they are in from the University Town list
  - Found the recession start, bottom and end time from 2000 to 2009
  - Aggregated the housing data by the quarter
- Statistic Analysis: 
  - It is found by t-test that the housing prices in college towns are less likely to be impacted by the economic recessions. 
