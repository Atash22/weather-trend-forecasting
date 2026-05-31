# Weather Trend Forecasting

## PM Accelerator Mission
PM Accelerator helps aspiring product managers break into the field through 
hands-on projects, mentorship, and community. Visit: https://www.pmaccelerator.io

## Project Overview
Analysis of the Global Weather Repository dataset (144,432 records, 211 countries)
to forecast temperature trends using machine learning models.

## Notebooks
- 01_data_cleaning.ipynb — Data cleaning, outlier removal, normalization
- 02_eda.ipynb — Exploratory data analysis and visualizations  
- 03_anomaly_detection.ipynb — Isolation Forest anomaly detection
- 04_forecasting.ipynb — Linear Regression, Random Forest, XGBoost, Ensemble
- 05_spatial_analysis.ipynb — Geographic and air quality analysis

## Results
| Model | MAE | RMSE | R² |
|---|---|---|---|
| Linear Regression | 4.36°C | 6.02°C | 0.302 |
| Random Forest | 4.48°C | 5.90°C | 0.330 |
| XGBoost | 4.04°C | 5.26°C | 0.466 |
| Ensemble | 4.07°C | 5.29°C | 0.461 |

## How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Run notebooks in order: 01 → 02 → 03 → 04 → 05

## Dataset
Global Weather Repository — https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository