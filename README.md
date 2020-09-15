# stock
To excercise and sharpen my skills for data processing and tensorflow, I built a small project with junipter notebooks (https://github.com/lingzix/stock). The purpose is to collect comprehensive economic data/index/events, and train a LSTM or other deep learning models to predict future stock trend.
First of all, I collected more than 200 kinds of macro economic historic data and events from the investing.com, using the investpy python library. These data covers a broad range of economic facts such as S&P 500, all major currencies, gold/crude oil price, unemployment rate, etc.  Since part of the data are missing in certain dates, I also used the API of data provider IEX Cloud to complement my data sources.
 Due to the diversity of economic index/events, I also needed to perform data cleansing and formating, so that they could be structured into a regular matrix. 
I also need to group the data into batches depending on the timesteps defined in for the LSTM model.
I used the scikit-learn to perform data normalization. Besides the LSTM model, I've also tried feeding the data into fully connected nerual networks. All these model were built using Tensorflow packages.
As for the target labels, I've tried both logistic 
When I set the target and other deep learning models to analyze these data and make predictions on stock trend.
