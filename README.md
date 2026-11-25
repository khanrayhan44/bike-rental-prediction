# Bike Rental Demand Prediction

A Machine Learning project focused on understanding and predicting bike rental demand using historical rental data.

## Project Overview

Bike rental demand can change depending on different factors such as time, weather, season, and working days.

The goal of this project is to explore historical bike rental data, identify important patterns, and eventually build a Machine Learning model to predict bike rental demand.

## Objectives

- Understand and analyze bike rental data.
- Perform Exploratory Data Analysis (EDA).
- Identify patterns and relationships between features.
- Prepare data for Machine Learning.
- Build and evaluate a Bike Rental Demand Prediction model.

## Dataset

This project uses the Bike Sharing Dataset, which contains hourly and daily bike rental records.

**Dataset files:**
- `hour.csv` — Hourly bike rental data.
- `day.csv` — Daily bike rental data.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Git & GitHub

## Project Structure

```text
bike-rental-prediction/
│
├── data/
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   └── 02_exploratory_data_analysis.ipynb
│
├── src/
├── README.md
└── requirements.txt
```

## Exploratory Data Analysis

Completed analyses include:

- Dataset overview and data types
- Missing value and duplicate checking
- Numerical feature distributions
- Categorical feature analysis
- Correlation analysis
- Target variable distribution
- Hourly rental demand patterns
- Weather condition vs rental demand analysis

### Preliminary Findings

**1. Hourly Rental Pattern**

- Bike rental demand peaks around 8 AM and 5 PM.
- This pattern may indicate increased bike usage during morning and evening commuting hours.
- The `hr` feature may help the Machine Learning model capture time-based demand patterns.

**2. Feature Correlation**

- `temp` and `atemp` show a very strong positive correlation (0.99).
- `temp` has the strongest positive correlation with rental demand among the numeric features.
- `hum` shows the strongest negative correlation with rental demand.

**3. Weather Impact**

- Rental demand tends to decrease as weather conditions worsen.
- Clear weather has higher median rental demand than light rain/snow conditions.
- Heavy rain/snow observations are too limited for reliable conclusions.

*Note: These are preliminary observations from the dataset and may be refined through further analysis.*

## Current Progress

- [x] Project Setup
- [x] Data Understanding
- [x] Exploratory Data Analysis
- [ ] Feature Engineering
- [ ] Data Preprocessing
- [ ] Model Training
- [ ] Model Evaluation
- [ ] Model Improvement
- [ ] Model Deployment

## Future Goals

- Build a Machine Learning model using Scikit-learn.
- Compare different regression algorithms.
- Evaluate model performance using appropriate metrics.
- Improve prediction accuracy through feature engineering.
- Deploy the final model as an application.

## Project Status

Data Understanding and Exploratory Data Analysis completed.

Currently preparing for Feature Engineering.

## Author

### Rayhan Khan

- GitHub: [khanrayhan44](https://github.com/khanrayhan44)
- Portfolio: [khanrayhan.netlify.app](https://khanrayhan.netlify.app/)