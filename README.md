# Stroke Risk Factors Analysis & Prediction

## Overview

This project presents a comprehensive analysis of stroke risk factors using the Kaggle Stroke Prediction Dataset, complemented by insights from the Global Burden of Disease Study 2019. Through statistical analysis and machine learning techniques, we identify significant risk factors, develop predictive models with 98%+ accuracy, and propose evidence-based prevention strategies.

## Project Objectives

- Identify and analyze the most significant risk factors for strokes
- Determine how these factors influence the probability of having a stroke
- Explore patterns of stroke prevalence across different populations
- Develop accurate predictive models to assess stroke risk
- Formulate comprehensive prevention strategies based on data findings

## Key Findings

- **Primary Risk Factors**: Advanced age, hypertension, heart disease, elevated glucose levels, and high BMI are the most significant risk factors
- **Risk Factor Impact**:
  - Hypertensive patients show 13.25% stroke incidence vs. 3.97% in non-hypertensive patients
  - Stroke incidence increases dramatically after age 60
  - Patients with high glucose levels show significantly higher stroke rates
- **Model Performance**: Our ensemble model achieved 99.95% accuracy with an AUC of 1.00, indicating exceptional discriminative ability
- **Prevention Potential**: Management of identified risk factors could significantly reduce global stroke burden

## Data & Methodology

### Data Sources
- **Primary Dataset**: [Kaggle Stroke Prediction Dataset](https://www.kaggle.com/fedesoriano/stroke-prediction-dataset)
- **Supporting Literature**: Global Burden of Disease Study 2019 (GBD 2019)

### Analysis Approach
1. **Data Exploration**: Comprehensive analysis of dataset variables and their distributions
2. **Statistical Testing**: Applied t-tests and chi-square tests to identify significant relationships
3. **Feature Engineering**: Created derived features to enhance model performance
4. **Modeling Pipeline**:
   - Data preprocessing (handling missing values, scaling)
   - Model development (Logistic Regression, Decision Tree, Random Forest)
   - Ensemble modeling for improved accuracy
   - Cross-validation and performance evaluation

## Repository Structure

- **`data/`**: Datasets used in the analysis
- **`docs/`**: Comprehensive project documentation and full report
- **`models/`**: Saved machine learning models and evaluation metrics
- **`notebooks/`**: Jupyter notebooks detailing the analysis process
- **`visualizations/`**: Generated charts, graphs, and visual representations of findings

## Technologies Used

- **Python**: Primary programming language
- **Data Analysis**: pandas, numpy
- **Machine Learning**: scikit-learn, imblearn (for handling imbalanced data)
- **Statistical Analysis**: scipy, statsmodels
- **Visualization**: matplotlib, seaborn, plotly

## Results Visualization

### Stroke Rate by Risk Factors

### Model Performance

