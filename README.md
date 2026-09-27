# Regression and Classification: Error Analysis — Indian Used-Car Market

**Homework Assignment 2** · Introduction to Data Science, HIT · Dr. Uri Itai, TA: Hanit Ohayon Hadad

**Student:** Ishay Hanufa · **ID:** 322368796

## Contents
- `used_cars_error_analysis.ipynb` — the full analysis (executed, with outputs)
- `used_cars_data.csv` — the dataset ([Cars Dataset on Kaggle](https://www.kaggle.com/datasets/ayushparwal2026/cars-dataset)), same as Assignment 1

## Summary
- **Regression** (target: log price) with Linear Regression, Decision Tree, Random Forest, Gradient Boosting, and bonus KNN and SVR; 5-fold cross-validation, with the choice of k justified experimentally.
- **Best model: Gradient Boosting.** R² = 0.95 on log price, MAE = 1.39 Lakh, median error ≈ 10%.
- **Classification** (price above the median) with Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, and bonus KNN. Best ROC-AUC = 0.981.
- **Main failure modes:** rare and luxury brands, very old cars, cars priced near the classification threshold, and a few implausible listings where the model was right and the label was wrong.

## How to run
pip install pandas numpy matplotlib seaborn scipy scikit-learn jupyter
Open the notebook and run all cells (takes about 2–3 minutes).
