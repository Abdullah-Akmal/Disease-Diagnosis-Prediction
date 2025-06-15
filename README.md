# Disease Diagnosis Prediction

## Description  
This notebook aims to build a predictive model to estimate the likelihood of diabetes using the PIMA Indian Diabetes dataset. By analyzing key patient health metrics, we use machine learning algorithms to classify individuals as diabetic or non-diabetic. The goal is to support early disease detection and assist healthcare professionals in identifying high-risk individuals for timely intervention and prevention.  
**[Dataset Source – Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)**

## Objectives  
- Analyze health-related data to identify patterns associated with diabetes  
- Build classification models using machine learning  
- Evaluate model performance with appropriate metrics  
- Deliver insights that can aid in preventive healthcare

## Methodology / Steps  
- Import libraries for data analysis, visualization, preprocessing, and modeling  
- Load and inspect the dataset (shape, preview, missing values, duplicates)  
- Conduct Exploratory Data Analysis (EDA) including histograms and boxplots  
- Visualize correlations via heatmaps to inform feature selection  
- Select and scale features using `SelectKBest` and `StandardScaler`  
- Split data into training and testing sets  
- Train and evaluate multiple ML models: SVM, Gradient Boosting, and MLP Classifier  
- Analyze results using F1-score, classification report, and ROC-AUC curves  
- Summarize key healthcare insights based on model outcomes

## Tools & Libraries Used  
Python, pandas, NumPy, seaborn, matplotlib, scikit-learn (SVM, GradientBoostingClassifier, MLPClassifier, SelectKBest, StandardScaler, classification_report, roc_auc_score, f1_score), train_test_split
