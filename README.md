<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# BTC Next Day's Price Prediction Project

Final project for the Building AI course

## Summary

This ai project aims to predict the next day's upwards or downwards price movement of a specific asset
based solely on the change in the previous day.

## Background

Price prediction is the quintessential financial problem. This modest project aims to find out whether a prediction
model can perform better than a coin toss.

## How is it used?

With the input of the previous day data, the model will suggest and upward or downward vector as a percentage change on the closing price asset compared to the previous day's closing price. The user could be any investment enthousiast interested with discovering
temporary patterns.
The model should be able to act as a function to automate suggestions.

## Data sources and AI methods

The data will be obtained from Kaggle the training set will be BTCUSD price between 2011-2023 with the following headers:

SNo	Name	Symbol	Date	High	Low	Open	Close	Volume	Marketcap
1	Bitcoin	BTC	2013-04-29 23:59:59	147.48800659179688	134.0	134.44400024414062	144.5399932861328	0.0	1603768864.5
2	Bitcoin	BTC	2013-04-30 23:59:59	146.92999267578125	134.0500030517578	144.0	139.0	0.0	1542813125.0
3	Bitcoin	BTC	2013-05-01 23:59:59	139.88999938964844	107.72000122070312	139.0	116.98999786376953	0.0	1298954593.75
...

## Challenges

Predicting the future on a highly volatile system by itself brings serious doubts on credibility. The model explores
the results on existing historical data. It is hardly an elaborate model but a tentative approach to machine learning.
It definitley shouldn't be a basis for investment, nor any other real life endavour except being a personal project.

## What next?

Through an API integration actual data could be added to the system through an estimation and retraining loop. The next step would be to look at prediction performane change through increase of the training data set.

I will need to try other models and libraries for faster and more accurate responses, the tabulate the results to explore its development.

## Acknowledgments

* University Helsinki, Building AI course and the ide gallery at:
* https://experiments.withgoogle.com/collection/ai
  
