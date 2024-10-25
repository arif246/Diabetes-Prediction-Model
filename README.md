# Diabetes Prediction Using SVM

This project focuses on predicting diabetes in patients based on various health metrics. It leverages the Support Vector Machine (SVM) algorithm to classify individuals as diabetic or non-diabetic based on their medical data. The project includes data preprocessing, model training, and evaluation, providing an accurate model to assist in preliminary diabetes screening.

### Project Overview

This Diabetes Prediction model uses an SVM classifier with a linear kernel to predict diabetes. The model is trained on a dataset containing health-related parameters like glucose levels, blood pressure, BMI, and age, which are essential indicators of diabetes risk. The main objective is to create a reliable and interpretable model to assist in identifying high-risk individuals.
### Key Components
1. Data Loading and Exploration:
- Dataset: The dataset consists of several health features, such as glucose level, BMI, age, and insulin, along with an Outcome column indicating if a person has diabetes (1) or not (0).
- Exploratory Data Analysis (EDA): Initial EDA includes summarizing dataset statistics, checking the data structure, and examining the class distribution.

2. Feature and Label Separation:
- The dataset is divided into features (X) and labels (Y). X contains the health metrics, while Y represents the diabetes outcome.

3. Data Splitting:
- The data is split into training and testing sets in an 80-20 ratio. Stratification is applied to ensure the class distribution remains consistent across training and testing datasets.

4. Model Selection and Training:
- Support Vector Machine (SVM) with a linear kernel is used as the classification algorithm. SVM is suitable for binary classification tasks and performs well with relatively small datasets.
- The model is trained on the training set to distinguish between diabetic and non-diabetic individuals based on the input features.

5. Model Evaluation:
- Accuracy Score: The model's performance is evaluated on both the training and test sets using accuracy as the primary metric.
- The training and test accuracy scores indicate the model’s effectiveness and its generalizability to new data.

6. Prediction Functionality:
- The project includes a feature where users can input their health metrics to predict whether they are likely to have diabetes.
- Based on the prediction outcome, the model outputs either “The person is diabetic” or “The person is not diabetic.”

How to Use
- Clone the Repository: Clone the repository and install required dependencies.
- Run the Script or Notebook: Load the dataset, preprocess the data, and train the SVM model.
- Make Predictions: Use the provided input_data format to check predictions for new data points.

Conclusion

This project provides an accessible and interpretable model for diabetes prediction, achieving reliable accuracy in identifying diabetic individuals. This model can serve as an initial screening tool for diabetes risk, helping individuals seek further medical guidance.
