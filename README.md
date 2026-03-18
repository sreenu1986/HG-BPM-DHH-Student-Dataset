Title: HG-BPM for DHH Student Performance Prediction

Description:
Hybrid GA-Boosted Predictive Model using CTGAN and Ensemble Learning.

Dataset:
- Source: https://doi.org/10.1109/ACCESS.2024.3363634 
- Samples: 454 original + augmented data

Code:
- preprocessing.py
- ctgan.py
- feature_selection.py
- model.py
- evaluation.py

Usage:
1. Install dependencies (requirements.txt)
2. Run preprocessing.py
3. Run ctgan.py
4. Run model.py

Requirements:
Python 3.9+
Libraries: numpy, pandas, sklearn, xgboost, lightgbm, ctgan

Methodology:
Preprocessing → CTGAN → XT Feature Selection → XGB+LightGBM → GA Optimization

License:
MIT License
