# Telco-Customer-Churn-Analysis

## Overview
This project analyses customer churn patterns for a telecommunications company, with the goal of identifying high-risk customer segments and supporting data-driven retention strategies under limited operational budgets.

## Business Questions
- What is the overall customer churn rate?
- Which customer groups exhibit higher churn risk?
- If retention resources are limited, which customers should be prioritised and why?

## Dataset
- Source: Public Telco Customer Churn dataset (Kaggle)
- Size: 7,032 customer records, 21 variables
- Grain: One row per customer
- Target variable: Churn (Yes / No)

## Approach
1. Data cleaning and validation (data types, consistency, missing values)
2. Business-driven feature engineering (tenure lifecycle, pricing segments, payment method, service bundling)
3. Exploratory data analysis and churn segmentation
4. High-risk segment identification using rule-based analysis
5. Interpretable baseline modelling (logistic regression) for risk ranking

## Key Insights
- Early-tenure customers and those without automatic payment methods show significantly higher churn rates.
- High monthly charges combined with payment friction represent a major source of churn risk.
- Customers with fewer bundled services have lower switching costs and higher churn propensity.

## Outcomes
- Identified three priority churn segments with churn lift up to 2.2× the overall average.
- Proposed actionable retention strategies focusing on payment friction reduction, service bundling, and lifecycle-based interventions.

## Tools
- SQL (MySQL)
- R (tidyverse, ggplot2, tidymodels)

## Next Steps
- Threshold optimisation and alternative models for improved churner recall
- Integration of retention cost and revenue impact for prioritisation
