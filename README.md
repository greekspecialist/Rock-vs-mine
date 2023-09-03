# Rock-vs-Mine

## Overview
SONAR technology uses sound propogation and reflection to locate and map objects under the water. One of the possible uses of SONAR is to detect hazardous objects like mines underneath the water surface. 

This machine learning model tries to predict whether an object is a rock or a mine using SONAR data.

## Data Used
This dataset was used in Gorman, R. P., and Sejnowski, T. J. (1988). “Analysis of Hidden Units in a Layered Network Trained to Classify Sonar Targets” in Neural Networks, Vol. 1, pp. 75–89.

The dataset contains information of the signals recieved after they bounced back from the surfaces of a rock or a mine. There are 60 attributes and 1 categorical column.

## Libraries Used
- Pandas
- Numpy
- scikit-learn

## Model Accuracy

The model achieved an accuracy of around 84% on the training set and of around 76% on the test dataset.

<img src = "https://user-images.githubusercontent.com/24411030/169765793-be52ad91-1bba-428c-a02e-7f6fc188c9ba.png" width="400" height="400">
