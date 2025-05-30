# 🏏 IPL Win Predictor – Real-Time Match Outcome Estimator using Machine Learning

A smart and interactive machine learning-based web application that predicts the probability of a team winning an IPL match based on current match conditions. Built using Python and Streamlit, this project is designed for cricket enthusiasts, data science learners, and developers interested in real-time predictive analytics.

---

## 📌 Project Overview

This project provides an intuitive user interface to input live match stats such as the batting team, bowling team, score, overs, wickets, and venue. It returns the predicted probability of the batting team winning the match using a trained ML pipeline based on historical IPL data.

---

## 🚀 Features

- 🧠 ML-powered predictions based on real-time match input
- 🖥️ Interactive web interface using Streamlit
- 🔮 Probability output for win prediction
- ✅ Lightweight and runs locally
- 📊 Easy to extend and retrain with more features

---

## 🧰 Tech Stack

| Component     | Technology        |
|---------------|-------------------|
| Web Framework | Streamlit         |
| Programming   | Python             |
| ML Libraries  | Pandas, Scikit-learn |
| Model Format  | Pickle (`pipe.pkl`) |
| Deployment    | Localhost via Streamlit |

---

## 📁 Project Structure

IPL_Win_Predictor/
├── app.py # Main Streamlit web application
├── pipe.pkl # Trained machine learning pipeline
├── model_building.ipynb # Jupyter notebook for model training
├── requirements.txt # Python dependencies
└── README.md # Project documentation (this file)

---

## 📈 ML Model Overview

- **Type**: Classification (Win / Lose)
- **Algorithm**: Logistic Regression (via Scikit-learn Pipeline)
- **Features Used**:
  - Batting Team
  - Bowling Team
  - City
  - Runs Left
  - Balls Left
  - Wickets Remaining
  - Current Run Rate (CRR)
  - Required Run Rate (RRR)

- **Output**: Probability score for win/loss prediction

---


📊 Dataset -->  https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020?select=matches.csv

---

🙋‍♂️ Author

Harshal Patil

Aspiring Data Scientist | Cricket Lover | Machine Learning Enthusiast

---

📸 Preview

project link -->  https://iplwinprediction-jld6ywdqdddjav2vyibqt2.streamlit.app/

![Screenshot 2025-05-30 135451](https://github.com/user-attachments/assets/639feb11-7d83-4f39-b2b4-b1d0e44bb364)

