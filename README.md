⚡🌞 SOLAR CHEAT SCAN – AI-POWERED SOLAR DATA INTEGRITY PLATFORM

A modern AI system that detects manipulated, faulty, or suspicious solar AC power values using machine learning, anomaly detection, and automated tamper scoring.

✨ FEATURES
🔆 CORE CAPABILITIES

● Predict AC Power using advanced ML regression models<br>
● Detect manipulated AC power using a tamper score<br>
● Auto-flag suspicious or abnormal solar readings<br>
● Graph comparison: Actual vs Predicted Power<br>
● Automatic threshold-based anomaly detection<br>
● Clean and simple UI for solar operators and auditors

🤖 MACHINE LEARNING FEATURES

■ Gradient Boosting Regressor — Best model for AC Power prediction
■ Random Forest & XGBoost for comparison
■ Stacking Ensemble Classifier — Best for tamper detection
■ SMOTE for imbalance correction
■ SHAP explainability for model transparency
■ Full preprocessing pipeline

🔐 SECURITY FEATURES

○ Consistency checks for solar data
○ Tamper detection based on power deviation
○ Threshold-based suspicious label generation
○ Validation against unrealistic AC/DC values

🚀 QUICK START
PREREQUISITES

● Python 3.10+
● pip
● Solar dataset (weather + plant data)

 

 
📊 MODEL WORKFLOW
1. PREPROCESSING

● Handle missing values
● Normalize numerical data
● Label encode categories
● Remove invalid solar readings

2. REGRESSION MODELS (AC POWER PREDICTION)

■ Gradient Boosting Regressor (BEST)<br>
■ Random Forest Regressor<br>
■ XGBoost Regressor

3. TAMPER DETECTION LOGIC
deviation = | actual - predicted |
tamper_score = deviation

if tamper_score > threshold:
    label = "Tampered"
else:
    label = "Normal"

4. CLASSIFICATION MODELS

○ Logistic Regression<br>
○ SVM<br>
○ Random Forest<br>
○ XGBoost<br>
○ Stacking Ensemble (BEST)

5. EXPLAINABILITY

● SHAP summary plots<br>
● Feature importance visualization

📸 RESULTS (SCREENSHOTS)

(Placed at the end as requested)

■ Input vs Output View<br>
■ AC Power Prediction & Tamper Flags<br>
■ Graph View & Anomaly Detection

🌞 MADE FOR SECURE, TRANSPARENT & TRUSTWORTHY SOLAR POWER SYSTEMS ⚡
