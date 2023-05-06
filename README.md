# Time-series-Analysis
This is a time series analysis for USD monthly exchange rates
Moving Average
![image](https://user-images.githubusercontent.com/74620085/236616505-3b92a426-45e5-4369-8096-b904ebbe0d6f.png)
![image](https://user-images.githubusercontent.com/74620085/236616582-f3845160-99f9-4789-9693-548431f451fb.png)
•	The plot represents a 3-month moving average of the US Dollar exchange rate.
•	Original data is represented by the black line, 
•	 the red line represents the 3-month moving average. 
Simple exponential smoothing
![image](https://user-images.githubusercontent.com/74620085/236616758-f5bf1676-22ad-4524-a099-52999d818b69.png)
![image](https://user-images.githubusercontent.com/74620085/236616798-a7f7b730-104c-44b9-8609-69489f9ed790.png)
Graph gives prediction interval as indicated by the shaded area.
 Based on the model fit ,this is the range in which future observations are expected to fall with a 0.95 probability.
Double exponential smoothing
![image](https://user-images.githubusercontent.com/74620085/236617040-1227787f-a79b-4cd4-9c90-0ab1da1bdd5f.png)
![image](https://user-images.githubusercontent.com/74620085/236617080-59bba362-03d0-454a-8c07-ded690e42850.png)
The time series data's actual values are displayed in black in the resulting plot below, while the predicted values are displayed in blue. The 95% confidence intervals around the predicted values are represented by the shaded regions. The predicted values' time period is shown on the x-axis, while the exchange rate values are shown on the y-axis. The graphic shows how well the time series data fit the double exponential smoothing model and how close the anticipated values get to the actual values.
Triple Exponential
![image](https://user-images.githubusercontent.com/74620085/236617332-e5a200bb-ac10-475a-a159-0cb39fd8fb3e.png)
![image](https://user-images.githubusercontent.com/74620085/236617355-ee657f3d-9573-4f14-bddb-39e898878489.png)
The Triple Exponential Smoothing model below has  captured the overall trend and seasonality in the data. Additionally, as we look further into the future, the confidence intervals gradually widen, reflecting growing forecast uncertainty.

Overall, the figure implies that using the Triple Exponential Smoothing model to predict dollar exchange rates for the upcoming 12 months is a sound decision.
Time Series Plot
![image](https://user-images.githubusercontent.com/74620085/236617447-c186313a-62bd-43f7-b9c1-2e70ff3ef28f.png)
Box and Jenkins methodology of fitting ARIMA modes
![image](https://user-images.githubusercontent.com/74620085/236617527-4bf4d6b0-42a6-4682-a324-d33f4e59eb3b.png)
![image](https://user-images.githubusercontent.com/74620085/236617540-00cb1c47-9075-4dae-8ec6-f7d1c8ca4c3a.png)
A systematic method for fitting time series models, specifically the Auto-regressive Integrated Moving Average (ARIMA) models, is the Box-Jenkins methodology. A well-liked model for predicting time series data with temporal dependence is the ARIMA model.
Phase 1 Identification of the model
A class of straightforward ARIMA models is chosen using data plots, autocorrelations, partial-correlations, and other information. This entails determining the proper values for p, d, and q. 
![image](https://user-images.githubusercontent.com/74620085/236618069-21807247-1df4-4588-89dc-02d4b54e669a.png)
![image](https://user-images.githubusercontent.com/74620085/236618089-5444b78e-4363-4b30-861e-0bab81664be1.png)
Auto-correlation figures shows a relationship between the time series and the value at lag 1 for the time series. A considerable association may be seen at lag 1
![image](https://user-images.githubusercontent.com/74620085/236618186-dfb0cdc6-9884-43e8-92b2-33a366c613aa.png)
![image](https://user-images.githubusercontent.com/74620085/236618210-4aaad4ed-35cf-4962-b9ef-a2afb68d232a.png)
