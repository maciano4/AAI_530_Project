# Model 1 – Time-Series Linear Regression

This folder contains the implementation of the Multiple Linear Regression model used to predict future gas concentrations.

## Objective

Predict CO and CO₂ concentrations one hour ahead using historical sensor data.

## Methodology

- Lag features (previous 3 hours)
- Rolling statistics (mean and standard deviation)
- Environmental variables (temperature, humidity)
- Motion-derived occupancy indicators
- Chronological 80/20 train-test split (no shuffling)

## Files

- (LinearRegression_ML_Model_1.ipynb) – Model implementation
- (model1_performance.csv) – Evaluation metrics
- 3 Figures – Visualization outputs (Actual vs Predicted, Coefficient analysis)

