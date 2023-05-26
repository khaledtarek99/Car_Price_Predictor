# Car Price Prediction
![image](https://github.com/khaledtarek99/Car_Price_Predictor/assets/53887110/5bb99302-790b-4f6e-a671-1c744ffa9aaa)

This repository contains a data analysis project aimed at solving the problem of determining the optimal selling price for a car. The goal is to help individuals who are looking to sell their car by providing them with insights on how to set a reasonable price that accurately represents the value of their vehicle, ensuring that potential buyers find it appealing.
## Problem Statement
When selling a car, people often face the challenge of setting an appropriate price. On one hand, they want to maximize their selling price and obtain the highest possible value for their vehicle. On the other hand, they need to ensure that the price is set reasonably so that potential buyers are enticed to make a purchase. This project addresses this predicament by leveraging data analysis techniques to predict the optimal selling price for a car based on its various attributes.
## Dataset
The dataset used in this project is provided in the repository and consists of two main files:
* ` AutoMobile_DataSet.csv `: This file contains the raw data on various attributes of cars, such as make, body style, drive wheels, engine location, horsepower, Price, and more.
* ` clean_AutoMobile.csv ` : This file contains a cleaned version of the dataset after performing data wrangling and preprocessing steps. It serves as the input for the subsequent data analysis and modeling steps.
## Notebooks
The project is divided into several Jupyter notebooks, each focusing on a specific stage of the data analysis process. The notebooks in this repository are as follows:
1. ` Data_Wrangling_Of_Automobile-Dataset.ipynb ` : This notebook outlines the steps taken to clean, preprocess, and transform the raw dataset (AutoMobile_DataSet.csv) into a clean and structured format (clean_AutoMobile.csv). It covers data cleaning, handling missing values, correcting data format, and feature engineering.
2. ` EDA_Of_Automobile-Dataset.ipynb ` : This notebook explores the clean dataset (clean_AutoMobile.csv) through exploratory data analysis (EDA) techniques. It visualizes and summarizes the data, identifies patterns, correlations, and insights related to car attributes, and provides a deeper understanding of the dataset.
3. ` Model_Development.ipynb ` : In this notebook, machine learning models are developed to predict the selling price of cars based on the available features. Various regression models are trained and evaluated using appropriate techniques. The notebook demonstrates the process of model selection and development, including feature selection, model training, hyperparameter tuning, and model evaluation.
4. ` Model_Evaluation_and_Refinement.ipynb ` : This notebook focuses on evaluating the performance of the trained regression models and refining them further. It involves analyzing model metrics, identifying areas of improvement, and applying techniques such as regularization or ensemble methods to enhance model performance.
## Usage
To use this repository and reproduce the results, follow these steps: <br />
1. Clone the repository to your local machine
2. Install the necessary dependencies. It is recommended to use a virtual environment
3. Open and run the Jupyter notebooks in the following order:
   * Data_Wrangling_Of_Automobile-Dataset.ipynb
   * EDA_Of_Automobile-Dataset.ipynb
   * Model_Development.ipynb
   * Model_Evaluation_and_Refinement.ipynb
4. Follow the instructions within each notebook to execute the code, generate visualizations, and explore the results.
## Conclusion
This project provides a comprehensive analysis of car pricing, guiding users on how to set a reasonable selling price that aligns with the value of their vehicle. By leveraging the dataset, performing data wrangling, conducting exploratory data analysis, and developing predictive models, users can gain insights and make informed decisions when pricing their cars for sale.
