# Superconduct-ML-Project
"Machine learning project using Superconduct dataset from Kaggle"

## Project Title
**Superconduct Critical Temprature Prediction using Machine Learning**

## Dataset
This project uses the [Superconductivity Dataset] (https://www.kaggle.com/datasets/mespadoto/superconductivty-data) from Kaggle, which contains features describing the properties of superconducting materials and their corresponding critical temperatures. 

- **File used:** `superconduct-train-new.csv` (27MB, locally stored)
- **Rows:** 21,263
- **Features:** 81 features including `critical_temp` (target variable)

## Objective
To build and evaluate machine learning models that can accurately predict the **critical temperature** of superconductors and chemical properties.

## ML Models Used
- Linear Regression
- Random Forest
- XGBoost
- Support Vector Regression (SVR)

## Tools & Libraries
- **R Programming**
- `tidyverse`, `caret`, `randomForest`, `xgboost`, `e1071`, `corrplot`, `data.table`
- RMarkdown for report generation

## Evaluation Metrics
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score

## Visualizations
The project includes the following:
- Correlation heatmaps
- Distribution of critical temperatures
- Feature importance plots
- Predicted vs Actual comparison graphs

## Files Included
File                                        Description 
`Superconduct-ML-Project.R`                 Full R script for data analysis & modeling 
`Supercondut-ML-Project.Rmd`                RMarkdown report with code, plots, and results
`Superconduct-ML-Project.pdf`               Final PDF report exported from RMarkdown
`superconduct-train-new.csv`                Kaggle dataset file (tracked locally)









