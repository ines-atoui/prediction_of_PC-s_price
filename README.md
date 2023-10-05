# prediction_of_PC-s_price
Welcome to the PC Price Prediction project! This repository contains a machine learning model and data pipeline designed to predict the prices of personal computers based on various features and specifications.
## Business request Overview
# PC Price Prediction Script README

This README provides an overview of the script for predicting the price of a PC based on various features. This script performs data preprocessing, exploratory data analysis, and builds machine learning models for price prediction.

## Table of Contents

- [Script Overview](#script-overview)
- [Running the Script](#running-the-script)
- [Dependencies](#dependencies)
- [Data](#data)
- [Exploration and Cleaning](#exploration-and-cleaning)
- [Formatting and Transformation](#formatting-and-transformation)
- [Modeling](#modeling)
- [Streamlit App (Not Included)](#streamlit-app-not-included)

---

## Script Overview

The script is organized into several sections:

### 1. Import Libraries
In this section, the necessary libraries are imported to perform data manipulation, visualization, and machine learning tasks.

### 2. Loading our Dataset
The dataset named "mytek.csv" is loaded into a Pandas DataFrame named "pc."

### 3. Exploration and Cleaning our Data
In this section, the script performs the following tasks:
- Provides a quick overview of the dataset with `.head()`, `.info()`, and `.describe()`.
- Identifies and handles missing values by checking for NaN values and dropping unnecessary columns.
- Cleans and preprocesses the "prix" column by removing unwanted characters and converting it to a float.
- Visualizes the data by creating bar plots for price distribution based on various features.

### 4. Formatting and Transforming Data
This section focuses on formatting and transforming the data:
- Converts categorical variables like "gamer," "grantie," and others into numerical values.
- Extracts numeric values from columns like "memoire_cache" and "ram."
- Transforms the "disque_dur" column to represent storage in gigabytes (Go).
- Extracts screen dimensions from the "resolution" column.
- Converts and prepares the data for modeling.

### 5. Modeling
In this section, the script builds and evaluates machine learning models for price prediction, including Linear Regression, K-Nearest Neighbors (KNN), Decision Tree, and Random Forest. Model performance is assessed using Mean Squared Error (MSE) and R-squared values.

### 6. Streamlit App 
The script mentions the use of Streamlit for creating a web application to predict PC prices. It includes the remaining code sections for handling the selected options, encoding them, and making a price prediction for the PC based on various features, such as brand, processor type, RAM, storage type, and more.

## Running the Script

To run the script, follow these steps:

1. Ensure you have the required libraries installed, including Pandas, NumPy, Seaborn, Matplotlib, Scikit-Learn, Yellowbrick, and Keras.
2. Download the dataset "mytek.csv" and place it in the same directory as the script.
3. Execute the script in your preferred Python environment.

## Dependencies

The script relies on the following Python libraries:

- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-Learn
- Yellowbrick
- Keras

Make sure to have these libraries installed before running the script.

## Data

The script loads the dataset named "mytek.csv" into a Pandas DataFrame called "pc." Ensure that you have this dataset available in the same directory as the script.

## Exploration and Cleaning

This section of the script performs data exploration and cleaning tasks, including identifying missing values, dropping unnecessary columns, and visualizing data distributions.

## Formatting and Transformation

The script transforms and formats the data, converting categorical variables to numerical values, extracting numeric values, and preparing the data for modeling.

## Modeling

The script builds and evaluates machine learning models for price prediction, including Linear Regression, K-Nearest Neighbors (KNN), Decision Tree, and Random Forest. Model performance is assessed using Mean Squared Error (MSE) and R-squared values.

## Streamlit App 

The script mentions the use of Streamlit for creating a web application to predict PC prices. It includes the remaining code sections for handling the selected options, encoding them, and making a price prediction for the PC based on various features, such as brand, processor type, RAM, storage type, and more.



