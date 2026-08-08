# predicting-future-dementia-conversion
Predicting Future Dementia Conversion from Baseline Clinical and MRI-Derived Biomarkers Using Interpretable Machine Learning
# Predicting Future Dementia Conversion

## Overview

This independent computational neuroscience project investigates whether baseline demographic characteristics, cognitive assessments, and MRI-derived biomarkers can predict future dementia conversion using the OASIS-2 longitudinal MRI dataset.

## Research Question

Can baseline demographic, cognitive, and MRI-derived biomarkers predict future dementia conversion?

## Dataset

- OASIS-2 Longitudinal MRI Dataset
- 86 baseline participants
- 72 stable participants
- 14 future converters

## Methods

- Data preprocessing
- Welch's t-tests
- Cohen's d
- Pearson correlation analysis
- Logistic Regression
- Random Forest
- Repeated stratified 5-fold cross-validation

## Results

- Logistic Regression outperformed Random Forest.
- Mean ROC-AUC: 0.556
- CDR demonstrated the strongest association with future dementia conversion.
- Individual baseline variables were not statistically significant predictors.

## Repository Contents

- Research manuscript (PDF)
- Google Colab notebook
- Figures
- Supporting analyses

## Technologies

- Python
- pandas
- NumPy
- SciPy
- scikit-learn
- Matplotlib
- Google Colab
