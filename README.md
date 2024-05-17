Plotly Python Open Source Graphing Library Artificial Intelligence and Machine Learning Charts. 
This repo is used to test Plotly capabilities for data visualization. Feel free to use and provide feedback.

## Graphing Script Usage: 
python plotdata_any.py data_file chart_title 
 ( Example : python plotdata_any data.csv "Awesome Apple Sales Projections" ) 

This script takes any CSV input data file and plots the data along with a customizable Chart title.  

## Graph Display 


![image](https://github.com/ewpHumanTech/AI-playground/assets/170042205/1b468aab-4fec-40ed-a53b-6a033a1c309b)
![image](https://github.com/ewpHumanTech/AI-playground/assets/170042205/3ec186f0-8c69-46d5-9044-3bfe7d8c5f6b)
![image](https://github.com/ewpHumanTech/AI-playground/assets/170042205/005ea0f3-4363-40d6-8e39-37c2743182d7)

## Predictive Script Usage:
python plotextrapolate_any.py input_file chart_title target_value
( Example : python plotextrapolate_any input_file.csv "When we hit 3 mils in Sales" 3400000 )

This script takes an additional command-line argument target_value, which is the value you want to predict reaching. It calculates the rate of increase based on the second column of input data and uses this rate to predict future values until the target value is reached. It then plots the original data along with the predicted values.

![image](https://github.com/ewpHumanTech/AI-playground/assets/170042205/3e315f60-737d-4f6f-954b-0da26b6136e8)

