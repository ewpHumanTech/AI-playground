Plotly Python Open Source Graphing Library Artificial Intelligence and Machine Learning Charts. 
This repo is used to test Plotly capabilities for data visualization. Feel free to use and provide feedback.

This repository contains two scripts for analyzing time series data, along with sample dataset input files. 

## First Script: Basic Graphing 
USAGE: python plotdata_any data_file chart_title 
 ( Example : python plotdata_any data.csv "Awesome Apple Sales Projections" ) 

This script takes any CSV input data file and plots the data along with a customizable chart title.  

![image](https://github.com/ewpHumanTech/AI-playground/assets/170042205/1b468aab-4fec-40ed-a53b-6a033a1c309b)
![image](https://github.com/ewpHumanTech/AI-playground/assets/170042205/3ec186f0-8c69-46d5-9044-3bfe7d8c5f6b)
![image](https://github.com/ewpHumanTech/AI-playground/assets/170042205/005ea0f3-4363-40d6-8e39-37c2743182d7)

## Second Script: Trend Extrapolation 
USAGE: python plotextrapolate_any data_file chart_title target_value key_column
( Example : python plotextrapolate_any input_file.csv "When will Sales reach 3.4 million" 3400000 "Total Count of Sold Apples")

This script predicts future values for each column in a dataset containing time series data. It accepts a target value as input and utilizes the specified key column from the dataset to forecast when the target will be reached. Finally, it generates a plot illustrating both the original and predicted data points.

![image](https://github.com/ewpHumanTech/AI-playground/assets/170042205/3e315f60-737d-4f6f-954b-0da26b6136e8)

