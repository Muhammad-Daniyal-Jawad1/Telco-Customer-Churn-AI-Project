# Telco Customer Churn Prediction

## Project Overview
This project aims to predict customer churn in a telecom company using data analysis and machine learning techniques. The project is divided into several steps, including data exploration, preprocessing, customer segmentation, feature selection, and model training.

## Made by:
- Muhammad Daniyal Jawad
- Ahmed Shaheer
- Sarmad Siddique

## Steps and Methodologies

### 1. Data Exploration and Preprocessing
- **Loading the Dataset**: The dataset is loaded using pandas.
- **Initial Exploration**: Basic exploration is conducted to understand the structure and summary statistics of the data.
- **Data Cleaning and Preprocessing**: The data is cleaned, missing values are handled, and necessary transformations are performed.

### 2. Customer Segmentation
- **Feature Encoding**: Categorical features are encoded to numerical values using LabelEncoder.
- **Optimal Number of Clusters**: The Elbow Method and Silhouette Score are used to determine the optimal number of clusters.
- **K-Means Clustering**: K-Means clustering is performed to segment customers into distinct groups.

### 3. Feature Selection
- **Mutual Information**: Feature selection is conducted using mutual information to identify the most informative features for predicting customer churn.

### 4. Model Training
- **Training Models**: Various machine learning models are trained and evaluated to predict customer churn.

## How to Run
1. Load the dataset using pandas.
2. Perform data cleaning and preprocessing.
3. Encode categorical features.
4. Determine the optimal number of clusters and perform K-Means clustering.
5. Select important features using mutual information.
6. Train and evaluate machine learning models.

## Conclusion
The project successfully segments customers and identifies key features for predicting churn, aiding in targeted marketing and retention strategies.
