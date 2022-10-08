# Neural_Network_Model_for_Forest_fires_Dataset
Neural Network Assignment: Problem Statement: Predict the Burned Area of Forest Fire with Neural Networks.

The dataset we will be working with is associated with a scientific research paper on predicting the occurrence of forest fires in Portugal using modeling techniques.
The our focus will not only be about modelling but also on visualizing it.
There will also be exploratory analysis on the data to better understand it and to find any relationships that might be present in it.
Below are descriptions of variables in dataset and range of values for each taken from the research paper:
X: X-axis spatial coordinate within the Montesinho park map: 1 to 9
Y: Y-axis spatial coordinate within the Montesinho park map: 2 to 9
month: Month of the year: 'jan' to 'dec'
day: Day of the week: 'mon' to 'sun'
FFMC: Fine Fuel Moisture Code index from the FWI system: 18.7 to 96.20
DMC: Duff Moisture Code index from the FWI system: 1.1 to 291.3
DC: Drought Code index from the FWI system: 7.9 to 860.6
ISI: Initial Spread Index from the FWI system: 0.0 to 56.10
temp: Temperature in Celsius degrees: 2.2 to 33.30
RH: Relative humidity in percentage: 15.0 to 100
wind: Wind speed in km/h: 0.40 to 9.40
rain: Outside rain in mm/m2 : 0.0 to 6.4
area: The burned area of the forest (in ha): 0.00 to 1090.84
Introduction to Neural Networks:

Neural networks also known as artificial neural networks (ANNs) or simulated neural networks (SNNs), are a subset of machine learning (ML) and are heart of deep learning algorithms.

Their name and structure are inspired by the human brain, mimicking the way that biological neurons signal to one another.

Artificial neural networks (ANNs) are comprised of a node layers, containing an input layer, one or more hidden layers, and an output layer.

Each node, or artificial neuron, connects to another and has an associated weight and threshold.

If the output of any individual node is above the specified threshold value, that node is activated, sending data to the next layer of the network. Otherwise, no data is passed along to the next layer of the network.
