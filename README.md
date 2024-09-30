# Machine-Learning-for-Indoor-Localization-Using-WiFi-Signals
# Indoor Localization Using Machine Learning

This repository contains the implementation of several machine learning algorithms for fingerprint-based indoor localization using WiFi signals. The project focuses on predicting indoor positions based on WiFi RSSI values and provides a comparative analysis of different algorithms using the UJIIndoorLoc dataset.

## Overview
This project implements several machine learning algorithms to predict indoor locations based on WiFi signal strength data (RSSI). The goal is to achieve high accuracy in localizing a device inside buildings where GPS is unavailable or unreliable.

## Dataset
We used the **UJIIndoorLoc** dataset, which consists of WiFi signal fingerprints from 520 Wireless Access Points (WAPs) recorded across three buildings and multiple floors. The dataset contains:
- 19,937 training records
- 1,111 validation records

Each record includes WiFi signal strengths, coordinates (latitude, longitude), building and floor IDs, and timestamps.

## Implemented Algorithms
The following machine learning algorithms have been implemented for indoor localization:
- **Support Vector Machine (SVM)**
- **Decision Tree**
- **K-Nearest Neighbors (KNN)**
- **Random Forest**
- **Linear Regression**
- **Ridge Regression**
- **Sequential Classification Neural Network (SCNN)**

These algorithms were tested and evaluated based on their performance in classifying building and floor, as well as predicting the longitude and latitude of the device inside the buildings.

## Results
The performance of the algorithms was compared based on classification accuracy and regression error metrics. Key results include:
- **KNN**: Achieved a classification accuracy of 96.67% for building and floor prediction.
- **Random Forest**: Delivered reliable predictions with strong regression accuracy.
- **SVM**: Showed an accuracy of 95.00% in classification tasks with reliable regression performance.
- **Ridge Regression**: Provided better regression performance due to regularization, reducing overfitting.
- Comparative results for each algorithm are documented in the project report.

