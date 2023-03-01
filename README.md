# Industry-4.0
Implementation of AI for the Industry 4.0 in a fiber optic sensor production process

This repository contains the code and data for the Industry 4.0 project, which aims to predict the characteristics of sensors in air, water, and isopropanol using machine learning algorithms.

Project Overview
The project consists of the following main parts:

1. Data collection and exploration: Raw data was collected from sensors in air, water, and isopropanol. The data was explored to gain insights into its characteristics and to identify potential challenges in using it to build machine learning models.

2. Data preprocessing and feature engineering: Data cleaning, missing value imputation, feature scaling, and normalization were performed. Feature engineering techniques were used to extract relevant features from the raw data.

3. Machine learning model building and evaluation: Four machine learning algorithms were used to build models for predicting the sensor characteristics. These algorithms are linear regression, decision tree, random forest, and neural networks using TensorFlow. The models were evaluated using various performance metrics, such as mean squared error (MSE), coefficient of determination (R2), mean squared absolute error (MSAE), loss in TensorFlow, and score.

4. Results and conclusions: The results of the evaluation show that it is possible to predict the characteristics of sensors in water and isopropanol from 93% to 99% of the time, depending on which model is chosen. The best performing model was the neural network using TensorFlow.

Repository Structure
The repository contains the following directories:

Task: This directory contains the raw data used for the project.

AI_for_the_Industry_4_0.ipynb: This directory contains Google Collab notebooks for the various parts of the project, including data exploration, data preprocessing and feature engineering, and machine learning model building and evaluation.

Presentation: This directory contains the project report and any other relevant documents.

Requirements
To run the code in this repository, you will need the following:

Python 3.x
Googole Colab
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
TensorFlow

How to Use:
Clone the repository to your local machine.
Open the Google Collab notebooks in the notebooks directory to see the code and results of the various parts of the project.
Run the scripts in the models directory to train and test the machine learning models.
Refer to the project report in the reports directory for more details on the project and its results.

Conclusion:
This project demonstrates the use of machine learning algorithms to predict sensor characteristics in air, water, and isopropanol. By following the steps outlined in this repository, you can explore the data, preprocess and engineer features, and build and evaluate machine learning models for your own industry 4.0 applications.
