# Jakarta Air Quality Index Prediction Model

This repository contains a machine learning model for predicting air quality in Jakarta, Indonesia. The model is designed to be integrated into a weather prediction website.

## Project Overview

This project focuses on predicting the Air Quality Index (AQI) in Jakarta based on historical data. The model analyzes patterns in air pollutant concentrations including PM10, PM2.5, SO2, CO, O3, and NO2 to forecast future air quality conditions.

## Dataset

The model is trained on the `ispu_dki_all.csv` dataset which contains historical air quality measurements from monitoring stations in Jakarta from 2010 onwards. The dataset includes:

- Date measurements
- Monitoring station locations
- Pollutant measurements (PM10, PM2.5, SO2, CO, O3, NO2)
- Maximum pollutant values
- Critical pollutant identifiers
- Air quality categories (BAIK, SEDANG, TIDAK SEHAT)

Link dataset: https://www.kaggle.com/datasets/senadu34/air-quality-index-in-jakarta-2010-2021?

## Model Development

The model development process is documented in `model.ipynb`, which includes:

1. Data exploration and preprocessing
2. Feature engineering
3. Model selection and training
4. Hyperparameter tuning
5. Model evaluation
6. Model deployment preparation

## Usage

To use the model for prediction:

1. Load the model and corresponding scalers
2. Preprocess new data using the same transformations applied during training
3. Make predictions using the loaded model

## Requirements

The model was developed using:

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Lisence
