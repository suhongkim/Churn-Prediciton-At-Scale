# Churn-Prediciton-At-Scale
The CUstomer Churn Analysis & Prediction of the Music Streaming Service At Scale (PySpark and Plotly)

## Table of Contents
* [Introduction](#Introduction)
* [Installation](#Installation)
* [Project Results](#Results)
* [Licensing, Authors, Acknowledgements](#License)


## Introduction<a name="Introduction"></a>
### Project Motivation 
In the music streaming industry like Sportify or YoutubeMusic, it is very important to monitor important business metrics and predict how their customers response. One of the most important metrics is "Churn" in business, which means the ratio of the users cancelling/downgrading the premium subscriptions. In this project, I build the prediction model to understand what kinds of factors affect the churn decision of users. 

### Project Description 
To process large amount of website-log data in website, which is not fit into my local computer, I need to understand how to work with the data at scale and build the prediction model with SparkMLlib. Thus, this project has three goals: 
[O] Analyze and Visualize the website logs   
[O] Build the ML model with SparkMLlib using mini-dataset(128MB) 
[X] Train the model on the large dataset(12GB) on AWS 


## Installation<a name="Installation"></a>
### Environment Setup
All libraries are available in Anaconda distribution of Python 3.*. The used libraries are:
```
os
datetime
numpy
pandas
matplotlib
seaborn
plotly
pyspark
chart-studio
```
## Results<a name="Results"></a>
- For the overview and general explanation of this project, please check my [Medium Post: How to Predict Customer Churn From Your Website Logs? ](https://suhongk.medium.com/how-to-predict-customer-churn-from-your-website-logs-bb02ea58385a)

- If you want to play with my code online, you want to visit my [Kaggle Post: 
A Tutorial of Customer Churn Analysis & Prediction](https://www.kaggle.com/suhong/a-tutorial-of-customer-churn-analysis-prediction) 

## Licensing, Authors, Acknowledgements<a name="License"></a>
Some parts of the codes in this project are provided by Udacity Data Scientist Program. If you think that it is useful, please connect with me via [linkedIn-Suhong](https://www.linkedin.com/in/suhongkim/)



