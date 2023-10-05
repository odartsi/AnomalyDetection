# Anomaly Detection in Time Series and MNIST Digits

## Description

This repository encompasses two distinct anomaly detection projects, each targeting different datasets and methodologies.

### Time Series Price Anomaly Detection with Clustering

The [`TimeSeriesPriceAnomalyDetection`](https://github.com/odartsi/AnomalyDetection/blob/master/TimeSeriesPriceAnomalyDetection.ipynb) focuses on detecting anomalies in time series house price data using clustering techniques. 

### Unsupervised Anomaly Detection for MNIST Digits

The [`Autoencoder`](https://github.com/odartsi/AnomalyDetection/blob/master/Autoencoder.ipynb) centers around unsupervised anomaly detection applied to the MNIST dataset. Here, the primary objective is to identify anomalies among hand-written digit images. During the training process, specific digit classes are deliberately held out as anomalous, and the model assigns a "score of normality" to each digit, with higher scores indicating greater normality.

<img width="998" alt="Screenshot 2023-10-04 at 15 15 25" src="https://github.com/odartsi/AnomalyDetection/assets/58295268/1e6e2617-8f98-4ea4-87fd-182411a8fcfb">
