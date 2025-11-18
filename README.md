Video Game Sales Analysis - Mini Project 🎮

Author: Abhishek Mishra
Portfolio: ShadowWasHere

1. Objective

The primary goal of this project is to analyze historical video game sales data to identify the key drivers of commercial success. Specifically, this analysis aims to:

Identify Trends: Determine which genres and platforms generate the highest revenue.

Assess Quality Impact: Investigate if higher Critic Scores actually lead to higher Global Sales.

Predict Success: Build a Machine Learning model (Linear Regression) to predict sales based on review scores.

2. Data Source

Dataset: Video Game Sales with Ratings

Source: Kaggle

Overview: ~16,700 rows containing sales data (NA, EU, JP, Global), review scores (Critic/User), and metadata (Genre, Platform, Year).

3. Methodology & Tech Stack

Tech Stack: Python, Pandas, Seaborn, Matplotlib, Scikit-Learn, Scipy.

Key Steps:

Cleaning: Removed games with missing names/years and converted 'tbd' scores to NaN.

EDA: Visualized the "Hit-Driven" nature of the industry (Action & Sports are dominant).

Hypothesis Testing: Performed a T-Test which proved ($p < 0.05$) that games with high critic scores (80+) earn significantly more revenue than average games.

Modeling: Trained a Linear Regression model to predict sales from scores.

4. Key Insights

The "Hit" Economy: The industry is defined by outliers. Most games earn very little, while a few "blockbusters" drive the bulk of the revenue.

Genre Matters: Action and Sports are the safest investment categories.

Quality Pays: There is a statistically significant correlation between high review scores and financial success.

Regional Dominance: Success in North America is the strongest predictor of Global Success (Correlation: 0.94).

This project was conducted as part of a Data Analytics Mini Project.