# Week 4 - Predictive Modeling and Performance Evaluation

## Project Overview

This project develops machine learning models to predict whether
an online shopping session will result in a purchase.

## Business Problem

The objective is to predict the Revenue outcome using visitor,
browsing, traffic, and session-level behavioral features.

## Dataset

Online Shoppers Purchasing Intention Dataset.

## Dataset Size

12,330 records and 18 original variables.

## Target Variable

Revenue

- 0 = No Purchase
- 1 = Purchase

## Data Cleaning

- Checked missing values
- Removed duplicate records
- Converted Boolean variables
- Validated data types

## Feature Engineering

- TotalPages
- TotalDuration
- AvgTimePerPage
- IsReturningVisitor
- EngagementScore

## Models

1. Dummy Classifier
2. Logistic Regression
3. Random Forest

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- PR-AUC

## Tools

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Excel

## Project Structure

```text
data/
outputs/
week4_predictive_model.py
requirements.txt
README.md