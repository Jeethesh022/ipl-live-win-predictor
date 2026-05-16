# IPL Live Win Predictor 🏏🔥

A Machine Learning project that predicts live IPL match winning probability using historical ball-by-ball IPL data.

## 📌 Project Overview

This project uses:
- Data Science
- Machine Learning
- IPL historical datasets

to predict the winning probability of a team during a live IPL match.

The model analyzes the current match situation such as:
- Runs left
- Balls left
- Wickets left
- Current Run Rate (CRR)
- Required Run Rate (RRR)

and predicts the probability of winning or losing.

---

## 🚀 Features

✅ Live match win probability prediction  
✅ Ball-by-ball IPL data analysis  
✅ Feature engineering  
✅ Random Forest Machine Learning model  
✅ Real-time style cricket analytics  
✅ Cricbuzz/ESPN style prediction logic

---

## 🗂 Dataset Used

Datasets:
- matches.csv
- deliveries.csv

The datasets contain:
- Match results
- Ball-by-ball delivery data
- Runs scored
- Wickets
- Teams
- Match winners

---

## 🧠 Machine Learning Model

Model Used:
- Random Forest Classifier

Why Random Forest?
- Good accuracy
- Beginner friendly
- Handles complex patterns
- Works well on structured cricket data

---

## 📊 Features Used

| Feature | Description |
|---|---|
| runs_left | Remaining runs to win |
| balls_left | Remaining balls |
| wickets_left | Remaining wickets |
| crr | Current Run Rate |
| rrr | Required Run Rate |

---

## 🧮 Important Formulas

### Balls Left

:contentReference[oaicite:0]{index=0}

### Current Run Rate

:contentReference[oaicite:1]{index=1}

### Required Run Rate

:contentReference[oaicite:2]{index=2}

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Google Colab
- GitHub

---

## 📈 Model Output

Example Prediction:

Input:
- Runs Left = 30
- Balls Left = 18
- Wickets Left = 7
- CRR = 9
- RRR = 10

Output:
- Winning Probability = 72%
- Losing Probability = 28%

---

## 🎯 Project Goal

To build a real-world cricket analytics system that predicts live IPL match outcomes using machine learning and historical match patterns.

---
## Datasets
Download the IPL dataset from Kaggle and place the CSV files inside the data/ folder.

## 📌 Future Improvements

- Streamlit Web App
- Better ML models (XGBoost)
- Live API integration
- Team-wise analysis
- Venue-based predictions
- Player impact analysis

---

## 📷 Sample Workflow

1. Load IPL datasets
2. Clean and preprocess data
3. Create match-state features
4. Train ML model
5. Predict live match probabilities

---

## 👨‍💻 Author

Developed by JEETHESH D  
CSE Student | 
