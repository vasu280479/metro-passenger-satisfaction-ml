# Metro Rail Passenger Satisfaction ML

Interview-ready end-to-end ML classification project based on a Metro Rail passenger-satisfaction business case.

## Public data
Uses Kaggle `teejmahal20/airline-passenger-satisfaction` as a transparent proxy. Airline records are not presented as actual Metro observations.

## Workflow
Data acquisition, audit, cleaning, EDA, leakage-safe preprocessing, Decision Tree/Random Forest/XGBoost comparison, five-fold cross-validation, confusion matrix, ROC and PR curves, permutation importance, error analysis, threshold tuning, model export, and inference helper.

## Colab
Upload `metro_passenger_satisfaction_end_to_end.ipynb`, open it in Google Colab, and select **Runtime > Run all**. The notebook downloads the dataset using KaggleHub. If access is restricted, upload Kaggle `train.csv` and `test.csv` when prompted.

## GitHub
```bash
git init
git add .
git commit -m "Add passenger satisfaction ML project"
git branch -M main
git remote add origin YOUR_REPOSITORY_URL
git push -u origin main
```

## Responsible-use note
Replace the proxy dataset with representative Metro data before operational use. Add privacy review, fairness testing, monitoring, and domain validation for production.
