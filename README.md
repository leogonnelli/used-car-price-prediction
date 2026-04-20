# Used Car Price Prediction

Machine learning project developed for the Business Analytics and Data Science course (University of St. Gallen).  
Goal: predict used car prices in a private Kaggle class competition.

## Result

- Final ranking: 3rd out of 34 participants
- Main models evaluated: Linear Regression, Random Forest, XGBoost, LightGBM
- Final submission approach: LightGBM

## Project Structure

```text
.
├── data/                 # Train/test and processed datasets
├── Notebooks/            # End-to-end modeling notebooks
├── Scripts/              # Reusable preprocessing utilities
├── results/              # Competition submissions and model outputs
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
3. Open notebooks and execute the model you want

## Model Performance (Validation)

- Linear Regression: RMSE 3621.28, R^2 0.844
- Random Forest: RMSE 1995.52, R^2 0.953
- XGBoost: RMSE 2024.35, R^2 0.951
- LightGBM: RMSE 1892.37











