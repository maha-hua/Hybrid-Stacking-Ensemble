# Hybrid Stacking Ensemble Project

Hybrid machine learning ensemble project for multiclass forest cover type classification using LightGBM, XGBoost, and TabNet.

## Project Overview
This project explores the performance of hybrid stacking ensemble methods on tabular data classification. Multiple machine learning and deep learning models were combined using stacking techniques to improve overall predictive performance.

The project compares:
- Individual models
- Stacking without TabNet
- Stacking with TabNet
- Tuned vs untuned models

## Models Used
- LightGBM
- XGBoost
- TabNet
- Logistic Regression (Meta-model)

## Techniques Applied
- Out-of-Fold (OOF) stacking
- Stratified K-Fold Cross Validation
- Hyperparameter tuning
- Feature scaling
- Outlier removal
- Class balancing
- Runtime analysis

## Dataset
The project uses the Forest Cover Type dataset for multiclass classification.

## Evaluation Metrics
Models were evaluated using:
- Accuracy
- F1 Score
- Precision
- Recall
- Confusion Matrix

## Results
The stacking ensemble without TabNet achieved the best performance with approximately 91% accuracy.

## Technologies Used
- Python
- Scikit-learn
- LightGBM
- XGBoost
- PyTorch TabNet
- NumPy
- Pandas
- Matplotlib

## Notes
This project was developed for experimentation and comparison between ensemble architectures and standalone models on tabular datasets.

