# Covid Response Description
Linear regression model that would explore which stock is most deterministic in relation to the S&P 500

# Objective
To provide a statistical basis of a real world data set and an applied linear regression model in Scikit-Learn.
This will show a process of data analysis as well, when the dataset with all companies are analyzed it can be seen that Netflix has the lowest T-stat,  which in 
the basics of statistics can be thought as having the least statistical significance. It will then be removed to see if it improves or worsens the model. 

# Datasets:
1.  All the companies closing data (24 total)
2.  Netflix data is removed (23 total)

- Data was acquired from Yahoo Finance from January 1st 2019 to April 3rd 2020
- Has 3 companies from 8 different sectors
- To provide varying data not only companies that stock decreased were included but also ones that increased

# Variables Listed 

The response variable is the S&P 500

Below are the Predictor Variables:

1.  Airlines
    1.  Delta (DAL)
    2.  American (AAL)
    3.  Jet Blue (BLU)
2.  Cruise Ships
    1. Carnival (CCL)
    2. Norwegian (NCLH)
    3. Royal Carribean (RCL)
3.  Hotels
    1. Marriot (MAR)
    2. Hilton Worldwide (HLT)
    3. Park Hotels and Resorts (PK)
4.  Oil
    1. Exxon Mobil (XOM)
    2. Chevron (CVX)
    3. BP (BP)
5.  Entertainment
    1. Disney (DIS)
    2. Netflix (NFLX)
    3. Cinemark (CNK)
6.  Store Supplies
    1. Proctor and Gamble (PG)
    2. Johnson and johnson (JNJ)
    3. Nestle (NSRGY)
7.  Telecommunications
    1. Zoom (ZM)
    2. Microsoft (MSFT)
    3. LogMeIn (LOGM)
8)  Social Media 
    1. Facebook (FB)
    2. Twitter (TWTR)
    3. Snap (SNAP)
