# HG-BPM: Academic Performance Prediction for Deaf Learners

## Project Title
Data-driven identification of academic risk factors in deaf and hard-of-hearing students using interpretable machine learning

## Description
This repository provides the complete implementation of the Hybrid GA-Boosted Predictive Model (HG-BPM) developed to predict the academic performance of Deaf and Hard-of-Hearing (DHH) students. The model integrates feature selection, ensemble learning, generative data augmentation, and evolutionary hyperparameter optimization to improve prediction accuracy under limited and imbalanced data conditions.

The work is intended as an AI Application to support inclusive education by assisting educators in identifying at-risk students and understanding key factors influencing academic outcomes.

## Dataset Information
The dataset used in this study was obtained from:

Raji et al., "Explainable Machine Learning Prediction for the Academic Performance of Deaf Scholars", IEEE Access, 2024  
DOI: 10.1109/ACCESS.2024.3363634 

The dataset contains records of 454 Deaf and Hard-of-Hearing students with socio-economic, deafness-related, and prior academic performance features.

Synthesis data is given in the name deaf_students_ctgan_augumented.
HG_BPM/
│
├── data/
│   └── dhh_students.csv
│
├── hg_bpm_end_to_end.ipynb   ← upload this
├── requirements.txt
└── README.md

## Features
- Socio-economic attributes (gender, income, parental education)
- Deafness-related attributes (hearing loss degree, communication mode, therapy)
- Academic attributes (Class 10 and 12 marks, semester scores)

## Code Information
The codebase includes:
- Data preprocessing and encoding
- CTGAN-based data augmentation
- Extra Trees-based feature selection
- Stacked ensemble model (XGBoost + LightGBM)
- Genetic Algorithm-based hyperparameter optimization
- Model evaluation and comparison

## Requirements
Python version: 3.9 or later

Required libraries are listed in the `requirements.txt` file.

## Installation
Install dependencies using:
pip install -r requirements.txt

## Usage Instructions
1. Place the dataset CSV file in the `/data/` directory.
2. Run preprocessing and encoding.
3. Generate synthetic data using CTGAN.
4. Perform feature selection using Extra Trees.
5. Train the stacked XGB–LightGBM model.
6. Optimize hyperparameters using Genetic Algorithm.
7. Evaluate performance using accuracy, precision, recall, and F1-score.

## Methodology
HG-BPM follows a structured pipeline:
- Data preprocessing and scaling
- Synthetic data generation using CTGAN
- Feature importance ranking using Extra Trees
- Hybrid ensemble learning
- Evolutionary optimization using Genetic Algorithm

## Evaluation Metrics
The model is evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- AUC-ROC

## Citation
If you use this work, please cite:

Raji et al., IEEE Access, 2024  


## License
This project is intended for academic and research purposes only.
