# Tesla Stock 

Program that allows to predict the price of wide range of equities, mutual funds, and ETFs by using  pandas_datareader to extract data from various Internet sources. 
This program predicts the stock price of Tesla for the upcoming day by using artificial neural network - LSTM(Long Short Term Memory). 

The time interval taken: 2015/01/01 - 2020/01/01


## Steps
First, by training and testing the data we predict the stock price of the last 60 days, and compare the resutls with the actual data.  

<img width="835" alt="Ph1" src="https://user-images.githubusercontent.com/42979064/93157331-d5275300-f72b-11ea-8dc4-90ea59363623.png">


On the graph we can see that the prediction for 60 days was decent.  
Now, we can predict for the next day.  
The price is: 

<img width="116" alt="Ph4" src="https://user-images.githubusercontent.com/42979064/93257921-685d9880-f7bf-11ea-9998-7031b479b9fa.png">

The actual price: 

<img width="208" alt="Ph3" src="https://user-images.githubusercontent.com/42979064/93258076-97740a00-f7bf-11ea-9530-839539255eea.png">

### Do not use this program to track the stock market
