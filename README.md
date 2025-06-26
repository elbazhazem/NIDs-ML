# Intrusion Detection System (IDS) Using Machine Learning

### Project Overview

This project focuses on developing an Intrusion Detection System (IDS) utilizing machine learning techniques. The goal is to classify network traffic as either benign or other malicious types, leveraging the **LycoS-Unicas-IDS2018 dataset**, which addresses limitations in earlier IDS datasets. The project integrates advanced data preprocessing, feature engineering, and machine learning algorithms to achieve high accuracy and efficient detection rates.
### Objectives

- Preprocess and analyze the dataset to ensure data quality and consistency.
- Apply memory optimization techniques for handling large datasets.
- Use data scaling and dimensionality reduction methods to improve model performance.
- Train and evaluate various machine learning models, including Decision Trees, Random Forest, Extra Trees, and XGBoost.
- Evaluate performance using metrics like accuracy, precision, recall, F1-score, confusion matrix and ROC-AUC.

### Dataset

The **LycoS-Unicas-IDS2018 dataset** is used in this project, offering significant improvements over the widely used CIC-IDS2018 dataset. The dataset contains various attack scenarios and benign traffic, enabling robust model training and testing.

# **The Code Structure**
1. **Dataset Preparation**
   - Importing and exploring the dataset.
   - Handling missing values and data cleaning.
   - Feature engineering and dimensionality reduction.
2. **Exploratory Data Analysis (EDA)**
   - Visualizations to understand data distributions.
   - Statistical summaries and insights.
3. **Data Preprocessing**
   - Applying techniques like Random under-sampling (RU) and Stacking Feature Embeded -Principal Component Analysis (SFE-PCA).
   - **rewrite** apply balancing in two approaches: make all classes have the same number of instances(artifically balancec), handling imbalnce while maintaining the same distribution.
   - Splitting the dataset into 10 fols using K-fold cross-validation.
4. **Model Training**
   - Selecting and training machine learning models.
   - train models for both Multiclass classificaion and binary classification.
   - **rewrite** for each of Multiclass and binary class classification train the both approaches I did 
     to handle imbalance making dataset artifivally imbalanced or preserve the original distribution.
   - Hyperparameter tuning for optimal performance.
5. **Model Evaluation**
   - Performance metrics: detection rate, false alarm rate, precision, recall, and F1 score.
   - Confusion matrix and ROC-AUC analysis.
6. **Conclusion**
   - Summary of results and findings.