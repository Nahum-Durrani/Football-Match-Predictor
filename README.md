# ⚽ Football Match Predictor

An AI-powered match prediction system built using Python, Pandas, and Scikit-learn to forecast the outcomes of Premier League football matches based on historical performance metrics and rolling averages.

## 📊 Features

- 🧠 Predicts match outcomes using a Random Forest Classifier
- 🔁 Computes rolling averages for stats like goals, shots, distance, etc.
- 📅 Automatically filters training and testing data based on match dates
- 🧪 Calculates precision and accuracy for model evaluation
- 🔀 Merges team-vs-opponent predictions for match-level insights

## 🧠 How It Works

The script loads Premier League match data from `matches.csv`, extracts key features like opponent, match time, and venue, and computes 3-game rolling averages for core stats. It trains a RandomForestClassifier on matches before 2022, predicts outcomes for later matches, and merges the predictions so that both teams' outcomes can be compared for each match. The result includes model precision and a sample merged output.

## 🛠️ Tech Stack

- Python
- Pandas
- Scikit-learn


