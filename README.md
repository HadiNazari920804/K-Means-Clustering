
# Customer segmentation by K-Means algorithm

![clustering](https://global-uploads.webflow.com/60af0e831a8c29b653fff5ff/611573bac7137d94a73a99e6_Market-Segmentation_Featured-1140x768%402x-80-min.jpeg)

*Improving customer clustering using the K-means algorithm by adding more features to the RFM model*

# About me
I'm Hadi Nazari. As a data enthusiast who is really passionate about diving into complex data and translating them into value-adding insights, I'd like to 
share my understandings with you.

## Project Intro/Objective
Delay always has a negative impact on customer satisfaction. It’s so important to take it into account when making decisions.
The purpose of this project is to answer to following questions:
* What are the most effective factors in flight delays?
* Is data Analytics able to predict delay?
* How does weather affect on flight delay? Is it possible to predict the delay caused by the weather and its factors?
* How can cluster airlines based on flight delay?
* What’s the effect of covid-19 pandemic on aviation industry in 2020?

## Key messages 
* Collected data from flight delays from 2003-2020 + Geographical location, latitude and longitude + Monthly Weather data
* Extracting important features and discovering the relation between them. 
* Dealing with missing values and imbalanced classes (downsampling method)
* Evaluation of different classification algorithms  and reassess the selected model to avoid overfitting
* Making prediction ready to use and interpret the features importance in model.
* Clustering airlines based on flight delays. What makes an airline great?

### Results / Recommended decisions
* A Model to predict delay class (short-medium-long) with new data
* A Model to predict weather delay (binary classification – delay or no delay) based on weather features   
* Clustering Airlines based on flight delays
* The cost of covid-19 pandemic on USA aviation industry in 2020  = 1,728,661 flight

### Partner
* ZeroG
* https://www.zerog.aero/

### Methods Used
* Machine Learning
* Classification
* Time Series
* Data Visualization
* Predictive Modeling
* Clustering
* Parallel Coordinates
* Feature Importance 
* Model Evaluation

### Packages and Libraries
* pandas
* numpy
* seaborn
* plotly
* folium
* sklearn
* xgboost
* tensorflow 
* shap
* scipy
* statsmodels
* meteostat


## About Dataset
- Data of flight delays in the United States from 2003-2020
- 73282 rows – 22 features

## Needs of this project

- data exploration/descriptive statistics
- data processing/cleaning
- statistical modeling
- data visualization
- writeup/reporting
- machine learning
- classification algorithms
- clustering methods
- Time series models

## Project Steps

1. Data cleaning - Dealing with missing values  
2. Extract new features to use in EDA and model
3. Classify delay to deploy classification algorithm
4. Deal with outliers
5. Discover the relationship between features
6. Analyze changes and fluctuations of feature during the years
7. Build a model to predict delay class (short-medium-long) with new data
8. Evaluate models and select the best one based on statistical metrics
9. Interpret the model and discover the importance of features in classification
10. Build a model to predict weather delay (binary classification – delay or no delay) based on weather features   
11. Cluster Airlines based on flight delays
12. Interpret the Airlines clustering 
13. Estimate the cost of covid-19 pandemic on USA aviation industry in 2020


## Jupyter Notebooks
* [01_Getting and cleaning data.ipynb](https://github.com/HadiNazari920804/Delayed_Flights/blob/main/01_Getting%20and%20cleaning%20data.ipynb)
* [02-EDA.ipynb](https://github.com/HadiNazari920804/Delayed_Flights/blob/main/02-EDA.ipynb)
* [03-Modeling_delay prediction.ipynb](https://github.com/HadiNazari920804/Delayed_Flights/blob/main/03-Modeling_delay%20prediction.ipynb)
* [04-Weather delay prediction.ipynb](https://github.com/HadiNazari920804/Delayed_Flights/blob/main/04-Weather%20delay%20prediction.ipynb)
* [05-Airline Clustering.ipynb](https://github.com/HadiNazari920804/Delayed_Flights/blob/main/05-Airline%20Clustering.ipynb)
* [06-Time series.ipynb](https://github.com/HadiNazari920804/Delayed_Flights/blob/main/06-Time%20series.ipynb)
* [delayed-reasons-over-years.ipynb](https://github.com/HadiNazari920804/Delayed_Flights/blob/main/delayed-reasons-over-years.ipynb)
