# Heart Disease Prediction using Logistic Regression

This repository contains the code and dataset required for the Heart Disease Prediction Machine Learning Model which predicts whether a person has a healthy heart or has a heart disease using Logistic Regression Model. It involves data pre-processing , feature selection, data splitting and model training and model evaluation. The goal is to create a reliable tool for early diagnosis and preventive healthcare.

## Project workflow
- Loading and exploring the dataset
- Data preprocessing: checking for missing values, distribution , etc.
- Feature analysis and visualization
- Splitting the features and target
- Train test split
- Model training using logistic regression
- Model evaluation using metrics such as accuracy score
- Building a predictive system

## Results
The trained model achieved the following performance metrics:

- Accuracy of training data: 0.85 
- Accuracy of training data: 0.82

## Requirements
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Logistic Regression - A linear model for binary classification

## About Dataset :

### context
This data set dates from 1988 and consists of four databases: Cleveland, Hungary, Switzerland, and Long Beach V. It contains 76 attributes, including the predicted attribute, but all published experiments refer to using a subset of 14 of them. The "target" field refers to the presence of heart disease in the patient. It is integer valued 0 = no disease and 1 = disease.

### content
Attribute Information:
- age
- sex
- chest pain type (4 values)
- resting blood pressure
- serum cholesterol in mg/dl
- fasting blood sugar > 120 mg/dl
- resting electrocardiographic 
- maximum heart rate achieved
- exercise induced angina
- oldpeak = ST depression induced by exercise relative to rest
- the slope of the peak exercise ST segment
- number of major vessels (0-3) colored by fluoroscopy
- thal: 1 = normal; 2 = fixed defect; 3 = reversible defect
- target : 0(healthy) or 1(defective)

Feel free to dive into the code, experiment with different features, and enhance the project further. If you have any suggestions, I'd love to hear from you. Happy coding!