# Data

This directory contains the datasets used for the stroke risk factor analysis project.

## Main Dataset
- `healthcare-dataset-stroke-data.csv`: The primary dataset from Kaggle containing patient information including demographic data, medical history, and stroke occurrence.

## Dataset Description
The Stroke Prediction Dataset includes 5110 patients with these features:
- Demographics: gender, age, residence type
- Medical factors: hypertension, heart disease, glucose levels, BMI
- Lifestyle factors: smoking status, work type, marital status
- Target variable: stroke occurrence (0/1)

## Data Sources
- Original dataset: [Kaggle Stroke Prediction Dataset](https://www.kaggle.com/fedesoriano/stroke-prediction-dataset)
- Supporting data: Metrics from Global Burden of Disease Study 2019

## Data Preprocessing
The raw data required several preprocessing steps:
- Handling missing values in BMI using random sampling
- Handling 'Unknown' values in smoking_status
- Removing extreme outliers (BMI > 55)
- Balancing the dataset using resampling techniques
- Feature engineering and encoding categorical variables

## Data Usage Notes
- The dataset contains an imbalanced distribution of stroke cases (only 4.9% positive)
- The reliability of this dataset for clinical purposes is limited as noted in the disclaimer
