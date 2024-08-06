# Chronic Kidney Disease Prediction Using Machine Learning

## Project Overview
This project uses machine learning models to predict Chronic Kidney Disease (CKD) outcomes and identify key risk factors. By analyzing a diverse set of health-related features, we aim to achieve high accuracy in CKD prediction and provide valuable insights for healthcare practitioners and policymakers.

## Dataset
The project uses a dataset ('kidney.csv') containing 319,795 entries with 18 health-related features, including:
- Demographic information (Sex, Age, Race)
- Health conditions (Heart Disease, Stroke, Diabetes, etc.)
- Lifestyle factors (Smoking, Alcohol Drinking, Physical Activity)
- Physical measurements (BMI, Sleep Time)
  
## Data Preprocessing
- Renamed 'KidneyDisease' column to 'hasKD'
- Encoded binary columns to 0 and 1
- Simplified categorical variables (e.g., 'Diabetic')
- Removed columns with string data ('GenHealth', 'Race', 'AgeCategory')

## Exploratory Data Analysis
- Visualized kidney disease prevalence by age and race
- Created histograms to show relationships between features (e.g., BMI) and kidney disease
- Performed correlation analysis using heatmaps
  
## Feature Selection
Two methods were used for feature selection:
1. Decision Tree-based feature importance
2. Recursive Feature Elimination (RFE) with Linear Regression
Both methods selected the top 15 features for modeling.

## Model Training and Evaluation
- Used Random Forest Classifier for modeling
- Split data into training (80%) and testing (20%) sets
- Evaluated model performance using accuracy score and classification report

## Conclusion / Key Findings
- Identified important features for CKD prediction, including BMI, Sleep Time, Mental Health, and Physical Health
- Visualized the prevalence of kidney disease across different age groups and races
- Explored the relationship between BMI and kidney disease
