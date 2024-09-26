Project Overview

This project aims to predict crime categories using machine learning techniques based on a rich dataset containing information about crime incidents. By leveraging advanced models, the goal is to enhance law enforcement strategies and bolster public safety measures by providing insights into the likelihood of different types of crime occurring in various contexts.
The project pipeline includes Exploratory Data Analysis (EDA), Data Preprocessing, Model Training, Model Evaluation, Hyperparameter Tuning, and final prediction on the test dataset using the best-performing model.

Dataset:

The dataset consists of crime incident data with the following details:

Attributes: Date, Time, Location, Modus Operandi, Premise, etc.

Target Variable: Crime Category (multi-class target)

The dataset is preprocessed to remove any inconsistencies and to prepare it for training machine learning models.

Project Workflow:

Exploratory Data Analysis (EDA):
Visualizations and statistical analysis of the data to gain insights and detect patterns.

Data Preprocessing:

Handling missing values.

Feature scaling and encoding.

Splitting the data into training and testing sets.

Model Training:

Training various models on the processed data.

Model Evaluation:

Models are evaluated based on accuracy.

Hyperparameter Tuning:

Fine-tuning of model parameters using GridSearchCV to improve performance.

Prediction:

Final predictions on test data using the best model.

Machine Learning Models:

Various machine learning models were implemented such as Logistic Regression, Decision Trees, Support Vector Machines (SVM), K-Nearest Neighbors (KNN), Bagging (Random Forest), Boosting (AdaBoost) etc
