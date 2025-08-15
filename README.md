#https://multiple-disease-prediction-by-ruchi.streamlit.app/

# Overview
This project is a web-based application built with Streamlit that predicts the likelihood of:

Diabetes

Heart Disease

The system uses pre-trained Machine Learning models to provide quick health risk assessments based on user-input medical parameters.

# 📂 Features
Multiple Predictions in One App: Diabetes and Heart Disease prediction.

Interactive User Interface: Built with Streamlit for smooth and fast interaction.

Trained ML Models: Models saved as .sav files for quick loading and prediction.

Simple Deployment: Can be run locally or deployed on platforms like Streamlit Cloud or Heroku.

# 📊 Models Used
Diabetes Model: Trained using features like:

Pregnancies

Glucose Level

Blood Pressure

Skin Thickness

Insulin Level

BMI

Diabetes Pedigree Function

Age

Heart Disease Model: Trained on a heart disease dataset, using parameters like:

Age

Sex

Chest Pain Type

Resting Blood Pressure

Cholesterol

Fasting Blood Sugar

Rest ECG Results

Maximum Heart Rate Achieved

Exercise Induced Angina

Oldpeak

Slope

Major Vessels Colored

Thalassemia

# 🛠 Tech Stack
Frontend & App Framework: Streamlit

Backend: Python

Libraries:

pickle (model loading)

streamlit

streamlit-option-menu

scikit-learn (for model creation)

