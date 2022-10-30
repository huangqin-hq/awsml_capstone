#### Source:
https://github.com/udacity/machine-learning/tree/master/projects/capstone

## Predicting Stock Price Movement Using Machine Learning
#### AWS Machine Learning Engineer Nano Degree Capstone Project

### Table of Contents
* [Repo Structure](#repo-structure)
* [Project Overview](#project-overview)
* [Dataset](#dataset)
* [Requirements](#requirements)

### Repo Structure
This repo contains below files:
- capstone_project.ipynb: project notebook with key results displayed
- capstone_project.html : project notebook in html format
- proposal.pdf          : project proposal
- report.pdf            : project's final report

### Project Overview
In this project, I used Random Forest, Gated Recurrent Unit(GRU) and Long Short Term Memory neural network(LSTM) along with time series stock data to build a classification model for predicting the direction of stock price movement in the next 1 day or 2 days, and benchmarked the prediction accuracy against the Naive Method.

### Dataset
The stock price data used in this project is retrieved from [Yahoo! Finance](https://finance.yahoo.com/).

### Requirements
The notebook requires the following packages to run:
* Python 3.8
* pandas
* pandas_ta
* numpy
* statsmodels
* yahoofinancials
* matplotlib
* seaborn
* sklearn
* keras
* warnings
