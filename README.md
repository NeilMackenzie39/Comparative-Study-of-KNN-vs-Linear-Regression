# Comparative-Study-of-KNN-vs-Linear-Regression
A comparison of the accuracy achieved when predicting FIFA 19 player values using KNN and Linear Regression 

## Getting Started
This repository contains a jupyter notebook of the code to execute this project as well as the data.csv file required to run the code

## Project Information
After completing [this](https://www.dataquest.io/course/linear-regression-for-machine-learning/) course on Linear Regression, I expanded on my original KNN [project](https://github.com/NeilMackenzie39/Predicting-FIFA-19-Player-Values-using-KNN) to include predictions using linear regression in this project. Statistics and data visualization are used to analyse the accuracy of these two models when using the top 10 indicative attributes to predict the value of forwards, midfielders, defenders and goalkeepers in the FIFA 19 game. 

As with the original project, the main purpose of this project was to explore the implementation of the models and practice data cleaning and the use of pandas, matplotlib and machine learning techniques. The result of this code has no direct impact since the value of all players is already known. The statistics of the predictions indicate that if the data sent to the models was assumed to be 'training data', the models have been implemented correctly and could be used to make predictions on test data after some tweaks/improvements.

Improvements can be made by selecting more neighbours in the KNN algorithm or analysing the ideal number of attributes to reduce the RMSE in the KNN model/improve the correlation coefficient in the Linear Regression model. These optimisations were not explored in this project since the goal was to assess the accuracy of each algorithm using 10 attributes and the default number of neighbours (5) in the KNN algorithm.
