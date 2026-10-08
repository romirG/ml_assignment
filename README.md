# Polynomial Regression Assignment

Roll number: **BT2024195**

This repository contains the code, datasets, predictions, generated figures, and report for the polynomial regression assignment.

## Repository Structure

```text
.
├── data/          # Train/test CSV files and sample submission
├── images/        # Generated EDA, model selection, residual, and diagnostic plots
├── notebooks/     # Training, validation, tuning, and inference notebooks
├── predictions/   # Final prediction CSV files for submission
└── report/        # Assignment report in PDF, HTML, and Markdown formats
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
- `report/BT2024195_report.html`
- `report/BT2024195_report.pdf`

The HTML report is print-ready in A4 portrait format and references figures from `images/`.

If rerunning the notebooks, open them from the `notebooks/` folder so their relative paths resolve to `../data/`, `../images/`, and `../predictions/`.
