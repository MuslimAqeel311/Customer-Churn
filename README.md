# Customer Churn Predictive Modelling with Deep Neural Network
This project aims to predict customer churn in the telecom industry using various machine learning techniques, including Random Forest and Deep Neural Networks. The notebook guides through the entire process from data loading, cleaning, and preprocessing, to feature engineering, model building, clustering, and evaluation.

## Key Components:
# 1. Introduction
Objective: Predict customer churn in a telecom dataset using different models, including Random Forest and Deep Neural Networks.
# 2. Data Loading and Preprocessing
Loading Data: The dataset is loaded using pandas.
Data Cleaning: Handling missing values, converting categorical variables to numerical ones using techniques like one-hot encoding.
# 3. Exploratory Data Analysis (EDA)
Visualization: Various visualizations to understand the distribution of data and relationships between features.
Key Insights: Identifying significant features that influence churn.
# 4. Feature Engineering
Feature Selection: Selecting important features for the model.
New Features: Creating new features such as 'TenureGroup' and 'NumServices' to enhance the model's performance.
# 5. Clustering
Customer Segmentation: Using clustering techniques like K-Means to segment customers into different clusters based on their characteristics.
# 6. Model Building
Train-Test Split: Splitting the data into training and testing sets.
Standardization: Standardizing features for better performance of certain models.
# 7. Random Forest Regressor
Model Training: Training a Random Forest Regressor on the dataset.
Evaluation: Evaluating the model using Mean Squared Error (MSE) and R² Score.
# 8. Predictive Modelling Using Deep Neural Network
Model Architecture: Building a neural network with Keras and TensorFlow.
Training: Training the deep neural network on the training data.
Evaluation: Evaluating the model using metrics like ROC AUC Score
