 It is focused on analyzing the "Bank Marketing" dataset from the UCI Machine Learning Repository. The primary tasks include data fetching, preprocessing, and applying a Decision Tree Classifier.You can view the Colab notebook [here.](https://colab.research.google.com/drive/1cbZfV6uPjzvE9fL0dMRpWP2MZ_TgpmiH#scrollTo=Sju21vF2XcN4)

### Overview of the Script:

1. **Data Fetching**: 
   - The script fetches the "Bank Marketing" dataset using the `ucimlrepo` library.
   - It separates the dataset into features (`X`) and target (`y`).

2. **Data Preprocessing**:
   - Categorical features are encoded using one-hot encoding.
   - The script handles any potential encoding for binary classification in the target variable.

3. **Model Training**:
   - The dataset is split into training and testing sets using an 80-20 ratio.
   - A Decision Tree Classifier is trained on the data.

4. **Model Evaluation**:
   - The script evaluates the model's performance using accuracy, classification report, and confusion matrix metrics.


# Bank Marketing Data Analysis and Decision Tree Classifier

This repository contains a Python script that analyzes the "Bank Marketing" dataset from the UCI Machine Learning Repository. The primary goal is to predict whether a client will subscribe to a term deposit based on various features using a Decision Tree Classifier.

## Overview

The analysis includes:

- Fetching and preprocessing data from the UCI Repository.
- Encoding categorical variables for machine learning models.
- Training a Decision Tree Classifier.
- Evaluating the model's performance using accuracy and other metrics.

## Dataset

The dataset used in this analysis is the "Bank Marketing" dataset, which includes:

- **Features**: Attributes related to the client, including age, job, marital status, education, and more.
- **Target**: Whether the client subscribed to a term deposit (binary outcome).

## Script Details

### 1. Data Fetching and Preparation

The script uses the `ucimlrepo` library to fetch the dataset. Features and target variables are separated, and categorical features are encoded using one-hot encoding.

### 2. Model Training

- The data is split into training and testing sets (80%-20%).
- A Decision Tree Classifier is trained on the training set.

### 3. Model Evaluation

- The model's accuracy is evaluated on the test set.
- A classification report and confusion matrix are generated to assess the model's performance.

### 4. Visualization (if applicable)

- Decision Tree visualization (optional): The decision tree can be visualized using the `plot_tree` function from `sklearn`.



## Results

The model's performance will be displayed in the terminal, including accuracy, confusion matrix, and a detailed classification report.

