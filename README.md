**SOLAR CHEAT SCAN** 
About the Project

AI system to verify and protect solar forecast data.

Detects manipulated or suspicious AC power values.

Integrates forecasting, anomaly detection, and classification.

Ensures transparency and reliability in renewable energy systems.

Problem Identification

No system checks whether solar forecasts are genuine or tampered.

Manipulation is difficult to detect in large time-series datasets.

Incorrect forecasts cause financial loss and grid mismanagement.

Existing ML models lack explainability.

Objectives
Primary Goals

Predict accurate AC power using machine learning.

Detect deviations and compute tamper scores.

Classify data as Normal or Tampered.

Secondary Goals

Forecast AC power for the next 15 days.

Provide interpretability using SHAP.

Build a visual dashboard for insights.

Literature Review

Existing works focus on forecast accuracy, not data authenticity.

Anomaly detection exists, but not for deliberate manipulation.

No combined approach of forecasting + deviation scoring + classification.

Defining the Objective

Build an AI system that predicts, detects, and explains tampering in solar data.

Ensure data integrity for solar power plants.

Proposed Plan

Collect solar and weather data.

Preprocess and engineer features.

Train regression and classification models.

Calculate tamper scores.

Use stacking ensemble for improved accuracy.

Forecast AC power for 15 days.

Build a dashboard for results.

System Architecture

Input: Solar AC power + weather data

Processing: Cleaning → Feature Engineering → Regression → Deviation → Classification → Forecasting

Output: Normal/Tampered labels, forecast graphs, tamper score plots

Workflow

Data → Cleaning → Features → Forecasting → Deviation → Tamper Detection → Future Forecasting → Dashboard

Technology Used

Python

Pandas, NumPy

Scikit-Learn, XGBoost, LightGBM

Matplotlib, SHAP

Streamlit

Core Algorithms

Regression: GBR, RFR, XGBR

Classification: Logistic Regression, SVM, Random Forest, XGBoost, Stacking

Tamper Detection: Deviation-based scoring

Results

R² = 1.000 (highly accurate forecasting)

Stacking model performs best for tamper detection.

Dashboard clearly highlights tampered points and future trends.

Conclusion

Solar Cheat Scan ensures reliable, transparent, and tamper-proof solar forecasting.

Detects manipulation, supports smart-grid systems, and strengthens renewable energy data integrity.
