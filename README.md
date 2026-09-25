# Human Activity Recognition Analysis

Statistical learning project analyzing relationships between movement intensity and variability across human activities using smartphone sensor data from the UCI Human Activity Recognition (HAR) dataset.

Developed as a team final project for **CS 405: Analysis and Presentation** at the University of Nevada, Las Vegas.

## Project Overview

The goal of this project was to investigate relationships between accelerometer- and gyroscope-based measurements across different human activities.

The analysis uses the UCI Human Activity Recognition Using Smartphones dataset, which contains sensor measurements collected from 30 participants performing six activities:

- Walking
- Walking Upstairs
- Walking Downstairs
- Sitting
- Standing
- Laying

The original dataset contains measurements derived from smartphone accelerometer and gyroscope signals.

## Analysis

The project explores relationships between movement intensity and variability across activities using statistical modeling and visualization.

The workflow includes:

- Data loading and preprocessing
- Exploratory data analysis
- Feature selection
- Construction of activity-related variables
- Multiple Linear Regression using Ordinary Least Squares (OLS)
- Train/test model evaluation
- Residual analysis
- Comparison of patterns across activity classes

## Dataset

The project uses the **UCI Human Activity Recognition Using Smartphones Dataset**.

The original study collected accelerometer and gyroscope measurements from 30 volunteers performing six activities while wearing a Samsung Galaxy S II smartphone on the waist.

Sensor signals were processed into fixed-width time windows and used to generate time- and frequency-domain features.

Additional documentation from the original dataset is included in this repository:

- `UCI_HAR_dataset_info.txt`
- `UCI_HAR_features_info.txt`

The full dataset is not included in this repository.

## Model

Multiple Linear Regression was used to analyze relationships within the selected activity features.

The model was fitted using **Ordinary Least Squares (OLS)** and evaluated on a train/test split.

Evaluation included:

- Mean Squared Error (MSE)
- R²
- Residual analysis
- Comparison of model behavior across activity types

The analysis also examines differences between static activities such as sitting, standing, and laying and dynamic activities such as walking and stair movement.

## Technologies

- Python
- NumPy
- Pandas
- Matplotlib
- scikit-learn
- statsmodels
- Jupyter Notebook
