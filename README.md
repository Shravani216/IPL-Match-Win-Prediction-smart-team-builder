# IPL-Match-Win-Prediction-smart-team-builder
An end-to-end analytics and machine learning project built on IPL ball-by-ball data from 2008 to 2025. It predicts a team's win probability during a match and turns player performance data into team-selection insights, all through an interactive Gradio application.

Features
Data pipeline: cleans and aggregates ball-by-ball data using SQL-style aggregations and Python (Pandas, NumPy).
Feature engineering: derives match-state features such as current run rate, required run rate, runs remaining, balls remaining, wickets remaining and innings phase.
Model benchmarking: compares Random Forest, XGBoost and LightGBM, and selects the best performer by accuracy and AUC.
Win probability prediction: takes live match inputs and returns the chasing team's chance of winning.
Smart Team Builder: translates player performance data into team-selection insights.
Interactive UI: a Gradio app that connects user inputs to the backend prediction logic.
