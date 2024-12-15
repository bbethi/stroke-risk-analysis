# Assessing the Risk Factors Associated with Stroke

This repository contains the materials for the project **"Assessing the Risk Factors Associated with Stroke"**. The project explores the relationships between various risk factors (e.g., age, BMI, hypertension, smoking, and glucose levels) and the occurrence of strokes, using machine learning models for analysis and prediction.

## Project Overview

- **Objective**: Investigate the impact of clinical and behavioral factors on stroke risk and identify patterns to support healthcare decision-making.
- **Data Source**: [BRFSS Health Survey Dataset](https://www.kaggle.com/datasets/prosperchuks/health-dataset).
- **Key Models**: Logistic Regression, CatBoost, Random Forest, K-Nearest Neighbors.
- **Results**: The Random Forest model demonstrated the highest accuracy (99%) and performance in predicting stroke risk.

## Files in the Repository

- `stroke-risk-analysis.ipynb`: Jupyter Notebook with the full data analysis and machine learning workflows.
- `stroke-risk-analysis-presentation.pdf`: A PDF presentation summarizing the project methodology, results, and key insights.

## Methodology

1. **Data Preprocessing**: Null value handling, outlier detection, and winsorization for a clean dataset.
2. **Exploratory Data Analysis**: Visualization and statistical tests to understand variable distributions and correlations.
3. **Machine Learning**: Evaluation of four classifiers:
   - Logistic Regression
   - CatBoost
   - Random Forest
   - K-Nearest Neighbors
4. **Model Evaluation**: Confusion matrices, ROC curves, and cross-validation metrics for performance assessment.

## Key Findings

- **Correlation**: Strong associations found between stroke and factors like hypertension, heart disease, and glucose levels.
- **Best Model**: Random Forest outperformed other models with an AUC of 1.0, indicating exceptional discriminatory power.

## Limitations

- Dataset merging was limited due to the lack of unique columns.
- Age inconsistencies in the dataset required additional preprocessing.

## Authors

- Keerthika Sunchu  
- Bhavana Bethi  
- Pallavi Telu  
- Srija Dammannagari  
- Yazna Penmesta  

## Contact

For questions or suggestions, please contact:  
Keerthika Sunchu - [ksunchu@iu.edu](mailto:ksunchu@iu.edu)
