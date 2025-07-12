#  ML Valorant Player Earnings Predictor

A machine learning project to predict professional Valorant player earnings based on their competitive performance.

##  Overview

This project uses historical data of Valorant esports players including:

- Medal counts (Gold, Silver, Bronze)
- S-tier tournament presence
- Actual earnings

A regression model predicts player earnings and evaluates errors on a per-player basis to assess prediction fairness and model accuracy.

##  Key Features

- Linear regression-based earnings prediction
- Evaluation using MAE (Mean Absolute Error)
- Error analysis grouped by player
- Normalized error-to-earning ratio analysis
- Visual insights via histogram

##  Technologies

- Python
- pandas
- scikit-learn
- matplotlib
- numpy

##  Example Outputs

- Predictions appended to test data
- Histogram of prediction error ratio per player
- Ranked players by prediction error relative to their earnings
