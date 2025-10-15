🩺 Stroke Prediction Web App
🌟 Overview

This project is a Streamlit-based web application that predicts the likelihood of a person having a stroke based on medical and demographic features.
It uses Machine Learning models (RandomForest & XGBoost) trained on a real-world healthcare dataset to deliver accurate and interpretable results.

The web app provides a smooth and user-friendly interface for exploring the dataset, training models, viewing evaluation metrics, and predicting stroke risk for new patients.

🚀 Features

📊 Data Overview: Automatically loads and cleans the healthcare stroke dataset

🧹 Data Cleaning: Removes the unnecessary id column and restricts gender to Male and Female only

⚙️ Model Training: Train RandomForest and XGBoost classifiers directly from the app

📈 Model Evaluation: Displays accuracy, F1 score, confusion matrix, and ROC curve

🩺 Prediction:

Single Prediction: Fill in patient details via dropdowns & sliders (no manual typing)

Batch Prediction: Upload a CSV file and download results instantly

💡 Interactive Interface: Simple, clean, and professional layout for all users

🧩 Dataset Information

File: healthcare-dataset-stroke-data.csv
Target Column: stroke

0 → No Stroke

1 → Stroke

Main Features:

gender

age

hypertension

heart_disease

ever_married

work_type

Residence_type

avg_glucose_level

bmi

smoking_status
