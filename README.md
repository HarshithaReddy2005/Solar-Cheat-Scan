⚡🌞 SOLAR CHEAT SCAN – AI-POWERED SOLAR DATA INTEGRITY PLATFORM

A modern ML based system that detects manipulated, faulty, or suspicious solar AC power values using machine learning, anomaly detection, and automated tamper scoring.

----------------------------------------------------------------------------------------------------

✨ FEATURES<br>
🔆 CORE CAPABILITIES

● Predict AC Power using advanced ML regression models<br>
● Detect manipulated AC power using a tamper score<br>
● Auto-flag suspicious or abnormal solar readings<br>
● Graph comparison: Actual vs Predicted Power<br>
● Automatic threshold-based anomaly detection<br>
● Clean and simple UI for solar operators and auditors

---------------------------------------------------------------------------

🤖 MACHINE LEARNING FEATURES

■ Gradient Boosting Regressor — Best model for AC Power prediction<br>
■ Random Forest & XGBoost for comparison<br>
■ Stacking Ensemble Classifier — Best for tamper detection<br>
■ SMOTE for imbalance correction<br>
■ SHAP explainability for model transparency<br>
■ Full preprocessing pipeline

-------------------------------------------------------------------------------

🔐 SECURITY FEATURES

○ Consistency checks for solar data<br>
○ Tamper detection based on power deviation<br>
○ Threshold-based suspicious label generation<br>
○ Validation against unrealistic AC/DC values

----------------------------------------------------------------------------------------------
 
 📊 MODEL WORKFLOW
1. PREPROCESSING

   ● Handle missing values<br>
   ● Normalize numerical data<br>
   ● Label encode categories<br>
   ● Remove invalid solar readings

2. REGRESSION MODELS (AC POWER PREDICTION)
  
   ■ Gradient Boosting Regressor (BEST)<br>
   ■ Random Forest Regressor<br>
   ■ XGBoost Regressor

3. TAMPER DETECTION LOGIC<br>

  **deviation = | actual - predicted | <br>
  tamper_score = deviation** <br>
  
  **if tamper_score > threshold:<br>
      label = "Tampered"**  <br>
  **else:<br>
      label = "Normal"**

4. CLASSIFICATION MODELS

   ○ Logistic Regression<br>
   ○ SVM<br>
   ○ Random Forest<br>
   ○ XGBoost<br>
   ○ Stacking Ensemble (BEST)

5. EXPLAINABILITY
 
   ● SHAP summary plots<br>
   ● Feature importance visualization

------------------------------------------------------------------------
 

🌞 MADE FOR SECURE, TRANSPARENT & TRUSTWORTHY SOLAR POWER SYSTEMS ⚡
