# Ensemble Learning for Molecular Binding Prediction

The project utilises ML models and ensembles to predict molecular binding, leveraging fingerprints and protein features. It evaluates model performance, integrates calibration for refined predictions, and aims to optimise accuracy in chemical compound interactions. Tools: DuckDB, RDKit, XGBoost, CatBoost, LightGBM, Ensemble Learning,Calibration

The purpose is to develop machine learning (ML) models that can accurately predict the binding affinity of small molecules to specific protein targets. This task is crucial in drug development, as it helps identify potential drug candidates more efficiently. Traditional methods of identifying such candidates involve physically testing each molecule's interaction with the protein target, which is laborious and time-consuming.


This code is a comprehensive pipeline for molecular binding prediction. It involves:

- Data processing using Pandas and DuckDB.
- Molecular fingerprint generation using RDKit.
- Model training with various classifiers including Random Forest, XGBoost, LightGBM, CatBoost, SVM, and MLP.
- Ensemble techniques such as Stacking, Blending, and Bagging.
- Evaluation of individual models and ensembles using Average Precision Score.
- Test set predictions, calibration, and ensemble predictions.

