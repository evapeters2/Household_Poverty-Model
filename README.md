# Household Poverty Classification

## Project Overview
Model to classify households into four poverty levels using observable attributes rather than income. Focused on data cleaning, exploratory analysis, and multinomial logistic regression with backward selection.

## Key Steps
- **Data Cleaning:** Filtered household heads, handled missing values, created categorical variables, dropped redundant columns.
 
- **Exploratory Analysis:** Visualized household attributes vs. poverty levels (schooling, assets, composition).

- **Modeling:** Multinomial logistic regression with backward selection; evaluated with accuracy, sensitivity, specificity, weighted kappa.

## Tools & Technologies
R (tidyverse, dplyr, ggplot2, nnet, caret), R Markdown → HTML report

## View Report
Full HTML report with visualizations and results is available online:  
https://evapeters2.github.io/Household_Poverty-Model/Project2.html

## Repository Structure
- `poverty.csv` — Raw dataset  
- `analysis.R` — Cleaning & modeling script  
- `analysis.Rmd` — R Markdown report  
- `final_predictions.csv` — Test set predictions
