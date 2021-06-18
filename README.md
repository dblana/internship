# Time series Forecasting

This git gathers my work during a 2-month internship with the Centre for Health Data Science of the University of Aberdeen. 
The objective of this project was to propose a simple R code that would allow forecasting on time series data, for example related to COVID-19 numbers.
To illustrate the method that I implemented to achieve this objective, I work on the dataset provided by the COVID Tracker Project, ([covidtracking.com](https://covidtracking.com/data)).
This dataset presents COVID-19 related data, for each state of the US, such as number of deaths, hospitalizations, positive tests along time.
For different methods, I have thus been able to train models on data of every state, and propose a robust evaluation of each of them, computing errors on my predictions.
The details of my code is presented on the `report.Rmd` markdown, while the resulting graphed are stored in the outpus directory. This document presents all the methodology that I followed to implement forecasting models and evaluate them.

Beside it, I also created a markdown which aims to make people able to use my code and adapt it to their own datasets. In this document, the forecasting method used is the exponential smoothing, because this is the one that produced the best results during my experiments.
