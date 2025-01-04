 Machine Learning for IoT Intrusion Detection

## Overview

This project implements various machine learning techniques to detect intrusions in Internet of Things (IoT) networks. The goal is to create an efficient and accurate Intrusion Detection System (IDS) that can identify malicious activities, such as unauthorized access or cyberattacks, within IoT environments. The system uses machine learning algorithms, such as Extra Trees, Random Forest, and Gradient Boosting, to analyze and classify network traffic data.




##Introduction
   Intrusion detection is a critical component of IoT security. As IoT devices proliferate, the need for robust security measures to detect and prevent cyberattacks is becoming more important. This project leverages machine learning to automate the detection of network-based intrusions in IoT systems. The focus is on analyzing network traffic to classify normal and malicious activities.

## Machine Learning Techniques

The following machine learning algorithms are used in this project for intrusion detection:

- **Random Forest Classifier**: . The random forest is used for classification as well as regression problems which helps to manage complex data that reduces overfitting and provides precise forecasts in different environments. 
- **Linear Regression Classifier**: This model uses the statistical method which helps to provide the predictive analysis, and this model predicts continuous and numeric variables. This model provides the slope straight line which shows the relationship between variables 
-  **Extra Trees Classifier**: The extra tree is the extremely randomized trees classifier which uses the decision tree classifier. This method is collective learning which aggregates the results of multiple correlated decision trees in a forest to provide the result of the classification. 
- **MLP Classifier**: The multi-layer Perceptron is based on the artificial neural network. This model is a flexible and effective approach for solving classification problems including text classification as well as picture recognition. 

## Dataset
The dataset used is a comprehensive collection of IoT network traffic data, containing over a million data points with 42 features. The dataset includes attributes such as duration, protocol type, source and destination bytes, and flags. The target variable, "xAttack," indicates whether the network activity is classified as normal or malicious.
The dataset used in this project comes from [Kaggle - IoT Intrusion Detection](https://www.kaggle.com/datasets/subhajournal/iotintrusion/data) and contains labeled network traffic data, including features like packet sizes, protocol types, and others. The dataset includes both normal and attack data.
test_data.csv  & Train_data.csv

## Project Objectives

-To preprocess and prepare IoT network intrusion datasets for analysis.

-To implement various machine learning algorithms, including Linear Regression, Random Forest, Extra Trees, and Multi-Layer Perceptron (MLP).

-To evaluate these algorithms using appropriate metrics and identify the model with the highest accura

## Implementation Details

This project involves the following steps:

- Data Preparation: Cleaning and preprocessing the dataset to handle missing values, normalize features, and encode categorical variables.

- Feature Engineering: Extracting and selecting relevant features to improve model performance.

- Model Training: Implementing and training machine learning algorithms on the processed dataset.
  
- Evaluation: Using metrics like accuracy, precision, recall, and F1-score to evaluate model performance.

  ## Libraries used
  ![image](https://github.com/user-attachments/assets/b12ca68e-125d-4b43-a9cf-bd605a4fd0db)


  ## Results

The models were evaluated on the dataset, and their accuracy was compared to identify the highest-performing algorithm. 


## Conclusion

This project highlights the importance of selecting an appropriate algorithm for IoT intrusion detection. The results indicate that Extra Tree achieved the best accuracy, showcasing its suitability for real-world applications.
