# Bootstrap-Method

# Overview

This assignment focuses on exploring machine learning techniques such as bootstrapping, neural networks, ensemble methods and also the time-series prediction using LSTM networks.

# Requirements

<ins>Part 1: Moon Dataset Analysis</ins>

The dataset contains 200 samples.

The first three columns are the feature values.

The fourth column is the labels (0 or 1).

 <ins>Tasks for part 1</ins>

Partition the dataset into first 150 samples as training dataset and the remaining 50 samples as the testing dataset.

Generate 50 training datasets, each containing 150 samples using the bootstrap method.

Design a feedforward neural network with one hidden layer consisting of 10 nodes.

Train the network for binary classification on each of the 50 training datasets.

Compute the error rate of each trained network using the test dataset.

Plot a histogram of the error rates.

<ins>Part 2: Time-series Forecasting</ins>

The dataset that have been utilized for this is DailyDelhiClimateTrain.csv.

This dataset includes climate information over four years.

The columns are: Date, Mean Temperature, Humidity, Wind Speed, Mean Pressure.

<ins>Tasks for part 2</ins>

Use the data form the first three years to construct three tarining sequences.

Use the fourth year for testing and prediction.

Network configuration: 128 nodes.

Train using the three training sequences.

Forecast the future values corresponding to the testing data.

# Requirements

Numpy

Pandas

Matplotlib

TensorFlow/Keras
