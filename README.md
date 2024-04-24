# MobilePhonePricing
## About
This repo is a submission to Nanyang Technological University as part of a graded assignment for Course SC1015 - Introduction to Data Science and Artificial Intelligence.
>**Data Source:** Mobile Phone Specifications and Prices that have been scrapped from Gadgets360's site. The [Mobile Phone Specifications and Prices](https://www.kaggle.com/datasets/pratikgarai/mobile-phone-specifications-and-prices/data) dataset was extracted from Kaggle.

Our project focuses on studying the factors that contribute to mobile phone pricing that we can in turn tune as parameters in modelling techniques to predict mobile phone prices of phone models given a specification.

## Libraries/Dependencies
- tensorflow
- numpy 
- pandas
- seaborn
- sklearn
- matplotlib
- tabulate

## Contents
1. [Exploratory Data Analysis](/Extraction_And_EDA.ipynb)
2. [Linear Regression](/LinearRegression.ipynb)
3. [Neural Network](/Implementation_of_NN.ipynb)
4. [Random Forest](/RandomForestImplementation.ipynb)
5. [Dataset](/Dataset/)

### Exploratory Data Analysis
Data was extracted from csv sourcefile, cleaned and processed to produce univariate, bivariate analysis as well as some correlation calculations to try to identify parameters that can be used to tune Price Prediction Models.

### Linear Regression
- A study of bivariate models - how we can model the effect of Internal Memory (MB) & Storage (GB) on price
- A study of multivariate modelling - adding predictors, Internal Memory (MB) & Storage (GB) & Resolution_X*Y into 1 model
- Analysis of Goodness of Fit and Error for respective Models

### Neural Network

### Random Forest

### Dataset
Contains source file of dataset [ndtv_data_final.csv](/Dataset/ndtv_data_final.csv)


<!-- This content will not appear in the rendered Markdown -->
<!-- [Contribution guidelines for this project](docs/CONTRIBUTING.md) -->
