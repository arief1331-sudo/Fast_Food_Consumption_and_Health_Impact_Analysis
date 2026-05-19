# Fast Food Consumption and Health Impact Analysis

## Overview
This project (Milestone 2) explores the relationship between fast food consumption behavior and physical health indicators. It analyzes how eating habits, physical activity, and demographic factors (such as age groups and gender) affect BMI, digestive health, and overall health scores.

## Dashboard
An interactive visualization of this analysis is available on Tableau: 
[View Tableau Dashboard](https://public.tableau.com/app/profile/arief.bagus.nugraha/viz/P1M2_17678122289280/Full?publish=yes)

## Dataset
The data is sourced from Kaggle: `prince7489/fast-food-consumption-and-health-impact-dataset`.

## Problem Statement
The analysis answers the following key questions (5W+1H method):
- **Who**: Which gender has the highest average fast-food consumption?
- **What**: Is there a statistically significant difference (T-Test) in the Overall Health Score between frequent and infrequent fast-food consumers?
- **Where**: How does fast-food consumption vary across different generation groups (Gen Z, Millennials, etc.)?
- **When**: How often do the majority of respondents consume fast food weekly?
- **Why**: What is the proportion of respondents experiencing digestive issues due to their diet?
- **How**: How does the level of physical activity mitigate the impact of frequent fast-food consumption on maintaining a normal BMI?

## Tech Stack
- **Python**: Data manipulation and statistical testing (`pandas`, `scipy`).
- **Data Visualization**: `matplotlib`, `seaborn`.
- **Tableau**: Dashboard creation.

## Key Steps
1. **Data Loading & Cleaning**: Handled missing values, checked for duplicates, and engineered new categorical features (Age Group, Activity Level, Diet Category).
2. **Descriptive Analysis**: Explored data distribution (e.g., identifying that the average consumption is 6.8 times/week with a mode of 7).
3. **Inferential Statistics**: Conducted T-Tests to evaluate the significance of health score differences between different groups.
4. **Insights Generation**: Derived actionable recommendations, highlighting how physical activity acts as a mitigator for BMI and evaluating digestive health risks.

## Author
Arief Bagus Nugraha 