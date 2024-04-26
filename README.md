# Ensemble Learning for Molecular Binding Prediction

The project utilises ML models and ensembles to predict molecular binding, leveraging fingerprints and protein features. It evaluates model performance, integrates calibration for refined predictions, and aims to optimise accuracy in chemical compound interactions. Tools: DuckDB, RDKit, XGBoost, CatBoost, LightGBM, Ensemble Learning,Calibration

The purpose is to develop machine learning (ML) models that can accurately predict the binding affinity of small molecules to specific protein targets. This task is crucial in drug development, as it helps identify potential drug candidates more efficiently. Traditional methods of identifying such candidates involve physically testing each molecule's interaction with the protein target, which is laborious and time-consuming.


This code is a comprehensive pipeline for molecular binding prediction. It involves:

- Data processing using Pandas and DuckDB.
  <img width="739" alt="Screenshot 2024-04-26 at 2 48 32 PM" src="https://github.com/yujansaya/molecule_binding_prediction/assets/109923065/ade7e92d-0d35-4165-bc51-ae6510a52d0e">

- Molecular fingerprint generation using RDKit.
  
  <img width="524" alt="Screenshot 2024-04-26 at 2 47 59 PM" src="https://github.com/yujansaya/molecule_binding_prediction/assets/109923065/a5c9daee-b6b6-45a8-85a8-356039f037a2">

- Model training with various classifiers including Random Forest, XGBoost, LightGBM, CatBoost, SVM, and MLP.
  <img width="679" alt="Screenshot 2024-04-26 at 2 50 15 PM" src="https://github.com/yujansaya/molecule_binding_prediction/assets/109923065/041b9a05-ef4f-44f3-b761-07881dc6cb2f">

- Ensemble techniques such as Stacking, Blending, and Bagging.
- Evaluation of individual models and ensembles using Average Precision Score.
  <img width="607" alt="Screenshot 2024-04-26 at 2 50 23 PM" src="https://github.com/yujansaya/molecule_binding_prediction/assets/109923065/48716a6c-1c39-4d57-9aaf-86d597a05605">

- Test set predictions, calibration, and ensemble predictions.

