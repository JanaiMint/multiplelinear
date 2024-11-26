# multiplelinear
I developed a Python script that uses multiple linear regression to analyze how my country India's plastic trade and waste patterns are influenced by our population growth and trade values, combining historical Excel data to create statistical models and visual representations of these relationships.
# Multiple Linear Regression Analysis - India's Plastic Trade

## Overview
This script performs a multiple linear regression analysis to examine the relationships between India's plastic trade/waste patterns and two key economic indicators: population growth rate and net trade values. The analysis uses data from Excel files containing historical data on plastic weight, population changes, and trade statistics.

## Features
- Data integration from multiple Excel sources via Google Drive
- Missing value handling through interpolation
- Multiple linear regression using statsmodels
- Visualization using seaborn pairplots with custom formatting
- Statistical analysis including regression coefficients, R-squared values, and p-values

## Dependencies
- pandas
- statsmodels
- seaborn
- matplotlib
- google.colab (if running in Google Colab)

## Outputs
- Statistical summary of regression analysis
- Multilinear correlation plots showing relationships between:
  - Population Growth (% change) vs Plastic Weight (kg)
  - Net Trade (USD) vs Plastic Weight (kg)

## Purpose
The analysis aims to quantify the impact of population dynamics and trade patterns on India's plastic trade/waste, providing insights for policy and environmental planning.
