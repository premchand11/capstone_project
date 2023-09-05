# capstone_project
Prediction using ML Algorithms
#Overview
This repository contains the code and data for a machine learning project aimed at building a predictive model for Cantone_pro, a hypothetical business or product. The goal of this project is to develop a model that can predict a target variable (in this case, 'pred') based on various features provided in the dataset.

#Dataset
We used two datasets for this project:

Train_Data.csv: This dataset contains the training data, which includes multiple features (e.g., 'pc', 'ld', 'm0', 'm1', etc.) and the target variable 'pred.' The 'pred' variable represents the binary classification target we aim to predict.

Test_Data.csv: This dataset contains the test data, which is used to evaluate the performance of our predictive model.

#Data Preprocessing
Before building the predictive model, we performed essential data preprocessing steps:

#Handling Missing Values: We identified missing values in the datasets and filled them using the median value for each respective feature.

#Label Encoding: We used Label Encoding to convert categorical variables ('pc' and 'ma') into numerical format for compatibility with machine learning algorithms.

#Exploratory Data Analysis
We conducted an Exploratory Data Analysis (EDA) to gain insights into the data, including:

#Data Visualization: We created visualizations, such as correlation matrices and heatmaps, to identify relationships between features.
Model Building
We built two machine learning models for this project:

#K-Nearest Neighbors (KNN) Classifier: We trained a KNN classifier on the training data and evaluated its performance using accuracy and F1-score metrics. The trained KNN model was used to make predictions on the test dataset.

#Multinomial Naive Bayes Classifier: We also trained a Multinomial Naive Bayes classifier on the training data and evaluated its performance using accuracy and F1-score metrics.

#Model Evaluation
We assessed the performance of both models using common evaluation metrics, including accuracy and F1-score. Additionally, we visualized the confusion matrices to understand the model's classification performance.

#Repository Structure
README.md: This file, providing an overview of the project.
1.Train_Data.csv: The training dataset.

2.Test_Data.csv: The test dataset.

3.Capstone.ipynb: The Jupyter Notebook containing the code for data loading, preprocessing, model building, and evaluation.

4.data.csv: The CSV file containing predictions from the KNN model on the test dataset.

5.dataNB.csv: Placeholder for predictions from the Multinomial Naive Bayes model.

#Usage
If you wish to run this project locally, you can follow the code provided in the Cantone_pro.ipynb Jupyter Notebook. Ensure you have the required Python libraries installed.

#Conclusion
This machine learning project showcases the process of building and evaluating predictive models for classification tasks. The models developed here can be used as a foundation for predicting the target variable 'pred' for new data points.
[Train_Data (1).csv](https://github.com/premchand11/capstone_project/files/12523509/Train_Data.1.csv)
[data.csv](https://github.com/premchand11/capstone_project/files/12523508/data.csv)
[dataNB.csv](https://github.com/premchand11/capstone_project/files/12523501/dataNB.csv)
[Test_Data (1).csv](https://github.com/premchand11/capstone_project/files/12523516/Test_Data.1.csv)

