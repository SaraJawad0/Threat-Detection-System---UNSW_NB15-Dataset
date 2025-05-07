# Threat-Detection-System--UNSW_NB15-Dataset
This is a project that aims to train a machine learning model using the UNSW_NB15 dataset for threat detection.

Dataset can be downloaded from here: https://research.unsw.edu.au/projects/unsw-nb15-dataset

# Overview

This project is about training a ML model using the UNSW_NB15-Dataset which is a dataset containing a comprehensive collection of network traffic data designed to support cybersecurity and network analysis research. This dataset includes both normal (0) and attack (1) traffic types. while doing this project, multiple challenges will be addressed such as class imbalance, missing values, categorial features, noise instances, and more.  

# Project Phases
## Step 1: Data Collection
Data will be collected into one frame to be handled.
 
## Step 2: Dataset Balancing
Dataset class imbalanced will be handled using upsampling and downsampling methods.

## Step 3: Filling Missing Values
Missing values will be handled

## Step 4: Cleaning and Adjusting the columns
Here, multiple columns will be explored and adjusted to be suited for further tasks.

## Step 5: One Hot Encoding
In this step categorial features will be handled using One Hot Encoding

## Step 6: Handling Non-Numeric Features
This part involves handling the non-numeric columns that were not handled in the previous step.

## Step 7: Noise Reduction
in this step noise was handled using Z-score to filter out data points which are introduce 'noise' to the dataset

## Step 8: Normalization:
preform normalization on the dataset using Min-Max scaling.

## Step 9: Features Selection
In this step, dimensionality reduction as preformed using PCA to filter out irrelevant columns.

## Step 10: Model Training & Testing
In this step 5 models were trained and tested. These models are Random Forest, Logistic Regression, K-Nearest Neighbors, Decision Tree, and Gradient Boosting.

## Step 11: Models Comparison
This is the last step in which we will compare the models' performance and choose the most suitable one for our project.
