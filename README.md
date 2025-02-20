# SHAP Hyperparameter Tuning

This project demonstrates how SHAP (SHapley Additive exPlanations) can be used to analyze feature importance when tuning hyperparameters for an XGBoost model.

## Dataset
- **California Housing Dataset** from `sklearn.datasets.fetch_california_housing()`
- Data source: Derived from the 1990 U.S. Census
- More details: [Scikit-Learn Documentation](https://scikit-learn.org/stable/datasets/real_world.html#california-housing-dataset)

## Requirements
Ensure you have the following Python libraries installed:
```bash
pip install shap xgboost numpy pandas scikit-learn matplotlib
```

## Running the Code
Run the script to:
1. Load the California Housing dataset.
2. Train two XGBoost models with different hyperparameters.
3. Compute SHAP values for feature importance.
4. Generate SHAP summary plots for model comparison.

## Key Files
- `shap_hyperparam_tuning.py` - Main script
- `README.md` - Project documentation

## Credits
- **SHAP**: Lundberg et al., "A Unified Approach to Interpreting Model Predictions"
- **California Housing Dataset**: Derived from the 1990 U.S. Census
- **XGBoost**: Chen & Guestrin, "XGBoost: A Scalable Tree Boosting System"
