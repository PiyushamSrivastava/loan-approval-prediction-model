# Loan Approval Prediction

Predicts loan approval status using applicant financial and demographic data.

## Dataset
[Kaggle: Loan Approval Prediction Dataset](your-kaggle-link)

## Models Tried
- Logistic Regression — 91.3% accuracy
- Random Forest — 98.2% accuracy (final model)
- XGBoost — 98.2% accuracy

## Key Insight
`cibil_score` is by far the most important feature (~80% importance), 
followed by `loan_term`. Other features contribute minimally.

## How to Run
1. `pip install -r requirements.txt`
2. Open `notebook.ipynb` and run all cells

## Results
- Final model: Random Forest (n_estimators=300)
- Accuracy: 98.2%
- Precision/Recall (Approved): 98%/99%
