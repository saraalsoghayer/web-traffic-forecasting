# Web Traffic Forecasting

## Problem Statment:

Forecasting the future web traffic (webpage visits) of multiple time-series for Wikipedia webpages and analyzing the pattern of traffic to understand the web traffic more. Forecasting webpages help the host to know if the server needs more cloud storage to handle a large number of visitors.

## Executive Summary:

Wikipedia web traffic forecasting was challenging due to missing data and time-series length. However, when i inspected the data, i found that English webpages get more visits compared to other languages, and the type of day (weekend,weekday) does not make a big difference. When it came to modeling, i used ARMA to fit train/test the data but the MSE was high due to the size of the train/test data.

## Datasets Description:

train_1 data is from Kaggle. The training dataset consists of approximately 145k time series. Each of these time series represent a number of daily views of a different Wikipedia article, starting from July, 1st, 2015 up until December 31st, 2016. The leaderboard during the training stage is based on traffic from January, 1st, 2017 up until March 1st, 2017.

## Conclusions:

After analyzing the data i discovered a number of things: webpages drive more traffic if they are in English, there is not a dramatic difference in web traffic between weekdays and weekends, and traffic can be predictable if i had more data to work with, as the model is not reliable due to the size of trainig/testing data
