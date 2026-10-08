# Polynomial Regression Assignment

Roll number: **BT2024195**

This repository contains the datasets, notebooks, generated plots, final predictions, and the final PDF report for the polynomial regression assignment.

## Repository Structure

```text
ml_assignment/
├── data/                     # Train/test datasets and sample submission files
│   ├── train.csv
│   ├── test.csv
│   └── sample_submission.csv
├── images/                   # Generated EDA, model-selection, residual, and diagnostic plots
│   ├── var1/
│   └── var2/
├── notebooks/                # Model development, tuning, validation, and inference notebooks
│   ├── var1_power_turbine.ipynb
│   └── var2_thermal_reservoir.ipynb
├── predictions/              # Final prediction CSVs for submission
│   ├── BT2024195_pred_var1.csv
│   └── BT2024195_pred_var2.csv
├── report/                   # Final PDF report folder
│   └── BT2024195 Polynomial Regression Report.pdf
├── README.md                 # Project overview and instructions
├── .gitignore
└── .git/
```

## Final Models

| Problem | Degree | Model | 10-fold CV R2 |
|---|---:|---|---:|
| var1 | 5 | ElasticNet, alpha = 0.009103, l1_ratio = 1.0 | 0.971316 +/- 0.004937 |
| var2 | 10 | ElasticNet, alpha = 0.000655, l1_ratio = 0.1 | 0.994225 +/- 0.002097 |

## Key Files

- `notebooks/var1_power_turbine.ipynb`
- `notebooks/var2_thermal_reservoir.ipynb`
- `predictions/BT2024195_pred_var1.csv`
- `predictions/BT2024195_pred_var2.csv`
- `report/BT2024195 Polynomial Regression Report.pdf`

If rerunning the notebooks, open them from the `notebooks/` folder so their relative paths resolve to `../data/`, `../images/`, and `../predictions/`.
