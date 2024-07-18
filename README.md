# Netflix Subscription Forecasting

## Overview

This repository contains Python scripts and Jupyter notebooks for forecasting Netflix quarterly subscriptions using time series analysis techniques.

### Project Structure

- **Data:** Contains the dataset (`Netflix-Subscriptions.csv`) used in the analysis.
- **Notebooks:** Jupyter notebooks (`Netflix_Subscriptions_Forecasting.ipynb`) containing detailed code and visualizations.
- **Scripts:** Python scripts for data preprocessing, model training, and forecasting.
- **Results:** Includes graphs and visualizations generated from the data and models.

### Workflow

1. **Data Preparation:**
   - Importing necessary Python libraries: Pandas, NumPy, Matplotlib, Plotly.
   - Reading and preprocessing Netflix subscription data.
   - Visualizing Netflix quarterly subscriptions growth using line and bar graphs.

2. **Analysis:**
   - Calculating quarterly and yearly growth rates of Netflix subscriptions.
   - Implementing ARIMA (AutoRegressive Integrated Moving Average) model for forecasting.

3. **Model Evaluation:**
   - Evaluating model performance using metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

4. **Prediction:**
   - Generating predictions for future quarters using the trained ARIMA model.

