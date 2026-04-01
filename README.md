# Premier League Match Outcome Predictor

A simple machine learning project predicting **Home Win, Away Win, or Draw** in Premier League matches.

This project follows a 5-day machine learning mini-course by [Mar Antaya](https://www.instagram.com/mar_antaya/) and demonstrates a basic ML workflow: from loading data to training and evaluating a model.

## What this project shows

- loading and inspecting a dataset with pandas
- basic exploratory data analysis (EDA)
- feature engineering using rolling averages
- training a classification model
- evaluating predictions with ML metrics

## Model

Logistic Regression using **scikit-learn**.

## Features used

- Home team
- Away team
- Average goals scored (last 5 matches)
- Average goals conceded (last 5 matches)

## Evaluation

The model is evaluated using:

- Accuracy
- Classification report (precision, recall, F1-score)
- Confusion matrix

## Requirements

- Python
- pandas
- scikit-learn
- matplotlib
- seaborn

Install dependencies:

```bash
pip install -r requirements.txt
```

## How to run

```bash
python3 premier_league_match_predictor.py
```

## Project structure

- `premier_league_match_predictor.py` - loads the dataset, performs basic EDA, engineers rolling-average features, trains a logistic regression model, and prints evaluation metrics
- `premier-league-matches.csv` - included dataset used by the script
- `requirements.txt` - Python dependencies for the project
- `README.md` - project overview and setup instructions

## Dataset

This repository includes `premier-league-matches.csv`, so no separate download is required to run the project.

Source dataset: [Premier League Matches 1993-2023](https://www.kaggle.com/datasets/evangower/premier-league-matches-19922022)

License: CC0: Public Domain

## Purpose
This is an educational project demonstrating the basic machine learning workflow for a classification problem.
