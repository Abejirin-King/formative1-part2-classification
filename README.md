# Formative 1 Part 2: Classical ML Classification Challenge

This repository contains the completed working notebook for the ALU Formative 1 Part 2 classification competition.

## Contents
- `Formative1Part2_Classification.ipynb`: end-to-end data exploration, preprocessing, baseline, XGBoost and LightGBM experiments, validation, plots, discussion, and submission generation.
- `requirements.txt`: Python dependencies used by the notebook.

## Best local validation result
- Logistic regression baseline: 0.6567 holdout ROC-AUC; 0.6520 five-fold mean.
- XGBoost deeper: 0.8288 holdout ROC-AUC; 0.8282 five-fold mean (std 0.0018).
- LightGBM complex: 0.8280 holdout ROC-AUC; 0.8273 five-fold mean (std 0.0021).

## Reproducibility
Use Python 3 with pandas, numpy, scikit-learn, xgboost, lightgbm, matplotlib, and wandb. Attach the competition data (`train.csv`, `test.csv`, and optionally `sample_submission.csv`) before running the notebook.

The W&B API key must be supplied through a secret. It must never be hardcoded into the notebook or committed to this repository.
