# Car Price Regression — Historical ML Project

> Historical Data Science project preserved as part of my technical progression. My current portfolio focus is Data Engineering and cloud data platforms.

## Overview

This repository explores regression modeling for vehicle prices using structured automotive attributes from `CarPrice_Assignment.csv`.

The original notebook evaluates a linear-regression workflow and reports the following cross-validation metrics from that experiment:

| Metric | Reported value |
|---|---:|
| MAE | 0.2569 |
| MSE | 0.1527 |
| RMSE | 0.3695 |
| R² | 0.8163 |
| RMSLE | 0.1839 |
| MAPE | 1.3264 |

These values are retained as results of the original notebook execution; they should not be interpreted as a production benchmark without reproducing the full preprocessing and validation pipeline.

## Repository structure

```text
.
├── car_price_regression.ipynb       # modeling notebook
├── CarPrice_Assignment.csv           # dataset
├── requirements.txt                  # reproducibility dependencies
└── .github/workflows/quality.yml      # lightweight validation
```

## Workflow

```text
Raw tabular data
   ↓
EDA and preprocessing
   ↓
Feature preparation
   ↓
Linear regression
   ↓
Cross-validation
   ↓
Regression metrics
```

## Reproduce locally

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook car_price_regression.ipynb
```

## What this project demonstrates

- regression modeling with scikit-learn;
- feature analysis and tabular preprocessing;
- cross-validation and multi-metric evaluation;
- exploratory analysis with Pandas, Matplotlib and Seaborn.

## Portfolio context

For current engineering work, see [`harrisvailvelame/pedrohvel`](https://github.com/harrisvailvelame/pedrohvel), including tested Medallion and dbt reference implementations.

---

**Author:** Harrison Grant Vail  
[LinkedIn](https://www.linkedin.com/in/harrison-grant-vail) · [GitHub](https://github.com/harrisvailvelame)
