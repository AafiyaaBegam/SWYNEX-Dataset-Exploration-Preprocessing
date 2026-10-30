# SWYNEX — Task 1: Dataset Exploration & Preprocessing

This repository contains the notebook for Task 1 of the SWYNEX Machine Learning Internship.

## Objective
Explore a dataset, inspect and handle missing values, encode categorical features, and prepare model-ready training and test features.

## Dataset
Titanic passenger dataset from the public Seaborn data repository:
https://raw.githubusercontent.com/mwaskom/seaborn-data/master/titanic.csv

The notebook downloads the CSV when executed, so an internet connection is required.

## Repository structure
```text
SWYNEX-Dataset-Exploration-Preprocessing/
├── README.md
├── requirements.txt
└── notebooks/
    └── SWYNEX_Task1_Dataset_Exploration_Preprocessing.ipynb
```

## Run locally
```bash
python -m pip install -r requirements.txt
jupyter notebook
```
Open the notebook under `notebooks/` and run all cells from top to bottom.

## Work covered
- Dataset loading and inspection
- Descriptive statistics and visual exploration
- Missing-value and duplicate inspection
- Feature and target selection
- Train/test split
- Median and most-frequent imputation
- Standard scaling
- One-hot encoding
- Export of processed train/test features

**Scope note:** This is a dataset preparation task. Model training and evaluation are reserved for later tasks.
