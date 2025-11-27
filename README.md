🌞⚡ **SOLAR CHEAT SCAN**
 **About the Project**

🔹 AI-powered system to verify, validate, and protect solar forecast data

🔹 Detects manipulated, faulty, or suspicious AC power readings

🔹 Combines forecasting + anomaly detection + classification in one pipeline

🔹 Ensures trust, transparency, and reliability in renewable energy systems
--------------------------------------------------------------------------------
⚠️ Problem Identification

❌ No system verifies if solar forecasts are authentic or tampered

❌ Manipulation is hard to detect in large solar time-series data

❌ Wrong forecasts lead to financial loss, grid imbalance, poor planning

❌ Existing ML models behave like black boxes with no explainability
--------------------------------------------------------------------------------
 **Objectives**
Primary Goals

✔️ Predict accurate AC power using ML

✔️ Detect deviations & compute tamper scores

✔️ Classify data as Normal / Tampered

Secondary Goals

✔️ 15-day AC power forecasting

✔️ Visual dashboard for insights

✔️ SHAP explainability for transparency
---------------------------------------------------------------------------------------------------
**Literature Review**

🔸 Existing works focus only on forecast accuracy, not tamper detection

🔸 DL models detect anomalies but not deliberate manipulation

🔸 No integrated system combining:

Forecasting

Deviation scoring

Classification

**Defining the Objective**

 Build an AI system to predict, detect, explain, and visualize solar data tampering

 Ensure data integrity & reliability for solar plants

 Proposed Plan (Short)

🔹 Collect solar + weather datasets

🔹 Preprocess & engineer features

🔹 Train regression & classification models

🔹 Compute tamper scores

🔹 Build stacking ensemble classifier

🔹 Forecast AC power for next 15 days

🔹 Develop interactive dashboard

**System Architecture**
Input

🌤️ Solar AC power data

🌡️ Weather data (irradiation, humidity, temperature, wind)

Processing

Cleaning → Feature Engineering → Regression → Deviation → Classification → Forecasting

Output

🔍 Normal / Tampered labels

📈 Forecast graphs

🟥 Tamper score visualizations

🔄 Workflow
Data → Cleaning → Features → Forecast → Deviation → Tamper Detection → Future Forecast → Dashboard
--------------------------------------------------------------------------------------------------------------------
**Technology Used**

🐍 Python

📦 Pandas, NumPy

🤖 Scikit-Learn, XGBoost, LightGBM

📊 Matplotlib, SHAP

🖥️ Streamlit Dashboard

🧠 Core Algorithms

🔹 Regression: GBR, RFR, XGBR

🔹 Classification: LR, SVM, RF, XGB, Stacking

🔹 Tamper Logic: Deviation-based scoring
---------------------------------------------------------------------------------------------------------------
**Results**
Regression

⭐ R² = 1.000

⭐ RMSE = 0.661, MAE = 0.209
➡️ Ultra-accurate forecasting

Classification

🥇 Stacking Model = Best for tamper detection

🔹 High recall

🔹 Very low false alarms

Dashboard

📉 Actual vs Predicted curves

🟥 Tampered timestamps highlighted

📆 15-day AC power forecast

🔥 Tamper score heatmap
---------------------------------------------------------------------------------------------
**Conclusion**

🌟 Solar Cheat Scan delivers AI-driven data integrity for solar forecasting

🌟 Detects hidden manipulation & supports smart-grid reliability

🌟 A complete end-to-end solution for secure renewable energy forecasting
