# Chronic Disease Analysis

## Overview
This project analyzes chronic disease data from the U.S. Chronic Disease Indicators dataset to identify insights and patterns related to different disease topics. The analysis focuses on exploring the data, visualizing distributions of diseases, topics and questions, and building classification models to predict disease topics from input features.

## Data
The data comes from the U.S. Chronic Disease Indicators (CDI) dataset and contains information on chronic disease prevalence, mortality, risk factors, and health system metrics for the U.S. at national and state levels. 

Main data fields:
- YearStart/YearEnd: Year of data collection
- Location: State information 
- Topic: Disease topic 
- Question: Specific question asked
- DataValue: Numerical response for the question

## Analysis
The analysis includes:

- Exploratory data analysis: Distributions, missing values, correlations
- Data preprocessing: Encoding categorical features, handling missing data
- Visualizations: Distributions by disease topic, geographic plots
- Modeling: Built classification models (Gaussian, Logistic Regression, Random Forest, etc) to predict disease topic from input features

Key findings:
- Cancer has the most questions, needing more policy clarification 
- Identified questions related to insurance policy amounts
- Random Forest model performed best with 100% accuracy

## Usage
To run the analysis:

1. Import libraries (pandas, matplotlib, sklearn, etc)
2. Load the CDI dataset
3. Explore, preprocess and visualize the data
4. Split data into train/test sets
5. Train classification models on the data 
6. Evaluate model accuracy, f1-score, confusion matrix etc.
7. Interpret and draw insights from the models


## Future Work
Some ways to extend this analysis:

- Try neural network models like MLPs for predicting disease topics
- Add more geographic visualizations of insights
- Operationalize models through API for real-time prediction
- Expand analysis to other chronic disease datasets
