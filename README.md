# QRT Challenge 2020: Stock Return Prediction

https://challengedata.ens.fr/participants/challenges/23/

## Description
This repository contains the notebook where I generated my submission for the QRT Stock Return Prediction Challenge. My current score is 0.5189, which grants me the 12th position out of 207 contestants.  

## Challenge context
Quantitative investment strategies require the analysis of historical data to predict the trend of a stock in a near future. However, the extremely low level of signal / noise makes it a very challenging problem. Digging slight information among the enormous amount of available data in the market is a key goal for Qube RT. To do so, Machine Learning techniques can be used to make better trading decisions through deep analysis of thousands of different data sources. In a financial world in constant movement, it is extremely difficult to detect patterns that make a stock move up or down. This challenge is an illustration of the financial stock prediction.

## Challenge goals
The proposed challenge aims at predicting the return of a stock in the US market using historical data over a recent period of 20 days.

In this challenge, we consider the residual stock return, which corresponds to the return of a stock without the market impact. Historical data are composed of residual stock returns and relative volumes, sampled each day during the 20 last business days (approximately one month).

The metric considered is the accuracy of the predicted residual stock return sign.
