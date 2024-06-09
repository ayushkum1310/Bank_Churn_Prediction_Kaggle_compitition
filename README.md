

# Bank Customer Churn Prediction

This repository contains a comprehensive notebook for predicting bank customer churn using various machine learning algorithms. The project covers data preprocessing, feature engineering, model training, hyperparameter optimization, and final model evaluation using a voting classifier.

## Table of Contents
1. [Introduction](#introduction)
2. [Import Libraries](#import-libraries)
3. [Read Dataset](#read-dataset)
4. [Missing & Duplicate Values](#missing--duplicate-values)
    - [Dropping Columns](#dropping-columns)
    - [Merging Datasets](#merging-datasets)
    - [Handling Missing Values](#handling-missing-values)
    - [Removing Duplicates](#removing-duplicates)
5. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
6. [Correlation Analysis](#correlation-analysis)
7. [Feature Engineering](#feature-engineering)
8. [Data Pipeline](#data-pipeline)
    - [Creating X and y](#creating-x-and-y)
    - [Main Pipeline](#main-pipeline)
9. [Model Training and Hyperparameter Tuning](#model-training-and-hyperparameter-tuning)
    - [Random Forest](#random-forest)
    - [CatBoost](#catboost)
    - [LightGBM](#lightgbm)
    - [XGBoost](#xgboost)
10. [Final Model with Voting](#final-model-with-voting)
11. [Generate Predictions and Create Submission File](#generate-predictions-and-create-submission-file)

## Introduction
This notebook aims to provide a clear and detailed workflow for predicting bank customer churn. The dataset contains various attributes related to bank customers and whether they have churned or not.

## Import Libraries
Importing necessary libraries for data processing, visualization, and model training.

## Read Dataset
Loading the datasets required for the analysis.

## Missing & Duplicate Values
### Dropping Columns
Dropping irrelevant columns to simplify the dataset.

### Merging Datasets
Combining multiple datasets to form a single comprehensive dataset.

### Handling Missing Values
Identifying and handling missing values in the dataset.

### Removing Duplicates
Removing duplicate rows to ensure data quality.

## Exploratory Data Analysis (EDA)
Performing initial analysis to understand the distribution and characteristics of the data.

## Correlation Analysis
Analyzing the correlation between different features to understand relationships within the data.

## Feature Engineering
Creating new features to enhance model performance. This includes transforming and combining existing features in meaningful ways.

## Data Pipeline
### Creating X and y
Defining the feature matrix (X) and the target variable (y).

### Main Pipeline
Setting up preprocessing steps for numerical and categorical data, and creating a complete data pipeline.

## Model Training and Hyperparameter Tuning
### Random Forest
Using Random Forest algorithm for classification and optimizing its hyperparameters.

### CatBoost
Applying CatBoost classifier and tuning its parameters for better performance.

### LightGBM
Implementing LightGBM classifier with hyperparameter tuning.

### XGBoost
Training XGBoost classifier and optimizing its parameters.

## Final Model with Voting
Combining the best models using a voting classifier to improve overall prediction performance.

## Generate Predictions and Create Submission File
Using the final model to generate predictions on the test set and creating a submission file for evaluation.

---

### Regards
**Ayush Kumar**  
Data Scientist

---

