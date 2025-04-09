# Football Match Outcome Prediction (ML Project)

This project predicts the outcome of football matches (Home Win, Draw, or Away Win) using historical match data and machine learning techniques.

## Project Overview

Using match-level statistics like goals, shots, cards, and fouls from past seasons, a Random Forest Classifier was trained to predict the final match result. Extensive feature engineering was done to compute rolling statistics based on previous seasons, making the dataset more informative and robust.

## Tools & Libraries

- Python  
- Pandas, NumPy – Data manipulation  
- Scikit-learn – Model building  
- Seaborn, Matplotlib – Visualization  
- Google Colab – Environment used for execution

## Key Features

- Seasonal labeling (Aug–May format)
- Rolling averages for key stats (Goals, Shots, Fouls, etc.)
- Rolling wins, draws, and losses per team
- Feature importance visualization
- Confusion matrix heatmap using `sns.heatmap()`
- Final cleaned dataset saved as CSV

## Model

- Model Used: Random Forest Classifier  
- Target Variable: `FTR` (Full-Time Result)  
- Accuracy Achieved: Displayed using `accuracy_score`

## Output

- Visualizations:
  - Top 20 important features
  - Confusion Matrix using seaborn
- Final processed dataset: `my_manipulated_data.csv`

## What I Learned

- How to engineer features from raw sports data
- Use of rolling window techniques across seasonal boundaries
- Training and evaluating classification models
- Importance of preprocessing and domain understanding

## Dataset

- Source: Provided as part of a private test task  
- Format: `.csv` file with match-level statistics
