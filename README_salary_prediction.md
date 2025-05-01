# Salary Prediction Model for New Hires

## Overview

This project presents a machine learning solution for recommending fair salary levels for potential new hires. The model is designed to support internal equity by aligning salary offers with the company's existing compensation structure.

An XGBoost regression model was developed using employee data, and deployed through a simple, user-friendly application for recruiters and HR teams.

> Note: The model was trained on the full dataset without a train/test split, as the goal was to precisely replicate the current internal salary structure for decision-support purposes.

## Key Features

- **Objective:** Ensure internal fairness in salary offers for new employees
- **Algorithm used:** XGBoost Regressor
- **Evaluation metrics:**
  - R² Score: 0.999
  - Mean Absolute Error (MAE): €26.25
  - Mean Absolute Percentage Error (MAPE): 1.84%
- **Input variables:**
  - Age
  - Gender
  - Department
  - Job Complexity Level
  - Education Level
- **Most influential variables:** Job Complexity Level, Department

## Files Included

- `salary_prediction_model.ipynb` – Jupyter notebook with full code and model analysis
- `Salary_Prediction_Report_EN.pdf` – PDF report explaining methodology, results, and recommendations
- `salary_prediction_app.png` – Image of the application used for salary recommendation

## Application Preview

![Salary Prediction App](salary_prediction_app.png)

## Notes

> All data in this project has been anonymized or synthetically modified to protect confidentiality.

## Author

Prepared by Jelena Pantić  
[GitHub Portfolio](https://github.com/Jelena44)
