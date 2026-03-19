# Telecom Churn Analysis using Apache Spark (PySpark)

This project analyzes customer churn in a telecommunications dataset using Apache Spark (PySpark). The goal is to identify patterns in customer behavior and understand the factors that lead to churn.

## Overview

The dataset includes customer demographics, contract types, services, and billing information. The analysis focuses on:

* Identifying churn patterns using Spark SQL
* Exploring how contract type and services affect churn
* Building a machine learning model to predict customer charges

## Technologies

* Python
* Apache Spark (PySpark)
* Spark SQL
* Spark ML
* Google Colab

## Data Processing

Missing values were handled as follows:

* Rows with missing target values (CHURN) were removed
* Missing numerical values were replaced with column averages

## Key Insights

* Customers with **month-to-month contracts** have significantly higher churn rates
* Churn decreases as the number of subscribed services increases
* Certain countries show consistently higher churn levels

## Machine Learning Model

A Decision Tree Regression model was used to predict monthly charges.

* RMSE: 7.88
* R²: 0.49

The model provides reasonable estimates but requires further tuning for higher accuracy.

## Files

* telecom_churn_analysis.ipynb – main analysis notebook
* telecom_churn_analysis_report.pdf – full report

## How to Run

Open the notebook in Google Colab and run all cells to reproduce the analysis.

## Authors

* Konstantinos Michaelides
* Pantelis Tasopoulos
