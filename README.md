# Sentiment Analysis on sample Twitter data using Neural Networks

- This project performs Sentiment Analysis of sample Twitter Data set.

- Training data consists of a column called Sentiment which is a binary value.It is 1 if the corresponding tweet is positive and is Zero if its negative.

- To build a Neural Network model,top 5000 tweets are considered and they are tokenized.

- Above 5000 tweets are then divided into training (67%) and validation (33%) sets.

- Above data is fit into a RNN model built with 5 epochs.

- Then a LSTM model is built by replacing above RNN layer with LSTM layer.

- Finally,a comparision of the results from LSTM and RNN models is done.
