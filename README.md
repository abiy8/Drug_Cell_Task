# Drug Response Regression

Exploratory notebook for predicting IC50 with a random forest using the included GDSC-related tabular data.

**Stack:** Python · pandas · NumPy · scikit-learn

## Contents

- `task/Untitled.ipynb` — data preparation, categorical encoding, regression, MSE / R², and prediction export.
- `task/GDSC1(6)-GESC2(6).csv` — input data.
- `task/IC50_predictions.csv` — existing prediction export.

## Run

Install `jupyter pandas numpy scikit-learn`, start Jupyter from the `task/` directory, and open `Untitled.ipynb`. The notebook currently uses an absolute Windows CSV path. Before running your local copy, point that path to the included CSV.

## Status

This is an exploratory learning task. Early cells include an intermediate feature/imputation attempt before later modeling cells; the notebook needs a consolidated preprocessing pipeline for reliable top-to-bottom execution. Existing exported predictions are not clinical evidence. No medical or production use is claimed.
