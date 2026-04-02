<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Project Title

Final project for the Building AI course

## Summary

This ai project aims to predict the next day's upwards or downwards price movement of a specific asset
based solely on the change in the previous day.

## Background

Which problems does your idea solve? How common or frequent is this problem? What is your personal motivation? Why is this topic important or interesting?

Price prediction is the quintessential financial problem. This modest project aims to find out whether a prediction
model can perform better than a coin toss.

## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

With the input of the previous day data, the model will suggest and upward or downward vector as a percentage change on the closing price asset compared to the previous day's closing price. The user could be any investment enthousiast interested with discovering
temporary patterns.
The model should be able to act as a function to automate suggestions.

## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

The data will be obtained from Kaggle the training set will be BTCUSD price between 2011-2023 with the following headers:
SNo	Name	Symbol	Date	High	Low	Open	Close	Volume	Marketcap
1	Bitcoin	BTC	2013-04-29 23:59:59	147.48800659179688	134.0	134.44400024414062	144.5399932861328	0.0	1603768864.5
2	Bitcoin	BTC	2013-04-30 23:59:59	146.92999267578125	134.0500030517578	144.0	139.0	0.0	1542813125.0
3	Bitcoin	BTC	2013-05-01 23:59:59	139.88999938964844	107.72000122070312	139.0	116.98999786376953	0.0	1298954593.75
...

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

Predicting the future on a highly volatile system by itself brings serious doubts on credibility. The model explores
the results on existing historical data. It is hardly an elaborate model but a tentative approach to machine learning.
It definitley shouldn't be a basis for investment, nor any other real life endavour except being a personal project.

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 

Through an API integration actual data could be added to the system through an estimation and retraining loop. The next step would be to look at prediction performane change through increase of the training data set.

## Acknowledgments

* University Helsinki, Building AI course and the ide gallery at:
* https://experiments.withgoogle.com/collection/ai
  
