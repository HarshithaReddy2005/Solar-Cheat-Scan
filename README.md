**Solar Cheat Scan
Detection of Tampering in Solar Forecast Data using Machine Learning**

Solar Cheat Scan is an AI-driven system that predicts AC power, detects manipulation, and classifies Normal vs Tampered solar data.
It ensures data integrity, transparency, and reliability in solar forecasting systems.

------------------------------------------------------------------------------------------------------------------------------------------------

📌 **Project Overview**

Solar forecast data may get corrupted due to faults or manual tampering.

Existing forecasting models cannot verify authenticity of the data.

This project integrates forecasting + deviation scoring + classification to detect tampering.

Provides explainability and visualization through a dashboard.

---------------------------------------------------------------------------------------------------------

📌 **Key Features**

Accurate ML-based AC power prediction.

Tamper Score generation using deviation logic.

Normal/Tampered classification using ML models.

15-day AC power forecasting.

SHAP-based model interpretability.

Interactive Streamlit dashboard for monitoring.

------------------------------------------------------------------------------------------------

📌 **Problem Statement**

No existing system validates solar forecast data before usage.

Hard to detect manipulation in large, nonlinear time-series datasets.

Incorrect data leads to financial loss and grid mismanagement.

---------------------------------------------------------------------------------------------

📌 **Objectives**
Primary

Predict expected AC power using regression models.

Detect deviations & compute tamper scores.

Classify data as Normal or Tampered.

Secondary

15-day future AC power forecasting.

Provide explainability via SHAP.

Build an interactive dashboard.

----------------------------------------------------------------------------------------------

📌 **Literature Review**

Past research focuses mainly on forecast accuracy.

Anomaly detection models do not target intentional manipulation.

No integrated pipeline combining:

Prediction

Deviation scoring

Tamper classification

------------------------------------------------------------------------------------------

📌 **Methodology**

Collect solar AC power + weather data.

Clean, merge, and preprocess the dataset.

Perform feature engineering (rolling, lag, time-based features).

Train regression models for AC power prediction.

Calculate deviation = |Actual – Predicted| → Tamper Score.

Train classification & stacking models for tamper detection.

Forecast AC power for 15 days.

Visualize outputs through a dashboard.

--------------------------------------------------------------------------------------------------

📌 **System Architecture**

Input: AC power + weather parameters
Process:
Cleaning → Feature Engineering → Regression → Deviation → Classification → Forecasting
Output:

Normal/Tampered label

Tamper score

15-day forecast

-----------------------------------------------------------------------------------------------------------------

📌 **Tech Stack**

Python

Pandas, NumPy

Scikit-Learn, XGBoost, LightGBM

Matplotlib, Seaborn

SHAP

Streamlit

Tools: Jupyter, VS Code, GitHub

-----------------------------------------------------------------------------------------------------------

📌 **Models Used**
Regression

Gradient Boosting Regressor (best)

Random Forest Regressor

XGBoost Regressor

Classification

Logistic Regression

SVM

Random Forest

XGBoost

Stacking Ensemble (best)

Tamper Logic
Deviation = |Actual - Predicted|
Tamper Score = function(deviation)
Threshold → Normal / Tampered

---------------------------------------------------------------------------------------------------------------------------------

📌 **Results**

R² = 1.000 → Highly accurate AC power prediction.

Stacking model gives best tamper detection accuracy.

Dashboard clearly shows deviations and tampered points.

-----------------------------------------------------------------------------------------------------------------------------

📌 **Conclusion**

Solar Cheat Scan is a comprehensive ML-based solution to ensure tamper-proof and reliable solar forecasting.
It helps solar plants maintain data authenticity, improve decision-making, and protect grid operations.
