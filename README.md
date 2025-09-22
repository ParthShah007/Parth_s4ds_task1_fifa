# Parth_s4ds_task1_fifa
This project explores the FIFA player dataset to uncover insights about player attributes, clubs, and nationalities.
We perform exploratory data analysis (EDA), create custom metrics (GOATScore), and build machine learning models to predict player ratings.

The notebook covers:
Data cleaning & preprocessing
Exploratory plots (distributions, comparisons, correlations, timelines)
Feature engineering (AttackingScore, FitnessScore, KeeperScore, TacklingScore, GOATScore)
Predictive modeling (Linear Regression, Random Forest, XGBoost)

Evaluation & interpretation of results

Final Model: XGBoost
R²: 0.987
MAE: 0.60 (average error < 1 rating point)
RMSE: 0.79 (no large errors)
Chosen for its ability to capture complex interactions between skills while remaining interpretable.

Results & Insights:
Reactions, Potential, BallControl, Age were most important in predicting ratings.
Market stats (Value, Wage) dominate if included, but removing them gives true skill-based insights.
Messi, Ronaldo, Neymar comparisons show distinct strengths (dribbling, finishing, stamina).
GOATScore ranking provides an alternative, skill-based measure of greatness.
