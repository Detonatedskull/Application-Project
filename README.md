# Stroke Prediction using various Machine Learning algorithms

## Author details and intended audience details:
  Author : Kiran Pillai
  AIML Developer 
  https://www.linkedin.com/in/kiran-pillai-492523242/

  Intended Audience: Google internship recruitement team 
  for the post of Customer Engineering Intern, Google Cloud, Summer 2024 - Gurgaon
  

## About Project:
The project involves building classification models to predict the occurrence of strokes based on various demographic and health-related features. The dataset has been preprocessed, normalized, and resampled to handle class imbalance. The main steps involved in this project are as follows:

Data Preprocessing: This step involves handling missing values, encoding categorical variables (one-hot encoding), and scaling numerical features (e.g., using MinMaxScaler).

Handling Class Imbalance: Class imbalance is a common issue in classification tasks where one class is significantly more prevalent than the other(s). In this project, techniques such as SMOTE (Synthetic Minority Over-sampling Technique) and ADASYN (Adaptive Synthetic Sampling) are used to resample the dataset and balance the classes.

Model Selection: Various classification models are considered, including Logistic Regression, Support Vector Machines (SVM), Decision Trees, Random Forests, Gradient Boosting XGBoost, and Artificial Neural Networks (ANN). Each model's architecture and hyperparameters are chosen based on experimentation and performance evaluation.

Model Training: The selected models are trained on the preprocessed and resampled training data. During training, the models learn to associate the input features with the target variable (stroke/no stroke) using optimization algorithms such as gradient descent.

Model Evaluation: Once trained, the models are evaluated using the preprocessed test data. Performance metrics such as accuracy, precision, recall, and F1-score are computed to assess how well the models generalize to unseen data.

Model Comparison: The performance of each model is compared based on the evaluation metrics. The model that achieves the highest accuracy and satisfactory performance in terms of precision, recall, and F1-score is considered the best for predicting strokes.

Model Deployment (Optional): Depending on the project's requirements, the best-performing model can be deployed in a real-world setting to make predictions on new, unseen data.

Overall, the project aims to develop an effective classification model for stroke prediction by leveraging machine learning techniques and addressing challenges such as class imbalance. By following these main steps, the project seeks to provide valuable insights for healthcare professionals in identifying individuals at risk of stroke.
