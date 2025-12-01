---
title: "Predicting Survival on the Titanic"
date: 2025-10-15
excerpt: "A machine learning project to predict passenger survival using Python, exploring factors like class, gender, and age."
---

**Tools Used:** Python, Pandas, Scikit-learn, Seaborn, Jupyter Notebook

## Project Overview
This project analyzes the famous Titanic dataset to answer the key question: **"What factors made someone more likely to survive the Titanic sinking?"** I will build a predictive model and aim to achieve >80% accuracy.

## Process & Methodology
1.  **Exploratory Data Analysis (EDA):** Used **Pandas** and **Seaborn** to visualize survival rates by passenger class, gender, and age. Discovered that women, children, and first-class passengers had significantly higher survival chances.
2.  **Data Preprocessing:** Handled missing values in the 'Age' and 'Cabin' columns, created new family-size features, and encoded categorical variables.
3.  **Model Building & Evaluation:** Trained and compared multiple **Scikit-learn** classifiers (Logistic Regression, Random Forest). Tuned the best model using cross-validation.

## Key Insights
- The **"women and children first"** protocol was strongly evidenced in the data.
- **Passenger class** (socio-economic status) was a major factor, with 1st-class passengers having a survival rate over 60%.
- The final **Random Forest model** identified 'Sex', 'Pclass', and 'Fare' as the most important predictors.

## Results & Visualization
![Chart Placeholder](https://via.placeholder.com/600x400/3d5a80/ffffff?text=My+Titanic+Analysis+Chart)
