Flight Mode Prediction from Fan Speed Data
This project applies a Support Vector Machine (SVM) model to predict aircraft flight modes using fan speed sensor data.

Objective:
Classify different flight phases—such as idle, climb, cruise, and descent—based solely on time-series fan speed measurements.

Model:
Support Vector Machine (SVM) was chosen for its ability to handle high-dimensional data and perform well with limited features.

The model was trained and evaluated using preprocessed fan speed data.
Feature engineering included time-based aggregation and normalization techniques.

This work was conducted as part of the Data Scientist – Capstone Project (Aug 2021 – Dec 2021) with GE Aviation, Auburn, AL, where the team:

  Developed a KNN-MACEst-KMeans framework to assess prediction confidence
  
  Compared model performance across KNN, SVM, and LSTM
  
  Validated robustness through sensitivity analysis on labeled test data
