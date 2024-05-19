# Exploring Plotly Python Open Source Graphing Library 

Welcome. This repo is created for the purpose of exploring and testing the capabiities of Plotly's Python Open Source Graphing Library for data analysis and online visualization. 

## Overview

Currently, the repository contains two Python scripts tailored for analyzing time series data, complete with sample dataset input files. Further explorations with artificial intelligence and machine learning charts, along with additional scripts, are planned for some time soon. Please feel free to utilize the scripts provided here and offer any feedback you may have.

### First Script: Basic Graphing

**Usage**: `python plotdata_any data_file chart_title`

Example: `python plotdata_any data.csv "Awesome Apple Sales Projections"`

This script takes any CSV input data file and plots the data along with a customizable chart title.

![image](https://github.com/ewpHumanTech/AI-playground/assets/170042205/1b468aab-4fec-40ed-a53b-6a033a1c309b)
![image](https://github.com/ewpHumanTech/AI-playground/assets/170042205/3ec186f0-8c69-46d5-9044-3bfe7d8c5f6b)
![image](https://github.com/ewpHumanTech/AI-playground/assets/170042205/005ea0f3-4363-40d6-8e39-37c2743182d7)

### Second Script: Trend Extrapolation

**Usage**: `python plotextrapolate_any data_file chart_title target_value key_column`

Example: `python plotextrapolate_any input_file.csv "When will Sales reach 3.4 million" 3400000 "Total Count of Sold Apples"`

This script predicts future values for each column in a dataset containing time series data. It accepts a target value as input and utilizes the specified key column from the dataset to forecast when the target will be reached. Finally, it generates a plot illustrating both the original and predicted data points.

![image](https://github.com/ewpHumanTech/AI-playground/assets/170042205/ac4d0f8f-811b-43c2-af43-8640ba52cdf3)

https://github.com/ewpHumanTech/AI-playground/assets/170042205/1fb076f0-50c4-4481-8a45-a623381db692



