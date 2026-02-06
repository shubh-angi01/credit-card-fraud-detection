# Credit Card Fraud Detection using Machine Learning

##  Project Overview

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. Financial fraud poses a significant risk to organizations, and early detection helps minimize financial losses while improving customer security.

The objective of this project is to build a classification model capable of distinguishing between legitimate and fraudulent transactions using historical transaction data.


##  Features

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Handling imbalanced datasets
* Model training using classification algorithms
* Performance evaluation using standard metrics


##  Machine Learning Models Used

* Logistic Regression
* Random Forest

Random Forest was selected as the primary model due to its robustness and strong performance on structured datasets.


##  Technologies & Libraries

 Python
 Pandas
 NumPy
 Scikit-learn
 Matplotlib / Seaborn
 Jupyter Notebook
 Git/Github

 ## Dataset

 Due to file size limitations,the dataset is not included in this repository.
 Download it from :
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud


##  Workflow

1. Loaded and explored the dataset
2. Performed preprocessing and feature scaling
3. Addressed class imbalance
4. Split the dataset into training and testing sets
5. Trained classification models
6. Evaluated performance using multiple metrics


##  Model Performance

The Random Forest model demonstrated strong predictive capability on the test dataset:

*  ccuracy: 99.95%
*  recision: 0.95
*  ecall: 0.81
*  1-Score: 0.87
*  Matthews Correlation Coefficient (MCC): 0.88

The model successfully detected the majority of fraudulent transactions while maintaining a low number of misclassifications. Matthews Correlation Coefficient was used as an additional evaluation metric because it provides a balanced measure of performance for imbalanced classification problems such as fraud detection.



