# CMPT353-World-Cup-Prediction

FIFA World Cup 2026

Project Overview

This project involves analyzing historical FIFA World Cup data from 1930 to 2022. The dataset provides detailed statistics for teams participating in various FIFA World Cup tournaments. The objective is to explore trends, uncover insights, and perform statistical analyses related to team performance, player usage, and match dynamics over time.

Required Library:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy
- jupyter
- soccerdata
- geopandas



Notebooks Overview
1. generate_data.ipynb

Description: This notebook is used for gathering and cleaning raw data related to World Cup tournaments.

Output: A cleaned data file (e.g., FIFA_World_Cup.csv).

2. tidy_data.ipynb

Description: Processes and transforms raw data into a more manageable format suitable for analysis.

Output: A tidy data file that will be used in subsequent notebooks (i.e., FIFA_World_Cup_Tidy.csv).

3. generate_features.ipynb

Description: Select features from the cleaned data that are relevant for predictive modeling.

Output: Selected features for target

4. model_prediction.ipynb

Description: Implements a machine learning model (i.e., decision tree, random forest, and neural network) to predict future World Cup winners.

Output: Model predictions

5. World_cup_winner.ipynb

Description: Provides exploratory data analysis (EDA) and visualizations for understanding past World Cup winners and patterns.

Output: Predictions insights into World Cup results.

6. generate_plots.ipynb

Description: Generates visual plots that help in analyzing trends and outcomes, such as goals scored, player performance, and team comparisons.

Output: Informative graphs about statistical performance in the World Cup



Produced/Expected:
- world_cup_cleaned.csv: Initial cleaned data.
- world_cup_tidy.csv: Tidy data set for analysis.
- Significant Features used for the model
- Model selection
- Winner Prediction
- Statistical graphs
