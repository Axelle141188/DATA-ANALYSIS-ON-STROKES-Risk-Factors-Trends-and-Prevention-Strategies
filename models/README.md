# Models

This directory contains the machine learning models developed for stroke prediction and their evaluation metrics.

## Model Files
- `logistic_regression_model.pkl`: Logistic Regression model (78.8% accuracy)
- `decision_tree_model.pkl`: Decision Tree model (98.0% accuracy)
- `random_forest_model.pkl`: Random Forest model (98.9% accuracy)
- `ensemble_model.pkl`: Stacking ensemble model combining the three approaches (99.9% accuracy)

## Hyperparameters
- Logistic Regression: C=0.01, penalty='l1', solver='liblinear'
- Decision Tree: criterion='gini', max_depth=50, min_samples_leaf=1, min_samples_split=5
- Random Forest: n_estimators=100, max_depth=20, min_samples_split=2, class_weight='balanced_subsample'

## Evaluation Metrics
- `model_performance_comparison.csv`: Table of precision, recall, F1-score, and AUC for all models
- `confusion_matrices.json`: Confusion matrices for each model on test data
- `feature_importance.csv`: Feature importance rankings from the Random Forest model

## Model Development Process
The models were developed using:
- SMOTE for handling class imbalance
- StandardScaler for feature normalization
- Cross-validation with 5 folds
- Grid search for hyperparameter optimization
