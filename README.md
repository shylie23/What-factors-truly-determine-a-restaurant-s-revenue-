# ACC102

## Introduction
This project analyzes the Restaurant Revenue Prediction Dataset from Kaggle to identify what factors truly determine a restaurant's revenue. Target users are restaurant entrepreneurs and investors. Many open restaurants based on intuition and fail. This analysis helps them make data-driven decisions on pricing, location, cuisine, and seating capacity before investing capital.

## Files
1. notebook
2. csv file

## Outcomes
1. Average Meal Price (0.69) and Seating Capacity (0.68) are the strongest predictors of high revenue.
2. Customer rating has almost no correlation with revenue (0.01) — good ratings do not guarantee high revenue.
3. Japanese cuisine has the highest high-revenue ratio (85%), followed by French (75%). Mexican (9%) and Indian (26%) have very low success rates.
4. Downtown locations achieve 83% high-revenue ratio; Rural only 16% — very high risk.
5. Random Forest model achieved 97.7% accuracy and 0.977 F1-Score. Top 5 drivers: Average Meal Price, Seating Capacity, Location_Rural (negative), Cuisine_Mexican (negative), Cuisine_Japanese (positive).

## How to run
Step1: open notebook
Step2: click run all and get the result
