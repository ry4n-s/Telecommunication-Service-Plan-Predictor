# Telecommunication Service Plan Predictor 📶👥🔍

## 🚀 Project Overview
This repository hosts a machine learning project aimed at predicting customer service plan preferences in the telecommunications industry. Using a dataset provided by a telecommunications provider, the project applies the K-Nearest Neighbors (KNN) classification algorithm to predict customer group membership based on demographic and service usage data. The goal is to classify customers into one of four service categories: Basic Service, E-Service, Plus Service, and Total Service.

## 📌 Key Features
- **Customer Demographic Data**: Leverages a dataset with features like region, age, marital status, address, income, and more.
- **Data Preprocessing**: Includes normalization of features and splitting data into training and test sets.
- **K-Nearest Neighbors Classifier**: Implementation of KNN to classify customers into different service groups.
- **Model Optimization**: Experiments with different values of K to find the most accurate predictive model.
- **Evaluation Metrics**: Uses accuracy as a metric to evaluate the performance of the KNN classifier.

## 🛠️ Built With
- Python: For data manipulation, model building, and analysis.
- Pandas & NumPy: For data handling and numerical operations.
- Scikit-Learn: For implementing the KNN algorithm and data preprocessing.
- Matplotlib: For visualizing the accuracy of different K values.

## 🎯 Application Scenarios
- **Telecommunications Marketing**: Useful for tailoring marketing strategies based on customer service plan preferences.
- **Customer Segmentation**: Helps in segmenting customers based on usage patterns and demographic data.

## 🔍 Inside the Code
- **Exploratory Data Analysis**: Initial exploration of the dataset to understand customer demographics and service preferences.
- **Feature Selection and Preprocessing**: Details on selecting relevant features and preprocessing steps like normalization.
- **KNN Model Training and Prediction**: Training the KNN model and making predictions on the test dataset.
- **Accuracy Optimization**: Finding the optimal K value for the highest classification accuracy.
