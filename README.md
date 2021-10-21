# Time-Series-Analysis
Time Series Analysis Homework

Time Series Plotting for the USD/YEN Pair based on the Settle prices.

![image](https://github.com/Aelrid/Time-Series-Analysis/blob/main/Resources/Time%20Series%20Plot.PNG)
 

## Decomposition of the Hodrick Prescott Filter

![](https://github.com/Aelrid/Time-Series-Analysis/blob/main/Resources/HP%20filter.PNG)
 

## Forecasting Results using the ARMA Model
###Results Summary

![](https://github.com/Aelrid/Time-Series-Analysis/blob/main/Resources/ARMA%20Result.PNG)

###5 Day Return Forecast

![](https://github.com/Aelrid/Time-Series-Analysis/blob/main/Resources/ARMA%205%20Day%20Forecast.PNG)


## Forecasting Results using the ARIMA Model
###Results Summary

![](https://github.com/Aelrid/Time-Series-Analysis/blob/main/Resources/ARIMA%20Result.PNG)

###5 Day Return Forecast

![](https://github.com/Aelrid/Time-Series-Analysis/blob/main/Resources/ARIMA%205%20Day%20forecast.PNG)


##Volatility Forecasting Using GARCH

###Results Summary

![](https://github.com/Aelrid/Time-Series-Analysis/blob/main/Resources/GARCH%20Result.PNG)

###5 Day Forecast of Volatility

![](https://github.com/Aelrid/Time-Series-Analysis/blob/main/Resources/GARCH%20Forecast.PNG)

## Conclusion
The p values for both the ARMA and ARIMA models are more than p > 0.05. Also,the AIC for the ARMA model is better than that of ARIMA model.

I would buy Yen now but undertand the volaitility is  high based on the GARCH output.

Based on the p value I would not use ARMA and ARIMA model but given a lower p-value for GARCH I might use it as a part if my analysis for trading.

It important to note that along with statistics there might be other fundamentals/unsystematic risks that might affect the price of the FX pair.


# Regression-Analysis
## Linear Regression Output using Lagged Returns

![](https://github.com/Aelrid/Time-Series-Analysis/blob/main/Resources/Linear%20Regression%20Output.PNG)

### Conclusion
THE RSME for out of sample data(0.415) is lower than the in sample data(0.596). A training data set will usually have a lower RSME than a test data and hence it is hard to tell if the above prediction can be used for analysis.
