# Parkinson-s-disease-prediction

Parkinson’s disease (PD) is a progressive neurological disorder that affects movement. It occurs due to the gradual degeneration of dopamine-producing neurons in the brain, particularly in the substantia nigra region.


## 📌 Overview
This project focuses on predicting Parkinson's disease using machine learning, specifically the **XGBoost algorithm**. The model is trained on a dataset containing biomedical voice measurements to distinguish between healthy individuals and Parkinson's patients.

## 📂 Dataset
The dataset used in this project is the **Parkinson’s Disease dataset** from the UCI Machine Learning Repository. It consists of various biomedical voice measurements recorded from patients, such as:
- MDVP:Fo(Hz) - Fundamental frequency
- MDVP:Jitter(%) - Jitter in voice
- MDVP:Shimmer - Shimmer amplitude variations
- NHR, HNR - Noise-to-Harmonics and Harmonics-to-Noise ratio
- Spread1, Spread2, PPE - Various speech signal features
- Status - Target variable (1 for Parkinson's, 0 for Healthy)

## 🚀 Project Workflow
1. **Data Preprocessing**
   - Handling missing values (if any)
   - Feature scaling and selection
2. **Exploratory Data Analysis (EDA)**
   - Understanding data distribution
   - Identifying important features
3. **Model Training (XGBoost)**
   - Splitting data into training and testing sets
   - Training the XGBoost classifier
   - Hyperparameter tuning using GridSearchCV
4. **Model Evaluation**
   - Accuracy, Precision, Recall, F1-score
   - Confusion matrix visualization
   - ROC-AUC curve analysis


