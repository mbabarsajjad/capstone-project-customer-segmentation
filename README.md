# Udacity's Machine Learning Engineer Nanodegree Program
## Capstone Project: Create a Customer Segmentation Report for Arvato Financial Services


### Introduction
In this project ‘Create a Customer Segmentation Report for Arvato Financial Services’, the demographical data will be analysed for the customers of a mail-order company to investigate different patterns. The data is provided by the Arvato Financial Solutions. The idea will be to make different comparisons between the general population and the existing customers to increase the customer base in the future by conducting focused marketing campaigns. 

### Main Parts
1.	Get to know Data: data preprocessing will be performed here to investigate the given data and to reencode, reengineer the features which could be problematic in the later analysis.
2.	Customer Segmentation Report: both general population and customer’s  data will be used here for the application of unsupervised learning model to get the needed target population for the marketing campaigns.
3.	Supervised Learning: labelled data will be used here to apply the supervised learning model to get the predictions on future customers.
4.	Kaggle competition: in this part, the tuned supervised learning model will be applied to the test data set and the scores will be uploaded to the kaggle site to get the rating of the results

### Datasets and Inputs
1.  Udacity_AZDIAS_052018.csv: Demographics data for the general population of Germany; 891 211 persons (rows) x 366 features (columns).
2.  Udacity_CUSTOMERS_052018.csv: Demographics data for customers of a mail-order company; 191 652 persons (rows) x 369 features (columns).
3.	Udacity_MAILOUT_052018_TRAIN.csv: Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns).
4.	Udacity_MAILOUT_052018_TEST.csv: Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366 (columns).
Additionally, there are two more files to describe the features:
- DIAS Information Levels - Attributes 2017.xlsx
- DIAS Attributes - Values 2017.xlsx 

### Pre-Installation
Python 3.x , Jupyter Notebook, NumPy, Pandas, SciPy, matplotlib, seaborn, scikit-learn, xgboost
