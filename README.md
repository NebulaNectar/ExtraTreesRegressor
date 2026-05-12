# ExtraTreesRegressor — Energy Load Prediction

## About the Project
This project predicts energy load using machine learning.
The dataset contains hourly energy load and temperature 
readings from 2012 to 2014.

## Dataset
- File: energy.csv
- Rows: 26304
- Columns: timestamp, load, temp

## Features Used
- time_num (converted from timestamp)
- temp (temperature)

## Model Used
- Extra Trees Regressor (from sklearn.ensemble)

## Results
- R2 Score : 0.9824
- RMSE     : 75.70
- MAE      : 53.36

## Why Extra Trees Regressor?
Linear Regression gave very low R2 (0.002) because 
energy load is non-linear data. It goes up and down 
every few hours depending on time of day and season.
Extra Trees Regressor handles non-linear patterns 
very well — giving R2 of 0.98!

## Libraries Used
- pandas
- numpy
- scikit-learn
- matplotlib

## How to Run
1. Open ExtraTree_Regressor.ipynb in Google Colab
2. Upload energy.csv to your Google Drive
3. Change the path variable to your file location
4. Run all cells
