# Healthcare Data Analysis & Risk Prediction Dashboard

## Project Overview
This project focuses on analyzing healthcare data to identify key factors influencing disease risk. 
The objective is to perform exploratory data analysis, build a predictive model, and present insights 
through visualizations to support data-driven decision-making.

## Dataset
- The dataset contains patient health indicators and symptoms.
- Data was cleaned and preprocessed before analysis.
- Missing values and inconsistencies were handled appropriately.

## Exploratory Data Analysis (EDA)
### Correlation Heatmap
![Correlation Heatmap](images/correlation_heatmap.png)

**Insight:**  
The heatmap highlights relationships between various features and the target variable, helping identify 
important risk indicators.

### Target Variable Distribution
![Target Distribution](images/target_distribution.png)

## Modeling Approach
- Algorithm Used: Support Vector Machine (SVM)
- Data split into training and testing sets
- Model achieved approximately **86% accuracy**
- The model is used as a decision-support tool, not a diagnostic system

## Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## Key Insights & Recommendations
- Certain features show strong correlation with disease occurrence
- Visualization helped identify high-risk patterns
- Such insights can support early screening and resource prioritization
- Improve feature engineering
- Explore additional models for comparison
