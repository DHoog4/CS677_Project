# Rainforest Deforestation in Brazil: Analysis and Forecasting

## Introduction
Rainforests are one of the most essential systems in our planet’s ability to sustain life. Brazil is covered by more rainforests than any other county. This project examined the amount of rainforest lost and the number of rainforest fires in Brazil from 1999-2019. Various machine learning methods were used to graph past data and forecasts of future data. Methods included linear regression, k-nearest neighbors (k-NN), moving average forecasting, and seasonal autoregressive integrated moving-average (SARIMA). 

## Technologies

* Python 3.10.12
* Scikit-learn 1.0.2
* Statsmodels 0.13.2

## Data

* [Brazilian Amazon Rainforest Degradation 1999-2019 dataset](https://www.kaggle.com/datasets/mbogernetto/brazilian-amazon-rainforest-degradation) - specifically, 'def_area_2004_2019' & 'inpe_brazilian_amazon_fires_1999_2019' (the latter was my primary dataset)   

## Room for Improvement

* Use automatic tuning for SARIMA model and compare results
* Explore other rainforest deforestation datasets
* Research and apply more time-series forecasting techniques (time-series forecasting was not covered in this course)
