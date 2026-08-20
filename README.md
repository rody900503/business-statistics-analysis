# Business Statistics Analysis

This project presents two applied statistical analyses using R, covering public-health and retail business datasets. It demonstrates how statistical modelling can be used to identify relationships within real-world data and translate quantitative results into interpretable insights.

The project focuses on:

1. Cardiovascular Disease (CVD) prevalence across local authority regions in England
2. Customer satisfaction across furniture retail stores

## Project Objectives

### 1. Cardiovascular Disease Analysis

This analysis investigates the regional factors associated with Cardiovascular Disease (CVD) prevalence, focusing on:

- Overweight prevalence
- Smoking prevalence
- Poverty
- Wellbeing

Multiple linear regression is used to evaluate these factors simultaneously, alongside correlation analysis, data visualisation, and regression diagnostics.

### 2. Customer Satisfaction Analysis

This analysis examines the operational and socio-economic factors associated with customer satisfaction across furniture retail stores, including:

- Delivery time
- Staff satisfaction
- New product range status
- Socio-economic status (SES)

An interaction regression model is also used to investigate whether the relationship between delivery time and customer satisfaction varies across SES groups.

## Key Findings

### Cardiovascular Disease

- Overweight prevalence and smoking prevalence were significantly positively associated with CVD prevalence.
- Poverty was significantly negatively associated with CVD prevalence.
- Wellbeing was significantly positively associated with CVD prevalence after controlling for the other predictors.
- The multiple regression model explained approximately 24.9% of the variation in CVD prevalence.
- The results represent statistical associations and should not be interpreted as causal relationships.

### Customer Satisfaction

- Longer delivery times were significantly associated with lower customer satisfaction.
- Higher staff satisfaction was significantly associated with higher customer satisfaction.
- New product range status was not a statistically significant predictor of customer satisfaction.
- The relationship between delivery time and customer satisfaction differed across SES groups, with the negative association significantly weaker in Low SES stores than in High SES stores.
- The main-effects regression model explained approximately 44.7% of the variation in customer satisfaction.

## Methods Used

- Data quality and missing-value assessment
- Descriptive statistics
- Exploratory data analysis
- Correlation analysis
- Data visualisation
- Multiple linear regression
- Regression diagnostics
- Interaction analysis
- Statistical and business interpretation

## Tools and Packages

The analysis was completed using R and R Markdown, primarily with:

- `tidyverse`
- `ggplot2`
- `gridExtra`
- `knitr`

## Repository Files

- `Individual-Assignment-5536640.Rmd` — R Markdown source containing the analysis and code
- `Individual-Assignment-5536640.html` — rendered report containing the complete results, tables, and visualisations

## Data

The original datasets are not included in this public repository.

The analysis references:

- `Cardio_Vascular_Disease.csv`
- `cust_satisfaction.csv`

These datasets were provided for the original academic assessment.

## Skills Demonstrated

This project demonstrates practical experience in:

- Statistical analysis using R
- Data cleaning and quality assessment
- Exploratory data analysis
- Multiple regression modelling
- Interaction modelling
- Regression diagnostics
- Data visualisation
- Translating statistical results into business insights
- Communicating analytical findings
- Reproducible analysis with R Markdown

## Academic Context

This project was originally developed as part of an MSc Business Statistics assessment at the University of Warwick and has been refined for portfolio presentation.

The repository demonstrates the application of statistical methods and R programming to public-health and business decision-making problems.