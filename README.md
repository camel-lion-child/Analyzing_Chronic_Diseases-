Social Inequalities in Chronic Diseases in France
How social class impacts chronic disease inequalities (France)

**Overview

This project analyzes how social class influences chronic disease prevalence in France, using official raw data from: https://data.drees.solidarites-sante.gouv.fr

The goal is to build a complete data pipeline (ETL → SQL → ML) showing the link between socioeconomic status and health inequalities.

**Technologies

Python (Pandas, NumPy, Matplotlib, Seaborn)

SQL (cleaning, transformations, aggregations)

Machine Learning (Logistic Regression, Random Forest)

Jupyter Notebook

*ETL Pipeline

Extract raw DREES files (CSV/Excel)

Clean: missing values, harmonize labels, normalize social categories

Transform: create age groups, income classes, PCS categories

Load cleaned dataset for SQL and ML analysis

*SQL Analysis

SQL scripts handle:

Table normalization and cleaning

Joins between demographic and health datasets

Aggregation by social class, age, gender, region

Inequality metrics (ratio low-income vs high-income prevalence)

Ranking most vulnerable groups

**Simulates real Data Engineering transformations on population-level data.

*Machine Learning

A simple, interpretable ML model predicts chronic-disease risk based on social determinants:

Social class (PCS)

Income level

Education

Age category

Region

Models included:

Logistic Regression

Random Forest

Metrics: Accuracy, F1, ROC-AUC, Feature Importance.

Shows how social determinants influence health outcomes.
