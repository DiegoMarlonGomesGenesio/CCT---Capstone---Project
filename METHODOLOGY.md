# Project Methodology

## Project Title
Predicting Peak Electricity Demand to Support Operational Planning

## 1. Methodological Approach
The project will follow the CRISP-DM framework: business understanding, data understanding, data preparation, modelling, evaluation and presentation of results.

The objective is to forecast electricity demand one hour ahead and identify potential peak-demand periods across three distribution zones in Tetouan, Morocco.

## 2. Data Understanding and Preparation
- Import the UCI Power Consumption of Tetouan City dataset using Python and Pandas.
- Check data types, timestamps, missing values, duplicates and measurement intervals.
- Explore electricity consumption patterns by hour, day and distribution zone.
- Examine relationships between consumption and weather variables.
- Create time-based features and lagged consumption features.
- Define the forecasting target as electricity demand one hour ahead.

## 3. Predictive Modelling
Three approaches will be compared:
- Persistence baseline: use the latest available consumption measurement as a simple forecast.
- Linear Regression: provide an interpretable statistical model.
- Random Forest Regression: investigate potentially non-linear relationships.

Separate forecasts will be considered for the three distribution zones.

Only information available at the prediction time will be used. Future observed weather values will not be included unless equivalent forecasts would realistically be available.

## 4. Training and Evaluation
The dataset will be split chronologically into training, validation and test periods.

Model performance will be assessed using:
- Mean Absolute Error (MAE).
- Root Mean Squared Error (RMSE).
- Comparison against the persistence baseline.

Peak-demand periods will be defined using a threshold calculated from training data. The study will also evaluate how effectively the predicted demand identifies high-demand periods.

## 5. Tools and Technologies
- Python: programming language.
- Jupyter Notebook: development environment.
- Pandas and NumPy: data preparation and analysis.
- Matplotlib and Seaborn: visualisation.
- Scikit-learn: predictive modelling and evaluation.
- GitHub: version control and project documentation.
- Streamlit: optional interactive dashboard.

## 6. Proposed Workflow
1. Obtain the public dataset from UCI.
2. Validate and prepare the data.
3. Conduct exploratory data analysis.
4. Create time-based and lagged features.
5. Split the dataset chronologically.
6. Train baseline and predictive models.
7. Evaluate forecast accuracy and peak-demand identification.
8. Present findings through charts, a dashboard and a final report.

## 7. Limitations
The dataset covers one city during 2017. The project will not claim to measure actual financial savings, network failures or operational improvements without additional supporting data.

This document describes the planned methodology. Model training and final evaluation will take place during the implementation stage of the Capstone. 
