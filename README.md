# Solar Energy Generation Prediction

This repository contains the code and documentation for predicting solar energy generation using various models such as SARIMA, Random Forest, and XGBoost.

## Table of Contents
- [Project Overview](#project-overview)
- [Directory Structure](#directory-structure)
- [Data](#data)
- [Notebooks](#notebooks)
- [Results](#results)
- [Documentation](#documentation)

## Project Overview
This objective of this project is to predict solar energy generation using advanced analytical methods. The specific objectives include:
-  Analyzing historical data on solar energy production and relevant weather conditions.
-  Developing forecasting models using time series analysis technique, SARIMA.
-  Incorporating machine learning algorithms such as random forests and gradient boosting.
-  Evaluating the models' performance using metrics like root mean squared error (RMSE) and mean absolute percentage error (MAPE).


## Directory Structure
```plaintext
├── Data/
│   ├── Plant_2_Generation_Data.csv
│   └── Plant_2_Weather_Sensor_Data.csv
├── Docs/
│   ├── 1_Project Proposal
│   └── 4_Capstone_Final_Report_Solar Power Generation
├── Notebook/
│   ├── 2_Data Wrangling and EDA.ipynb
│   └── 3_Pre-processing Work and Model.ipynb
├── Results/
│   ├── Model_metrics.txt
│   ├── Random_Forest_feature_importance.png
│   ├── Random_Forest_plot.png
│   ├── Random_Forest_plot_tuning.png
│   ├── Sarima_plot.png
│   ├── Sarima_plot_tuning.png
│   ├── XGBoost_feature_importance.png
│   ├── XGBoost_plot.png
│   ├── XGBoost_plot_tuning.png
└── README.md

## Data
The Data directory contains the solar power generation data used in this project. The dataset that is used in this study taken from Solar Power plant Dataset, which contains data from two separate solar power plants located in India, with a particular focus on Plant 2. Solar power generation data gathered at 15 minutes intervals over a 34-day period, providing time-series information about power generation and weather conditions.

## Notebooks
The Notebook directory contains Jupyter notebooks used for data wrangling, exploratory data analysis (EDA), preprocessing, and modeling. These notebooks provide step-by-step procedures and visualizations used to clean the data, explore its characteristics, and build the predictive models. The main notebooks included are:

  - 2_Data Wrangling and EDA.ipynb: Covers data cleaning and exploratory data analysis.
  - 3_Pre-processing Work and Model.ipynb: Covers data preprocessing, feature engineering, model training, and evaluation.

## Results
The Results directory contains the model metrics and plots comparing the actual vs. predicted values for each model, as well as feature importance plots. These results help in understanding the performance and importance of different features in the models. The main files included are:

  - Model_metrics.txt: Summarizes the performance metrics for each model.
  - Random_Forest_feature_importance.png: Feature importance plot for the Random Forest model.
  - Random_Forest_plot.png: Plot showing Random Forest model predictions vs. actual values before tuning.
  - Random_Forest_plot_tuning.png: Plot showing Random Forest model predictions vs. actual values after tuning.
  - Sarima_plot.png: Plot showing SARIMA model predictions vs. actual values before tuning.
  - Sarima_plot_tuning.png: Plot showing SARIMA model predictions vs. actual values after tuning.
  - XGBoost_feature_importance.png: Feature importance plot for the XGBoost model.
  - XGBoost_plot.png: Plot showing XGBoost model predictions vs. actual values before tuning.
  - XGBoost_plot_tuning.png: Plot showing XGBoost model predictions vs. actual values after tuning.


## Documentation
The Docs directory contains the project proposal and the final report. These documents provide a detailed explanation of the project's objectives, methodology, results, and conclusions. The main files included are:

  - 1_Project Proposal: The initial project proposal outlining the objectives and approach.
  - 4_Capstone_Final_Report_Solar Power Generation: The final report detailing the analysis, results, and conclusions.
