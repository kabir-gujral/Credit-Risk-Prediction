# German Credit Risk Prediction in R

## Overview
This project focuses on the prediction of credit risk using the German Credit dataset. The dataset contains information about individuals and their respective credit risk. The primary goal is to leverage this data to construct models that can predict the likelihood of credit default, aiding financial institutions in their decision-making processes.

## Dataset Description
The dataset originates from the German Credit dataset and encompasses various attributes related to individual credit applicants. Features include financial histories, savings accounts, employment durations, and other pertinent personal details.

## Key Steps & Methodologies

### Data Preparation:
- Loaded and inspected the dataset.
- Conducted preliminary data cleaning, including handling missing values and outliers.
- Segmented data based on the 'Checking' attribute to create distinct subsets.

### Exploratory Data Analysis (EDA):
- Visualized distributions of individual features.
- Identified key patterns and relationships among variables using correlation matrices and other visualization tools.

### Variable Selection & Binning:
- Selected four relevant predictors for each training set, including a mix of continuous and categorical variables.
- Applied binning to the selected variables to ensure the data was appropriately structured for modeling.

### Hypothesis Testing:
- Employed chi-square tests to validate the significance of categorical variables and guide the model-building process.

### Model Building:
- Developed models using linear regression, logistic regression, and advanced regression techniques.
- Trained models on a designated training set and validated performance on a separate dataset.

### Model Evaluation:
- Assessed model performance using metrics like ROC curves, Gini coefficients, and KS values.

## Tools & Libraries
**R:** The primary programming language for data analysis and modeling.
**Libraries:** ggplot2, dplyr, caret, gmodels, ROCR, scorecard, Information, xlsx

## Key Findings
- Identified crucial predictors of credit default, including historical financial behaviors and employment duration.
- The logistic regression model displayed promising results in terms of prediction accuracy and robustness.
- Highlighted the importance of proper variable selection and preprocessing in enhancing model performance.

## Conclusions
The project successfully demonstrates the application of statistical methodologies and machine learning techniques in predicting credit risk. The developed models can be instrumental for financial institutions in assessing creditworthiness and making informed lending decisions.
