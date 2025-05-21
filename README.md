# 💰 Personal Loan Acceptance Prediction using ML

Predicting personal loan acceptance using supervised machine learning models: Logistic Regression, K-Nearest Neighbors (KNN), and Complement Naive Bayes.

## Overview

This project focuses on predicting whether a bank customer will accept a personal loan offer based on their demographic and financial attributes. We implement and compare three supervised machine learning algorithms: Logistic Regression, K-Nearest Neighbors (KNN), and Complement Naive Bayes.

## Dataset

- `Bank_Personal_Loan_Modelling.csv` — The main dataset containing customer demographic, financial, and loan offer acceptance information.
- `uszips.xls` — A supplementary dataset containing information about U.S. zip codes.

## Models Used

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Complement Naive Bayes

## How to Run

### Notebooks

| File | Description |
|------|-------------|
| `personal_loan_prediction.ipynb` | Clean version of the notebook without heavy outputs (viewable on GitHub) |
| `personal_loan_prediction_full_output.ipynb` | Full version with all model outputs and visualizations (download to run locally) |


1. Clone the repo:

```bash
git clone https://github.com/YOUR_USERNAME/personal-loan-prediction.git
cd personal-loan-prediction
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Run the Jupyter Notebook:
``` bash
jupyter notebook Personal_Loan_Classification.ipynb
```


---

### Model results

```markdown
 Final Evaluation Metrics Table:

| Model                                     | Accuracy | Precision | Recall | F1 Score | ROC AUC |
|-------------------------------------------|-----------|-----------|-----------|-----------|-----------|
| Logistic Regression                       | 0.8880    | 0.9481    | 0.8880    | 0.9064    | 0.9807    |
| K-Nearest Neighbors                       | 0.9230    | 0.9290    | 0.9230    | 0.8908    | 0.9592    |
| Complement Naive Bayes                    | 0.6325    | 0.9048    | 0.6325    | 0.7149    | 0.8018    |
| Ensemble Model(Logistic Regression + KNN) | 0.9761    | 0.9755    | 0.9761    | 0.9749    | 0.9857    |
 	 	
```
