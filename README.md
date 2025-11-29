⚡🌞 Solar Cheat Scan – AI-Powered Solar Data Integrity Platform

A modern AI system that detects manipulated, faulty, or suspicious solar AC power values using machine learning, anomaly detection, and automated tamper scoring.
Built with Python, Scikit-Learn, XGBoost, LightGBM, Matplotlib, SHAP, and SMOTE.








✨ Features
🔆 Core Capabilities

Predict AC Power using ML regression models

Detect manipulated AC power using a tamper score

Auto-flag suspicious or abnormal solar readings

Graph comparison: Actual vs Predicted Power

Automatic threshold-based anomaly detection

Clean UI for solar operators and auditors

🤖 Machine Learning Features

Gradient Boosting Regressor — best model for AC power prediction

Random Forest & XGBoost for comparison

Stacking Ensemble Classifier — best for tamper detection

SMOTE for imbalance correction

SHAP for explainability

Full preprocessing pipeline

🔐 Security Features

Consistency checks for solar data

Tamper detection based on power deviations

Threshold-based suspicious label generation

Validation against unrealistic AC/DC values

🚀 Quick Start
Prerequisites

Python 3.10+

pip

Solar dataset (AC Power, DC Power, Irradiance, Temperature…)

Installation

Clone the repository

git clone https://github.com/HarshithaReddy2005/solar-cheat-scan
cd solar-cheat-scan


Install packages

pip install -r requirements.txt


Run application

python app.py


Upload dataset → View predictions → See tamper detection results

📁 Project Structure
solar-cheat-scan/
│── app.py                 # Main interface (Streamlit/Flask)
│── train_regression.py    # Regression model training
│── train_classifier.py    # Classification (tamper detection)
│── shap_analysis.py       # SHAP explainability
│── preprocess.py          # Cleaning, encoding, scaling
│── predict.py             # Model inference
│── requirements.txt
│── README.md
└── data/                  # Sample datasets

📊 Model Workflow
1. Preprocessing

Handle missing values

Normalize numerical data

Label encode categories

Remove invalid solar readings

2. Regression Models (AC Power Prediction)

Gradient Boosting Regressor (best)

Random Forest Regressor

XGBoost Regressor

3. Tamper Detection Logic
deviation = | actual - predicted |
tamper_score = deviation

if tamper_score > threshold:
    label = "Tampered"
else:
    label = "Normal"

4. Classification Models

Logistic Regression

SVM

Random Forest

XGBoost

Stacking Ensemble (best)

5. Explainability

SHAP summary plots

Feature importance visualization

🛠️ Commands
python app.py            # Run UI
python train_regression.py
python train_classifier.py
python shap_analysis.py

🎨 UI Features

Upload file section

Result table with tamper flags

Power curve graph

Highlighted anomalies

Clean colors & simple layout

📄 License

This project is licensed under MIT License.

To add license in GitHub:

Click Add File → Create New File → Name it LICENSE

Choose template → MIT License

Commit

🤝 Contributing

Fork repository

Create new branch

Commit your changes

Open Pull Request

🙏 Acknowledgments

Python, Scikit-Learn, XGBoost, LightGBM

SHAP for model explainability

Matplotlib for graph visualization

Designed to protect solar energy data integrity

📸 RESULTS (Screenshots)

(Placed at the end as you requested)

Input vs Output View

AC Power Prediction & Tamper Flags

Graph View & Anomaly Detection

Made for secure, transparent, and trustworthy solar power systems ⚡🌞
