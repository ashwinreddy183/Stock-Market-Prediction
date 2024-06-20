# Stock-Prediction
The provided project is focused on predicting the next opening price of the stock market using LSTM (Long Short-Term Memory) and analyzing the accuracy of the prediction model by tweaking various hyperparameters. The project follows a specific plan of attack, including steps such as data acquisition, data preprocessing, structuring the data, creating the model, training the model, prediction, and plotting the chart for analysis.

The project uses LSTM, a type of recurrent neural network (RNN), which is particularly suitable for analyzing and predicting temporal-dependent phenomena over a long period of time or multiple instances in the past. LSTM is an improvement over traditional RNNs as it can effectively "remember" long sequences of events in the past, making it well-suited for analyzing stock market data.

The plan of attack for the project includes data acquisition, where historical data from Yahoo Finance is downloaded in the form of CSV files. The next step is data preprocessing, which involves cleaning the data by handling discrepancies and removing null values. Data extraction is performed to select the relevant features, such as the opening price, which will be used as the deciding variable for predicting the outcome. Feature scaling is applied to normalize the data and bring all the values within the same range.

The data is then structured by creating input sequences for training the LSTM model. The length of the series is equivalent to the number of previous days considered for prediction. The data is split into training sets and output sets. Similar data structuring is performed for the prediction dataset.

The next steps involve creating the LSTM model, training the model on the training dataset, making predictions using the trained model, and finally plotting the chart to visualize the predicted opening prices. The accuracy of the models will be analyzed based on the line charts and the performance of the predictions.

The project also mentions tweaking the hyperparameters, such as batch size for LSTM, number of epochs, and previous days considered for prediction. By varying these hyperparameters, the aim is to improve the accuracy of the prediction models.

Finally, there is a mention of a graphical user interface (GUI) to view the charts, which can provide a user-friendly way to analyze the predicted stock market prices.
