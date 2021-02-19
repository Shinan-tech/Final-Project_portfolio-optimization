# Portfolio Optimization

## My objectives:
### To perform portfolio (crypto assets) optimization by using monte carlo simulation 

## Used link (sources):
[My repository](https://github.com/Shinan-tech/Portfolio_Optimization)

[Coingecko API] (https://www.coingecko.com/api/documentations/v3#)
(https://www.coingecko.com/api/documentations/v3#/coins/get_coins__id__market_chart)

## Work done:
Step 1: Collecting the data necessary for analysis. Closing price for top10 coins according to marketcap. Use API CoinGecko to grab daily closing price in USD for 365 days during from 01.01.2019 - 31.12.2019. 

Step 2: Preparing the data to calculate a few different metrics: expected returns, expected volatility, and the sharpe ratio.

Step 3: Building a simulation that will randomly generate results that we can use to help to determine the optimal results for a wide range of portfolios.

Step 4: Taking this simulation, plot them using matplotlib

Step 5: Using K-Means to classify the listed coins around 1800 coins (with available data from 01.08.19 - 31.12.19)

## Conclution:
#### In the traditional market, the sharpe ratio is normally above 1, however in crypto market is all below 1. It is probably due to the very high volatility. For the optimised allocation, please refer to the ppt. Regards the unsupervised learning (classification), the coins could be really good classified by annualised return (very negtive annualised return / negtive to zero / positive annualised return), unfortunatly I had a look at the group with high positive annualised return, due to the limited the knowledge I do not recognise most of the porjects. 

