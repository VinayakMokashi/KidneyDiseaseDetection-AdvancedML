# Chronic Kidney Disease Detection using Advanced Machine Learning Algorithms

This repository contains machine learning models and deployment tools to predict Chronic Kidney Disease (CKD) based on clinical data. The project utilizes various algorithms, from traditional classifiers to neural networks, aiming to improve diagnostic accuracy and deploy a practical solution.

## Project Overview:

Chronic Kidney Disease (CKD) is a progressive health issue, and early diagnosis is crucial for effective management. This project explores traditional and advanced machine learning approaches to classify CKD status using patient health records, focusing on a data-driven solution to aid in early detection and intervention.

## Project Structure:

### Folders and Files:

Problem_Statement_Prediction_of_Chronic_Kidney_Disease_using_Machine_Learning.pdf: Outlines the problem statement, dataset details, and primary objectives for predicting CKD

Chronic_kidney_disease_Information.pdf: Provides medical insights into CKD, including its causes, symptoms, and prevention strategies.

Neural_Networks_for_CKD_Prediction.ipynb: Jupyter Notebook detailing the use of neural networks for CKD classification. This includes:

__Data Preprocessing__: Steps to handle missing values, normalize features, and encode categorical data.

__Model Architecture__: A neural network designed to classify CKD with layers that mitigate overfitting and enhance learning.

__Training and Evaluation__: Tracks accuracy and loss over multiple epochs, highlighting the model's predictive performance.

## Model Deployment with Streamlit:

Includes a Jupyter Notebook  named Model_Deployment.ipynb and Streamlit application script named app.py to deploy the trained model. Key components are:

__Deployment Platform__: The interactive web app provides user-friendly input and prediction functionalities.

__Data Handling__: Ensures data is correctly processed before predictions.

__Inference Model__: Loads the saved model to provide real-time CKD predictions through the Streamlit interface.


## Additional Files:

Pycaret_to_predict_Kidney_diseases.ipynb & predicting_chronic_kidney_disease.ipynb discuss other ML models and Libraries for prediction. (Especially Pycaret which is very simple to implement)

## Dataset and Attributes:

Name: kidney_disease.csv

The dataset comprises 25 health indicators, including age, blood pressure, and hemoglobin levels. Each attribute is carefully preprocessed and used to enhance the predictive accuracy of the models.

## Project Workflow:

__Exploration and Data Preprocessing__: Data is explored to identify missing values and anomalies, followed by preprocessing steps like normalization and feature encoding.

__Model Training__: Multiple classifiers, including neural networks, extra trees, random forest, and several other statistical ML models are tested to determine the most accurate model.

__Model Evaluation__: Performance metrics, such as accuracy and precision, assess each model's effectiveness, with the neural network and tree-based models showing promising results.

__Deployment__: The final model is deployed using Streamlit, creating an interactive tool for real-time CKD predictions.

## Future Work:

__Hyperparameter Tuning__: Enhance model performance with optimized parameters.

__Larger Dataset__: Incorporate additional data to improve model robustness.

__Enhanced Deployment__: Add features for a more user-friendly experience in the Streamlit app.




