# DSW-Products-Prediction

This repository contains data and analysis related to predicting the success of products based on various features such as category, main promotion method, color, and customer ratings (stars).

## Introduction

In retail and e-commerce, understanding the factors that contribute to the success of products is crucial for making informed decisions regarding inventory management, marketing strategies, and product development. This project aims to predict the success of products using machine learning techniques based on historical data.

## Approach

1. **Data Preprocessing:**
   - Drop unnecessary columns (`item_no`) and encode categorical variables (`Category`, `main_promotion`, `Color`) into numerical values.
   - Analyze the distribution of features and explore relationships between features and the target variable (`Success_Indicator`).

2. **Feature Engineering:**
   - Convert customer ratings (`Stars`) into binary labels based on a threshold.
   - Address data imbalance in the target variable using techniques like SMOTE (Synthetic Minority Over-sampling Technique).

3. **Modeling:**
   - Train various machine learning models such as logistic regression, SVM classifier, decision trees, ensemble models, including Random Forest, to predict the success of products.

4. **Evaluation:**
   - Evaluate the performance of the models using metrics such as accuracy, precision, recall, and F1-score.

5. **Insights and Recommendations:**
   - Analyze the results and provide insights into the factors influencing product success.
   - Make recommendations for product launches based on the analysis.

## Random Forest Approach

The Random Forest classifier is utilized to predict the success of products based on historical data. Here's a summary of the process:

1. **Importing Libraries:** 
   - Necessary libraries such as pandas, scikit-learn, and RandomForestClassifier are imported.

2. **Loading Data:** 
   - The historical data is loaded into a DataFrame.

3. **Data Preprocessing:** 
   - Unnecessary columns are dropped, and categorical variables are converted into dummy variables.

4. **Splitting Data:** 
   - The data is split into training and testing sets.

5. **Model Initialization and Training:**
   - A Random Forest classifier is initialized and trained on the training data.

6. **Model Evaluation:**
   - The trained model is used to make predictions on the test set, and its accuracy is evaluated.

