# Used Car Price Prediction

Machine learning project developed for the Business Analytics and Data Science course (University of St. Gallen).  
Goal: predict used car prices in a private Kaggle-style class competition.

## Result

- Final ranking: 3rd out of 34 participants
- Main models evaluated: Linear Regression, Random Forest, XGBoost
- Final submission approach: weighted blending of top models

## Project Structure

```text
.
├── data/                 # Train/test and processed datasets
├── Notebooks/            # End-to-end modeling notebooks
├── Scripts/              # Reusable preprocessing utilities
├── Results/              # Competition submission files
├── requirements.txt
├── .gitignore
└── README.md
```

## How To Run

1. Clone the repository:
   ```bash
   git clone https://github.com/leogonnelli/used-car-price-prediction.git
   cd used-car-price-prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open notebooks and execute in order:
   - `Notebooks/01_exploration.ipynb`
   - `Notebooks/02_linear_regression.ipynb`
   - `Notebooks/03_random_forest.ipynb`
   - `Notebooks/04_XGBoost.ipynb`
   - `Notebooks/06_blendering.ipynb`
   - `Notebooks/05_submission.ipynb`

## Model Performance (Validation)

- Linear Regression: RMSE 3621.28, R^2 0.844
- Random Forest: RMSE 1995.52, R^2 0.953
- XGBoost: RMSE 2024.35, R^2 0.951











