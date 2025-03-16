# Stock Market Data Analysis
## Project Description
This project developed a predictive analysis method that understands the current market behaviour and predicts the future trends. 
It trained the LSTM Model on historical stock data alongside technical indicators for predicting the future stock prices. 
LSTM’s superiority showcased a 30% enhancement in predictive accuracy compared to the traditional ARIMA Model.

## Data Model used
LSTM : LSTM (Long Short Term Memory) is a special kind of recurrent neural network where the output from the previous step is fed as the input to the current step.
It has a memory that stores the information from the last steps and is capable of learning long term 
dependencies in data. LSTM is a supervised learning where both the input and the output data used should be labeled.
It is well suited for time series data. 


## Project Outcomes
The actual and the predicted close price values have been compared with the help of a plot. 

The percentage error matrix obtained after the final prediction is checked using 3 error metrics 
Mean Absolute Error(MAE) which gives the value 4.26 , 
Mean Absolute Percentage Error (MAPE) having value 1.78 , and 
Median Absolute Percentage Error (MDAPE), value of which is 1.55 .

Finally, the next day’s closing price is predicted and compared with the actual value of the same day,
and thus checked how much greater or lesser than the predicted value is. 
