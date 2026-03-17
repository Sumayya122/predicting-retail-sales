# Predicting Retail Sales Using Machine Learning

## Project Overview
This project develops an end-to-end predictive analytics pipeline to predict retail sales using a Superstore sales dataset. The notebook includes exploratory data analysis, preprocessing, model development, and evaluation.

## Files in the Repository
- `sales_forecasting.ipynb` — main notebook containing the complete analysis
- `train.csv` — dataset used for modelling
- `README.md` — project overview and run instructions
- `requirements.txt` — required Python packages

## Required Packages
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- plotly
- jupyter

## Setup and Running Instructions
1. Download or clone the repository.
2. Ensure that `train.csv` is stored in the same folder as `sales_forecasting.ipynb`.
3. Install the required packages using:
   ```bash
   pip install -r requirements.txt

## Notes
The final selected model was Linear Regression, which achieved a lower RMSE than Random Forest on the test set.