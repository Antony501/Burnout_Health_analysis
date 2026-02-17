# Burnout_Health_analysis
Machine learning project predicting burnout risk in healthcare workers.
# Burnout Prediction in Healthcare Workers

## Overview

Burnout syndrome is a growing problem among healthcare professionals, affecting job performance, mental health, and patient safety.

This project aims to:
- Analyze key predictors of burnout
- Build a machine learning model to predict high burnout risk
- Interpret model outputs from a clinical and occupational health perspective

The project combines statistical analysis with machine learning to bridge clinical research and applied data science.


##  Dataset

Source: Public occupational health dataset (simulated / Kaggle dataset)

Variables include:
- Age
- Gender
- Weekly working hours
- Years of experience
- Job satisfaction score
- Work-life balance score
- Emotional exhaustion
- Personal accomplishment score


Target variable:
- High Burnout Risk (0 = No, 1 = Yes)


## Technologies Used

- Python
- Pandas
- Scikit-learn
- Stats models

##  Methodology

###  Data Cleaning
- Missing value handling
- Outlier inspection
- Feature encoding (categorical variables)

###  Exploratory Data Analysis (EDA)
- Correlation matrix
- Distribution plots
- Group comparisons
- Burnout prevalence analysis

###  Statistical Modeling
- Logistic regression
- Odds ratio interpretation
- Multicollinearity testing (VIF)

###  Machine Learning Modeling
- Train/Test split (80/20)
- Random Forest classifier
- Cross-validation
- ROC curve analysis

##  Results

Logistic Regression:
- Significant predictors: Emotional exhaustion, Work-life balance, Weekly working hours
- Odds Ratio interpretation showed strong association between emotional exhaustion and burnout risk.

Random Forest:
- Accuracy: 0.84
- ROC-AUC: 0.89

Feature Importance:
1. Emotional exhaustion
2. Work-life balance
3. Job satisfaction
4. Weekly working hours

##  Clinical Interpretation

Emotional exhaustion appears as the strongest predictor of burnout risk, confirming theoretical burnout models.

Reduced work-life balance significantly increases predicted burnout probability.

The model demonstrates potential application in occupational screening and preventive workplace interventions.

##  Future Improvements

- External validation on independent dataset
- Implementation into Streamlit web application
- Inclusion of longitudinal data
- Testing additional models (XGBoost, Gradient Boosting)

##  Author

Antonija Hrkać  
Health Data Analyst | Biostatistician | PhD in Health Sciences  
Focused on clinical research, occupational health, and applied machine learning.

---

##  Repository Structure

burnout-analysis/
│
├── data/
├── notebooks/
├── src/
├── figures/
└── README.md
