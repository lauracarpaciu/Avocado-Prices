#Avocado Prices

Historical data on avocado prices and sales volume in multiple US markets.
This data was downloaded from the Hass Avocado Board website in May of 2018 & compiled into a single CSV.
I have data where temporal ordering matters ,for that reason recurrent networks are a great fit and easily outperform models that first flatten the temporal data.
In this notebook, I will predict the average price of avocado using time-series modeling techniques
I wanted to calculate root mean squared error and  error distribution.
To use dropout with recurrent networks, you should use a time-constant dropout mask and recurrent dropout mask. These are built into Keras recurrent layers, so all I have to do is use the dropout and recurrent_dropout arguments of recurrent layers.Stacked RNNs provide more representational power than a single RNN layer.





