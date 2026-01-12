# Anomaly Detection in Global Burden of Disease Data

## Overview
This project explores country-level mortality patterns using data from the
Institute for Health Metrics and Evaluation (IHME) Global Burden of Disease (GBD)
study. Statistical and machine learning–based anomaly detection methods are applied
to identify countries with atypical cause-of-death profiles.

The analysis emphasizes careful interpretation of anomalies in a public health
context and demonstrates how multivariate methods can reveal patterns not visible
through univariate analysis alone.

## Data Source and Licensing
Source: Institute for Health Metrics and Evaluation (IHME). Used with permission.
All rights reserved.

This analysis uses Global Burden of Disease (GBD) 2023 estimates, released in
2025. The underlying data are not included in this repository due to licensing
restrictions.

All visualizations and results shown are derived outputs shared for non-commercial,
educational, and portfolio purposes in accordance with IHME’s Free-of-Charge
Non-Commercial User Agreement.

## Methods
- Exploratory Data Analysis (EDA)
- Interquartile Range (IQR)–based outlier detection
- Isolation Forest
- One-Class Support Vector Machine
- Principal Component Analysis (PCA)

## Tools
- Python
- pandas, numpy
- scikit-learn
- Plotly

## Repository Contents
- `Anomaly_detection_GBD.ipynb`: Main analysis notebook
