# Sequences, Time Series and Prediction  
## Exercise 1-Create and Predict Synthetic Data  
A time series was created and features trend, seasonality and noise.  A naive prediction of the time series was made simply by predicting the next point to be equal to the last point.  Mean squared error and mean average error were used to measure prediction performance.  By performing various operations on the data, a prediction that was better than the naive prediction was made.
- [Introduction to Time Series](https://github/lmoroney/dlaicourse/blob/master/TensorFlow%20In%20Practice/Course%204%20-%20S%2BP/S%2BP_Week_1_Lesson_2.ipynb)  
- [Forecasting](https://github/lmoroney/dlaicourse/blob/master/TensorFlow%20In%20Practice/Course%204%20-%20S%2BP/S%2BP%20Week%201%20-%20Lesson%203%20-%20Notebook.ipynb)  
## Exercise 2-Predict with a DNN  
This time predictions of the time series were made.  With a moving window size of 20 time steps as input to a deep neural network, predictions were made for the next single time step in the series.  
- [Preparing Features and Labels](https://github/lmoroney/dlaicourse/blob/master/TensorFlow%20In%20Practice/Course%204%20-%20S%2BP/S%2BP%20Week%202%20Lesson%201.ipynb#scrollTo=Wa0PNwxMGapy)  
- [Single Layer Neural Network](https://github/lmoroney/dlaicourse/blob/master/TensorFlow%20In%20Practice/Course%204%20-%20S%2BP/S%2BP%20Week%202%20Lesson%202.ipynb)  
- [Deep Neural Network](https://github/lmoroney/dlaicourse/blob/master/TensorFlow%20In%20Practice/Course%204%20-%20S%2BP/S%2BP%20Week%202%20Lesson%203.ipynb)  
## Exercise 3-Predict with an RNN  
Predictions of the synthetic time series were done using an RNN.  A LearningRateScheduler was used as a callback to increase the size of the learning rate as the number of epochs increased.  Comparing the history of the learning rate and the loss, a fixed learning rate was chosen for a SGD optimizer.  
- [RNN Network](https://github/lmoroney/dlaicourse/blob/master/TensorFlow%20In%20Practice/Course%204%20-%20S%2BP/S%2BP%20Week%203%20Lesson%202%20-%20RNN.ipynb)  
- [LSTM Network](https://github/lmoroney/dlaicourse/blob/master/TensorFlow%20In%20Practice/Course%204%20-%20S%2BP/S%2BP%20Week%203%20Lesson%204%20-%20LSTM.ipynb)  
## Exercise 4-Sunspots  
- [Conv1D and 2-layer LSTM Network](https://colab.research.google.com/github/lmoroney/dlaicourse/blob/master/TensorFlow%20In%20Practice/Course%204%20-%20S%2BP/S%2BP%20Week%204%20Lesson%201.ipynb)  


