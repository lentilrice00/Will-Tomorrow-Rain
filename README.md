# **Introduction**
Ever wonder if you need to carry umbrella tomorrow? This project compares three Machine Learning Models: k-Nearest Neighbor Classifier, Random Forest Classifier, and Artificial Neural Network.

The study is based on following steps:
# Getting started with packages and data
1. Understanding of the problem: The project aims to compare different models for next day rainfall prediction.
2. Conversion of problem to AI task: The problem is Classification based problem where the goal is to classify instances based on their likelihood of rainfall
3. Data Acquisition: The data used in the project is acquired from https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package
# Preprocessing:
1. Data description: Statistical descriptions such as mean, standard deviation, min, max, and median of variables will be analyzed to understand the trend of the data.
2. Data Cleaning: Removal of missing data
3. Feature Engineering: The date data will be converted to seasonal information to feed more information, thus enhancing prediction accuracy of the models
4. Handling Text Data and Categorical Attributes: Categorical data, such as seasonal info, wind direction, rain today and rain tomorrow will be encoded using techniques like LabelEncoding and OneHotEncoding
5. Data splitting: Splitting entire data into train and test.
**NOTE: Always split before scale to ensure no information leakage**
6. Visualization and Correlation: Visualization and Correlation of rainfall tomorrow with other features
7. Data scaling: Scaling of the data using RobustScaler
# Model Development
1. Model Selection: KNN Classifier, RF Classifier, ANN
2. Loss function: Categorical Cross-Entropy
3. Model Training and Tuning: K-Fold Cross validation and Random Search for Hyperparameter Tuning for kNN and RF, while fixed parameters for ANN
# Performance Comparison and Analysis
1. Comparison of best models
2. Outcome Interpretation
# **Conclusion**
The study shown that RF and ANN shown similar precision, recall, and f1-score, demonstrating both models could predict equally if rainfall will occur tomorrow. However, the study could have been benefited with additional computational resources. For instance, no hyperparameter tuning for ANN or shap analysis was performed in this study because of lack of computational resources.

# **Visualization of correlation of data features**
![download](https://github.com/user-attachments/assets/96726540-233f-422f-bdad-a0b54fd02e50)

Fig: Demonstrating the correlation among some features used in the data
