========================================================================
Carbonation Risk Predictor v1.0 - User Guide
========================================================================

CONTENTS:
  ✓ CarbonationRiskPredictor_v1.0.exe  (Application)
  ✓ lightgbm_model_20250721_163433.joblib  (Default Model)
  ✓ README.txt  (This file)

INSTALLATION:
  No installation required! This is a portable application.
  
  1. Keep both files in the same folder
  2. Double-click CarbonationRiskPredictor_v1.0.exe to run

USAGE:
  1. Input Parameters:
     - Fill in concrete structure parameters
     - Leave empty to use default values
     - Click gear button (⚙) to customize defaults
     
  2. Model Selection:
     - Default model loads automatically
     - Click "Select Model" to choose different .joblib model files
     
  3. Prediction:
     - Click "Start Prediction" to analyze risk
     - View detailed tree-by-tree calculation log
     - Check final risk level (Low/Medium/High)

INPUT PARAMETERS:
  • Compressive Strength (MPa): 5-78, Default: 30.0
  • Half-Cell Potential (mV): -500 to -100, Default: -250.0
  • Structure Age (years): 1-100, Default: 30.0
  • Chloride Content (%): 0.01-3.0, Default: 0.2
  • Element Type: Slab/Beam/Column, Default: Beam
  • Cement Content (kg/m³): 4.5-70.0, Default: 15.0

RISK LEVELS:
  🟢 LOW RISK: Probability < 50%
  🟡 MEDIUM RISK: 50% ≤ Probability < 80%
  🔴 HIGH RISK: Probability ≥ 80%

FEATURES:
  ✓ Single-sample risk prediction
  ✓ Custom default value settings
  ✓ Model file selection
  ✓ Detailed prediction logging
  ✓ Professional risk assessment

SYSTEM REQUIREMENTS:
  • Windows 10/11 (64-bit)
  • No additional software required
  • Minimum 1GB RAM recommended

TROUBLESHOOTING:
  • Ensure both files stay together
  • Run as administrator if needed
  • Check Windows Defender exclusions if blocked

MODEL INFORMATION:
  • LightGBM Regression Model
  • 51 decision trees, max depth 8
  • Performance: R² = 0.8356, RMSE = 0.1105
  • Training date: July 21, 2025

SUPPORT:
  For technical support, please contact the author.

========================================================================
© 2025 Carbonation Risk Predictor
======================================================================== 
