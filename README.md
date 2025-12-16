# End-to-End-Diabetes-Prediction
Diabetes Prediction
This repository contains an end-to-end machine learning project aimed at predicting the likelihood of diabetes based on user-provided health data. The project demonstrates the full machine learning pipeline from data gathering to model deployment using a Flask web application hosted on Heroku.

Project Overview
The goal of this project is to create a seamless process for predicting diabetes by building a machine learning model that analyzes various health parameters. The web application takes user input, processes the data through the model, and provides the prediction result on a new page.

Project Objectives
The project follows these key steps:

Data Gathering: Collected relevant medical data from various sources, including public datasets.
Descriptive Analysis: Explored the dataset to understand the underlying patterns and trends.
Data Visualizations: Created insightful visualizations to represent key relationships in the data.
Data Preprocessing: Cleaned and transformed the data for use in the machine learning model.
Data Modelling: Trained a machine learning model using scikit-learn to predict diabetes.
Model Evaluation: Assessed the model's performance using various metrics to ensure accuracy.
Model Deployment: Deployed the model as a web application using Flask, hosted on Heroku.
Technical Aspects
Machine Learning Model
Library: scikit-learn
Algorithms Used: Logistic Regression, Decision Trees, Random Forests (or any chosen algorithms based on your project)
Input Features: The following fields are taken from the user:
Number of Pregnancies
Insulin Level
Age
Body Mass Index (BMI)
Blood Pressure
Glucose Level
Skin Thickness
Diabetes Pedigree Function
Output: The model predicts whether the person is likely to have diabetes (Yes/No).
Web Application
Framework: Flask
Deployment: Hosted on Heroku for easy access.
Functionality:
The user provides health-related data via a form.
After submitting the form, the model processes the data and presents the prediction on a new page.
How to Use
Prerequisites
Python 3.x
Flask
scikit-learn
Pandas
Heroku CLI (for deployment)
Installation
Clone this repository:
