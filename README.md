# Breast Cancer Prediction (Malignant or Benign)

Classifies breast tumours as malignant or benign from cell measurements, comparing several machine learning models.

This is a small machine learning project I made while learning Python and data science.

## What it does

- Explores the dataset and checks for missing values and duplicates
- Maps the diagnosis to binary labels (B = 0, M = 1)
- Uses a stratified train/test split and scales features with `StandardScaler`
- Trains and compares **Logistic Regression**, **K-Nearest Neighbours** and **Random Forest**
- Evaluates with accuracy, precision, recall and F1 score

## Results

| Model | Accuracy | Precision | Recall | F1 |
|---|---|---|---|---|
| **Random Forest** | **97.4%** | 100% | 92.9% | 96.3% |
| Logistic Regression | 96.5% | 97.5% | 92.9% | 95.1% |
| KNN | 95.6% | 97.4% | 90.5% | 93.8% |

## Files

- `cancer.ipynb`
- `data-cancer.csv`

## Run it

```
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook cancer.ipynb
```
