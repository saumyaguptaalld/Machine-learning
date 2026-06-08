# Machine Learning Projects Portfolio
This repository contains a collection of machine learning and data analysis projects implemented in Python using Jupyter Notebooks. The projects cover classification, exploratory data analysis, regression, and unsupervised learning techniques.

## Repository Structure

├── CreditWise_Loan_Approval_System.ipynb
├── CreditWise_Read_Me.pdf
├── CreditWise_loan_approval_data.csv


├── Exploratory data analysis and visualization.ipynb
├── LAHD_Affordable_Housing_Projects_List__2003_to_Present_.csv
├── Restaurant_and_Market_Health_Inspections.csv

├── Supervised learning using linear regression.ipynb

└── unsupervised clustering (KMeans + PCA) using Python.ipynb

# Project 1: CreditWise Loan Approval System

## Overview
CreditWise is a machine learning-based loan approval prediction system developed for a hypothetical financial institution, SecureTrust Bank. The objective is to automate loan approval decisions for home loan and personal loan applications while balancing business growth and financial risk.
### Business Challenges
1. Good customers may be rejected, leading to loss of business.
   * Goal: Minimize False Negatives
   * Focus Metric: Recall
2. High-risk customers may be approved, leading to financial losses.
   * Goal: Minimize False Positives
   * Focus Metric: Precision
### Dataset
* CreditWise_loan_approval_data.csv
### Techniques Used
* Missing value imputation
* Exploratory Data Analysis (EDA)
* Feature engineering
* One-Hot Encoding
* Label Encoding
* Feature scaling
* Train-Test Split
### Machine Learning Models
* Logistic Regression
* K-Nearest Neighbors (KNN)
* Naive Bayes
### Results
#### Baseline Dataset (28 Features)
Best Model:
* Naive Bayes
* Precision: 80.35%
#### Feature-Engineered Dataset (35 Features)
Best Model:
* Logistic Regression
Performance Improvements:
* Recall improved by approximately 7%
* Precision maintained at approximately 78%
### Files
* CreditWise_Loan_Approval_System.ipynb
* CreditWise_Read_Me.pdf
* CreditWise_loan_approval_data.csv

########################################################################################
########################################################################################

# Project 2: Exploratory Data Analysis and Visualization

## Overview
This project demonstrates exploratory data analysis techniques using real-world datasets. Various visualization techniques are used to understand data distributions, trends, relationships, and potential data quality issues.
### Datasets
1. LAHD Affordable Housing Projects Dataset
   * LAHD_Affordable_Housing_Projects_List__2003_to_Present_.csv
2. Restaurant and Market Health Inspections Dataset
   * Restaurant_and_Market_Health_Inspections.csv
### Analysis Performed
* Data cleaning
* Missing value analysis
* Descriptive statistics
* Distribution analysis
* Correlation analysis
* Data visualization
### Visualization Techniques
* Histograms
* Count Plots
* Box Plots
* Scatter Plots
* Heatmaps
* Bar Charts
### Files
* Exploratory data analysis and visualization.ipynb
* LAHD_Affordable_Housing_Projects_List__2003_to_Present_.csv
* Restaurant_and_Market_Health_Inspections.csv

########################################################################################
########################################################################################


# Project 3: Supervised Learning Using Linear Regression
## Overview
This project demonstrates the implementation of Linear Regression for predictive modeling. The notebook covers the complete machine learning workflow from preprocessing to model evaluation.
### Topics Covered
* Data preprocessing
* Feature selection
* Model training
* Prediction
* Performance evaluation
### Evaluation Metrics
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score
### Skills Demonstrated
* Supervised Learning
* Regression Analysis
* Data Preprocessing
* Model Evaluation
### Files
* Supervised learning using linear regression.ipynb

#############################################################################################
#############################################################################################

# Project 4: Unsupervised Clustering Using K-Means and PCA

## Overview
This project explores unsupervised learning techniques for identifying hidden patterns and structures within datasets.
### Techniques Used
#### K-Means Clustering
* Cluster formation
* Centroid optimization
* Cluster visualization
#### Principal Component Analysis (PCA)
* Dimensionality reduction
* Feature compression
* Data visualization
### Analysis Performed
* Data preprocessing
* Feature scaling
* Determining optimal number of clusters
* Cluster visualization
* PCA-based dimensionality reduction
### Skills Demonstrated
* Unsupervised Learning
* Clustering
* Dimensionality Reduction
* Data Visualization
### Files
* unsupervised clustering (KMeans + PCA) using Python.ipynb
# Technologies Used
* Python
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
# Learning Outcomes
Through these projects, the following machine learning concepts were explored:
* Data Cleaning and Preprocessing
* Exploratory Data Analysis
* Feature Engineering
* Classification
* Regression
* Clustering
* Dimensionality Reduction
* Model Evaluation
* Data Visualization
