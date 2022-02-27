# Fintech-API


The kernel file includes a demonstration of using pandas and matplotlib to plot data gathered from an alpaca API.

To access the code, click the link below or above!  

- [Financial Planner](https://github.com/muramemory/Fintech-API/blob/main/financial_planner.ipynb)


## Overview

### 1. Step one - Data Intialising & Crypto Portfolio

Intiated the alpaca trade API to pull the data from online. We used that API to specifically pull bitcoin data, as shown below in the image.

![image_add](Images/imports_and_api.png)
![image_add](Images/personal_crypto.png)
![image_add](Images/fetch_and_compute.png)


### 2. Step two - Find Stock Prices & Create Pie Plot 

Createad a pie plot with the price we discovered of stocks 'AGG' and 'SPY' and therfore the total amount owning in the portfolio.

![image_add](Images/stock_close_prices.png)
![image_add](Images/pie_plot.png)

Programmed an emergency fund message to let the user know if their portfolio has hit emergency levels.

![image_add](Images/emergency_fund.png)


### 3. Step three - Monte Carlo Simulation

Created a monte carlo simulation of the stock portfolio to see possible outcomes over 30 years for the portfolio.

![image_add](Images/configure_simulation.png)
![image_add](Images/line_distribution_plot.png)
![image_add](Images/retirement_analysis.png)


###  4 . Step four - Expected Portfolio return

![image_add](Images/expected_portfolio_return.png)
