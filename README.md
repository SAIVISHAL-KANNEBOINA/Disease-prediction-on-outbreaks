🧑‍⚕️ Disease Prediction on Outbreaks using Machine Learning

A web-based application built using Streamlit that predicts the likelihood of three major diseases — Diabetes, Heart Disease, and Parkinson’s Disease — using pre-trained Machine Learning models.

📌 Project Overview

This project provides an easy-to-use interface for early detection of critical diseases. Users can enter medical parameters and instantly receive predictions based on trained ML models.

Supported Predictions
Disease	Model File
Diabetes	saved_models/diabetes_model.sav
Heart Disease	saved_models/heart_model.sav
Parkinson’s	saved_models/parkinsons_model.sav
🧠 Technologies Used

Python

Streamlit

Scikit-Learn

Pickle

Pandas, NumPy

streamlit-option-menu

📂 Project Structure
Disease-prediction-on-outbreaks/
│
├── datasets/                # Datasets used for training
├── saved_models/            # Trained ML models
│     ├── diabetes_model.sav
│     ├── heart_model.sav
│     └── parkinsons_model.sav
│
├── training_model/          # Model training scripts / notebooks
├── web.py                   # Streamlit Web Application
├── requirements.txt        # Required Python packages
└── .gitignore

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/SAIVISHAL-KANNEBOINA/Disease-prediction-on-outbreaks.git
cd Disease-prediction-on-outbreaks

2️⃣ Create Virtual Environment (Optional but Recommended)
python -m venv venv
venv\Scripts\activate   # Windows
source venv/bin/activate  # Mac/Linux

3️⃣ Install Required Libraries
pip install -r requirements.txt

▶️ Run the Application
streamlit run web.py


Your browser will open automatically at:

http://localhost:8501

🖥️ Application Features
🩺 Diabetes Prediction

Uses features like:

Pregnancies

Glucose Level

Blood Pressure

Insulin

BMI

Age etc.

❤️ Heart Disease Prediction

Based on parameters like:

Age

Chest Pain Type

Resting Blood Pressure

Cholesterol

Max Heart Rate

ST Depression etc.

🧠 Parkinson’s Prediction

Voice-based features such as:

MDVP Frequencies

Jitter & Shimmer

NHR, HNR

Spread & PPE etc.

🧪 Sample Output
The person is diabetic
The person does not have heart disease
The person has Parkinson’s disease

🎯 Purpose

This system helps in early disease detection and awareness, enabling people to take preventive measures and consult medical professionals in time.

⚠️ Disclaimer

This application is built for educational purposes only and should not be used as a substitute for professional medical diagnosis.

👨‍💻 Developed By

Saivishal Kanneboina
B.Tech – Data Science
GitHub: SAIVISHAL-KANNEBOINA
