# EV Purchase Prediction & Consumer Behavior Analysis

This is a Kaggle machine learning project focused on predicting EV purchase intention.

I compared Logistic Regression, Random Forest, and XGBoost using 5-fold cross-validation, then used SHAP to interpret the main factors influencing model predictions.

## Results

| Model | Mean ROC-AUC |
|---|---:|
| Logistic Regression | 0.938 |
| Random Forest | 0.933 |
| XGBoost | **0.941** |

XGBoost achieved the best overall performance.

## Key Findings

The most important predictive factors included:

- Environmental concern
- Subsidy availability
- Annual income
- Range anxiety
- Home charging access

## Tools

Python · pandas · scikit-learn · XGBoost · SHAP · matplotlib

## Files

- `EV_Purchase_Prediction.ipynb` — full analysis and modeling workflow
- `submission.csv` — Kaggle submission file
