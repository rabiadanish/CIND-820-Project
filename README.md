# Housing Pricing Prediction 

Housing prices are rising in recent years due to emerging inflation rates, it is more important than ever for people to make educated choices when it comes to real estate investments. Our research uses the available "Housing Prices Dataset" for Boston to determine future prices based on the available features which will enable people to make reliable decisions. The dataset consists of various features related to the properties, including price, area, number of bedrooms, bathrooms, stories, and other factors that may influence housing prices. The objective of this project is to develop accurate prediction models that can assist in estimating housing prices.

## Overview of the Dataset

The housing pricing dataset used in this project is sourced from Kaggle, a well-known platform for data science and machine learning. The dataset contains information about housing attributes such as area, number of bedrooms, bathrooms, stories, and other relevant features. The dataset is publicly available and can be accessed at Kaggle Housing Prices Dataset.

## Project Stages

#### Research: 
Conduct background research on housing pricing prediction, exploring relevant literature, and understanding the methodologies employed in similar projects.

#### Data Collection: 
Download the housing pricing dataset from Kaggle and document the source and collection process.

#### Data Preparation: 
The dataset is preprocessed by checking for missing values and duplicates. In this case, the data does not contain any missing values or duplicates. Additionally, feature selection and encoding of categorical variables are performed to ensure that the data is in a suitable format for further analysis.

#### Data Analysis: 
Exploratory data analysis (EDA) is conducted to gain valuable insights into the dataset, identify patterns, and understand the relationships between features and the target variable. Correlation analysis is performed to examine the relationships among various attributes of houses, identify highly correlated features, and evaluate their impact on housing prices. This analysis helps in uncovering key factors that influence the pricing of houses.

#### Model Selection: 
Machine learning techniques linear regression, decision tree regression, and Random Forest is used to develop predictive models for housing price estimation.

#### Model Training:
The prepared dataset is used to train the models using three machine learning algorithms (Linear Regression, Decision Tree, and Random Forest). The 10-fold cross-validation technique is employed to capture the underlying linear relationship between the features and the target variable, ensuring robust model evaluation and performance estimation.

#### Model Evaluation: 
Evaluate the trained models using commonly used evaluation metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R2 coefficient to assess their performance and accuracy in predicting housing prices.

#### Results Interpretation: 
The linear regression model performs the best among the three models, providing relatively lower prediction errors and a higher R-squared coefficient. The decision tree and random forest models exhibit higher errors and lower R-squared coefficients, indicating poorer performance compared to linear regression. However, it's important to note that the high MAE, MSE, and RMSE values are primarily due to the larger scale of the target variable "price" (in millions), and are not necessarily indicative of poor model performance.

## 🔗 Links to Repository Content
This repository includes the following files and directories:

#### [Dataset](https://github.com/rabiadanish/CIND-820-Project/tree/main/Dataset/)
Folder containing the housing prices dataset obtained from Kaggle.
#### [Reports](https://github.com/rabiadanish/CIND-820-Project/tree/main/Reports/) 
Folder containing Abstract, Literature review, Project report, and Project presentation.
#### [Coding](https://github.com/rabiadanish/CIND-820-Project/tree/main/Coding/) 
Folder containing Google Colab ipynb python notebooks for Exploratory data analysis, Data Visualization, and Machine learning Models.
#### [README.md](https://github.com/rabiadanish/CIND-820-Project/blob/main/README.md/) 
This file provides an overview of the project, its stages, and the content of the repository.


