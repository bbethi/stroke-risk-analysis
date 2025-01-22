# Assessing the Risk Factors Associated with Stroke

This repository contains materials for the project **"Assessing the Risk Factors Associated with Stroke"**. The project investigates the relationships between various risk factors (e.g., age, BMI, hypertension, smoking, and glucose levels) and stroke occurrence. By employing data analysis and machine learning, we aim to provide insights that can aid healthcare decision-making and policy formulation.

## Project Overview

- **Objective**: Investigate the impact of clinical and behavioral factors on stroke risk and identify patterns for healthcare interventions.
- **Data Source**: [BRFSS Health Survey Dataset](https://www.kaggle.com/datasets/prosperchuks/health-dataset).
- **Key Models**: Logistic Regression, CatBoost, Random Forest, K-Nearest Neighbors.
- **Results**: The Random Forest model achieved the highest accuracy (99%) and AUC (1.0), showcasing its exceptional predictive capability.

## Files in the Repository

- `stroke-risk-analysis.ipynb`: Jupyter Notebook containing the full data analysis, statistical tests, and machine learning workflows.
- `stroke-risk-analysis-presentation.pdf`: A presentation summarizing the project methodology, results, and key insights.
- `stroke-risk-analysis-report.pdf`: The detailed project report outlining the methodology, data analysis, statistical results, and model performance.

## Methodology

1. **Data Preprocessing**:
   - Handling null values and outliers.
   - Transforming categorical and numerical data.
   - Winsorization for outlier adjustment.

2. **Descriptive Statistics**:
   - Analyzed distributions of age, BMI, smoking status, and gender.
   - Computed summary statistics for risk factors.

3. **Exploratory Data Analysis**:
   - Visualized relationships between independent variables and stroke.
   - Created correlation matrices for deeper insights.

4. **Statistical Analysis**:
   - Performed Chi-Square tests to evaluate the association between risk factors and stroke.
   - Verified statistical significance of key variables.

5. **Machine Learning Models**:
   - Trained and evaluated classification models:
     - Logistic Regression
     - CatBoost
     - K-Nearest Neighbors
     - Random Forest
   - Assessed model performance using confusion matrices, ROC curves, and cross-validation.

## Key Findings

- Strong correlations were found between stroke and factors like hypertension, heart disease, and glucose levels.
- The Random Forest model outperformed other models, achieving 99% accuracy and an AUC of 1.0, indicating outstanding predictive performance.

## Contributors

- Bhavana Bethi  
- Keerthika Sunchu  
- Pallavi Telu  
- Srija Dammanagari  
- Yazna Penmetsa  

## Contact

For questions or suggestions, please contact:  
Pallavi Telu - [ptelu@iu.edu](mailto:ptelu@iu.edu)
