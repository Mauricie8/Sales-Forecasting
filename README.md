# Sales-Project
![](images/introduction.jpg)

---
<img src="images/matplotlib-logo.png" alt="Matplotlib Logo" width="110"/> <img src="images/numpy-logo.png" alt="Numpy Logo" width="110"/> <img src="images/sklearn-logo.png" alt="Sklearn Logo" width="110"/> <img src="images/pandas-logo.jpg" alt="Pandas Logo" width="110"/> <img src="images/seaborn-logo.png" alt="Seaborn Logo" width="110"/>  <img src="images/prophet-logo.jpg" alt="Facebook Prophet Logo" width="110"/>

## Introduction
This project focuses on using data science to address a key challenge in business sales. It involves building a Python model using Facebook Prophet, a powerful tool for time series forecasting, to provide accurate predictions that can help optimize business strategies.

## Problem Statement
This project addresses the problem by developing a machine learning model that forecasts the future sales of different stores of a brand. The main idea is to predict how good or bad is the near future and be prepared for it.

## Background
- Libraries and datasets
- Visualize dataset
- Data cleaning and transformation
- Exploratory Data Analysis (EDA)
- Merge Datasets Analysis
- Prediction Model (Facebook Prophet)
- Final Predictions with Holidays

## Models Used
- Facebook Prophet

## Data Sourcing
The dataset used in this project is a cleaned version of information extracted from the internet. 

## Data Cleaning and Exploration
The data was previously cleaned with a first ETL process, the changed made here were:
1) To discard closed stores.
2) To drop column "Open"
3) To convert to zero all missing data in columns Promo2SinceWeek, Promo2SinceYear, PromoInterval, CompetitionOpenSinceYear, CompetitionOpenSinceMonth.
4) To fill missing data in CompetitionDistance with the mean.

## Exploratory Data Analysis (EDA)
In this part, the principal objective was to visualize data with histograms for a better understanding of the variation and distribution in each feature.
  ![](images/credit-limit-kdeplot.jpg)
- To graph and understand other correlations in values.
  ![](images/correlations.png)


