# Heart Disease Prediction

Predicting heart disease using Logistic Regression (UCI dataset, 303 rows).

## Dataset
303 rows, 14 columns. Target: 1 = disease, 0 = healthy.

## Methods
- EDA, hypothesis tests (t-test, chi-square)
- Feature engineering (thalach_ratio, One-Hot Encoding)
- RobustScaler
- Logistic Regression + Cross-Validation

## Results
- Test accuracy: ~90%
- CV accuracy: ~82% (±5.8%)

## Getting Started
pip install -r requirements.txt
jupyter notebook Heart_Disease_Prediction.ipynb
