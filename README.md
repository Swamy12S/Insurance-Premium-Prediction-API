# 🧠 Insurance Premium Prediction API

## 🚀 Overview
The **Insurance Premium Prediction API** is a machine learning–powered web service built using **FastAPI**, **Docker**, and deployed on **AWS**.  
It predicts an individual's **insurance premium amount** based on key demographic and lifestyle attributes such as **BMI**, **Age Group**, **Lifestyle Risk**, **City Tier**, **Income**, and **Occupation**.

---

## 📁 Project structure
```text
insurance-premium-prediction-api/
│
├── app.py                     # Main FastAPI application (endpoints)
├── config/                    # Configuration files (if any)
├── model/                     # Model code + serialized model
│   ├── predict.py
│   └── model.pkl
├── schema/                    # Pydantic request/response models
│   ├── user_input.py
│   └── prediction_response.py
├── requirements.txt           # Python dependencies
├── Dockerfile                 # Docker configuration
├── .dockerignore
├── .gitignore
└── README.md                  # This file
