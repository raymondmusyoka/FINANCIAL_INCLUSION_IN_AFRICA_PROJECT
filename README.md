# FINANCIAL_INCLUSION_IN_AFRICA_PROJECT
# East African Financial Inclusion Predictor
Overview
The East African Financial Inclusion Predictor is a machine learning project aimed at predicting the likelihood of individuals in East Africa having a bank account. This project uses demographic information and financial services usage data from four East African countries: Kenya, Rwanda, Tanzania, and Uganda. The goal is to build a predictive model that can determine whether a person is likely to have a bank account or not.

Dataset
The dataset used for this project contains demographic information and information about the financial services used by approximately 33,600 individuals across the four East African countries. The data was extracted from various Finscope surveys conducted between 2016 and 2018. Here are the links to the specific survey data sources:

FinAccess Kenya 2018
Finscope Rwanda 2016
Finscope Tanzania 2017
Finscope Uganda 2018
Problem Statement
The main objective of this project is to predict whether a person has a bank account or not, with the target variable coded as follows: Yes = 1, No = 0. To achieve this, we will use machine learning techniques to train a model on a portion of the dataset and evaluate its performance on the remaining data. The model will make predictions for each unique ID in the test dataset.

Project Structure
The project is structured as follows:

data: This folder contains the dataset files from the Finscope surveys for each country.

notebooks: Jupyter notebooks are provided to guide you through the data exploration, preprocessing, feature engineering, model training, and evaluation processes.

src: The source code for the machine learning model is located here. You'll find Python scripts for data preprocessing, feature engineering, model training, and prediction.

models: This directory stores trained models in a serialized format for future use.

requirements.txt: A list of required Python libraries and their versions for setting up the project environment.
