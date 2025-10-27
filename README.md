# 🧠 Insurance Premium Prediction API

## 🚀 Overview
The **Insurance Premium Prediction API** is a machine learning–powered web service built using **FastAPI**, **Docker**, and deployed on **AWS**.  
It predicts an individual's **insurance premium amount** based on key demographic and lifestyle attributes such as **BMI**, **Age Group**, **Lifestyle Risk**, **City Tier**, **Income**, and **Occupation**.

---

## 🏗️ Project Structure
insurance-premium-prediction-api/
│
├── app.py # Main FastAPI application
├── config/ # Configuration files (if any)
├── model/ # Contains trained ML model and prediction logic
│ ├── predict.py
│ └── model.pkl
├── schema/ # Request and Response Pydantic models
│ ├── user_input.py
│ └── prediction_response.py
├── requirements.txt # Python dependencies
├── Dockerfile # Docker configuration
├── .gitignore # Files/folders to ignore in Git
└── README.md # Project documentation
