# 🏏 IPL Win Predictor 🎯
📌 Project Overview
This project is an interactive web application built using Streamlit that allows users to:

Select batting and bowling teams

Input match details like city, score, overs, and wickets

Predict the winning probability of the batting team using a trained machine learning pipeline

The model uses real-time match inputs and returns a probability distribution for each team winning the match.

------


🚀 Features
Dropdowns for team and city selection

Dynamic input for match progress (score, overs, wickets)

Backend ML model built using match statistics

Intuitive UI using Streamlit

Real-time winning probability predictions

------

🔧 Tech Stack

| Layer          | Tools/Technologies                                   |
| -------------- | ---------------------------------------------------- |
| **Frontend**   | Streamlit (Python-based Web UI)                      |
| **Backend**    | Python, Pandas, Scikit-learn                         |
| **ML Model**   | Logistic Regression / Pipeline (Saved as `pipe.pkl`) |
| **Deployment** | Localhost via Streamlit                              |

-----

📂 Project Structure
IPL_Win_Predictor/
│
├── app.py                  # Main Streamlit app
├── pipe.pkl                # Pre-trained ML pipeline
├── model_building.ipynb    # Notebook for model training
├── requirements.txt        # Project dependencies
└── README.md               # Project description

