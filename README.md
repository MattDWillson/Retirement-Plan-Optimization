# Retirement Plan Forecaster
-	Tools / languages: JupyterLab, Python, Pandas, Alpaca API, Monte Carlo simulations

## Overview:
-	Financial planning algorithm that allows users to assess monthly personal finances, visualize savings composed of stocks, bonds, and crypto currencies; allows users to run Monte Carlo simulations to forecast retirement plan performance at 5, 10, and 30 years.
-	Fetched real time data for Bitcoin, Ethereum, SPY ETF, and AGG bonds through an API and created variables to identify the amount of each cryptocurrency or financial security in U.S. dollars the user has at the moment 
-	Fetched historical data for cryptocurrencies and financial securities via the Alpaca API to run Monte Carlo simulations and forecast portfolio performance; identified 95% confidence intervals for portfolio performance based on different investment amounts and time periods of 5, 10, and 30 years. 

## 5 Year Simulation 
<img width="520" alt="Screen Shot 2021-08-04 at 12 57 08 PM" src="https://user-images.githubusercontent.com/83780964/128222968-60ed5f76-b703-424a-b3b4-9d3e8f37a656.png">
<img width="387" alt="Screen Shot 2021-08-04 at 12 57 21 PM" src="https://user-images.githubusercontent.com/83780964/128222972-ab38b985-ff38-46fb-bd2c-fc033c69f7c8.png">

## 5 Year Forecast:
- There is a 95% chance that an initial investment of $30000 in the portfolio over the next 5 years will end within in the range of $25257.03 and $82917.14

## 10 Year Simulation 
<img width="524" alt="Screen Shot 2021-08-04 at 12 58 16 PM" src="https://user-images.githubusercontent.com/83780964/128223090-0bbf7930-d7de-4d3b-8576-76a82e516edd.png">
<img width="386" alt="Screen Shot 2021-08-04 at 12 58 32 PM" src="https://user-images.githubusercontent.com/83780964/128223096-63cd5e9b-fdca-40df-98b3-36b519503d9c.png">

## 10 Year Forecast:
- There is a 95% chance that an initial investment of $60000 in the portfolio over the next 10 years will end within in the range of $73989.76 and $332472.54

## 30 Year Simulation 

<img width="514" alt="Screen Shot 2021-08-04 at 12 56 18 PM" src="https://user-images.githubusercontent.com/83780964/128223151-629513ad-2d98-48d2-8f29-309cc5e457f7.png">
<img width="404" alt="Screen Shot 2021-08-04 at 12 56 47 PM" src="https://user-images.githubusercontent.com/83780964/128223162-3eb9b6b3-583e-4706-b51b-1c0139c9b635.png">

## 30 Year Forecast:
- There is a 95% chance that an initial investment of $20000 in the portfolio over the next 30 years will end within in the range of $78907.12 and $1242512.88
- There is a 95% chance that an initial investment of $30000 in the portfolio over the next 30 years will end within in the range of $118360.68 and $1863769.32
