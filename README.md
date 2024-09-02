# Diabetes Risk Analysis and Prediction

## Project Overview

This project focuses on analysing and predicting the risk of Type 2 diabetes based on non-invasive health and lifestyle indicators. The goal is to develop a predictive model that can identify individuals at risk of diabetes, thereby aiding in early detection and prevention efforts. This work is not only critical for public health but also demonstrates the application of data science techniques that can be leveraged across various domains.

## Business Context

Diabetes is a growing public health concern, particularly Type 2 diabetes, which is influenced by lifestyle and behavioural factors. Early detection is crucial to prevent complications and manage healthcare costs effectively. By using machine learning models, this project aims to provide a predictive tool that can help healthcare professionals identify at-risk individuals based on easily accessible data.

## Dataset

The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset/data), based on the **2015 Behavioral Risk Factor Surveillance System (BRFSS)**. The BRFSS is an annual health-related survey conducted by the CDC (US), which collects data on health risk behaviours, chronic health conditions, and the use of preventive services.

### Total Size: 
253,680 rows x 22 columns

### Key Features:
- **Demographics**: Age, Education, Income
- **Health Indicators**: BMI, Blood Pressure, Cholesterol
- **Lifestyle Factors**: Physical Activity, General Health, Difficulty Walking

### Target Variable:
A binary indicator of diabetes risk.

![image](https://github.com/user-attachments/assets/67a4a793-41c1-4bbe-86ed-2e5400205887)

## Methodology / Workflow

This project involved the following key steps:
1. **Data Cleaning**: Removal of duplicates, handling of outliers, and ensuring data integrity.
2. **Exploratory Data Analysis (EDA)**: Visualising and understanding the distribution of variables and their relationships with diabetes risk.
3. **Feature Selection**: Selecting the most relevant features based on their correlation with diabetes risk.
4. **Data Preprocessing**: Scaling features and applying SMOTE to handle class imbalance.
5. **Machine Learning Models**: Building and evaluating both baseline and optimised models using Logistic Regression (LR), Naive Bayes (NB), Decision Tree (DT), and Random Forest (RF) algorithms.
6. **Hyperparameter Tuning**: Using Randomised Search to optimise model performance.
 ![image](https://github.com/user-attachments/assets/79ff67f8-38c7-4f6a-ba38-74789048d7fb)

## Key Findings & Visualisations

- **Improved Recall/Sensitivity**: After applying SMOTE and hyperparameter tuning, the Logistic Regression model achieved the highest recall, making it highly effective for identifying at-risk individuals.
  ![image](https://github.com/user-attachments/assets/63287265-7f10-46a3-a46c-d2ee7dd90882)
  ![image](https://github.com/user-attachments/assets/a652e016-1bf3-4907-9361-68195f7786e9)

- **Balanced Performance**: The Random Forest model provided a balanced performance across several metrics, making it a strong overall model despite its longer runtime.
  ![image](https://github.com/user-attachments/assets/9ed9dafa-a8bf-4646-b155-3cd7d9bff2dc)
  ![image](https://github.com/user-attachments/assets/70dd9bd1-3857-41d9-b4f3-faa197bcfad4)


- **Feature Importance**: BMI, Age, and Income level were identified as the top three most significant predictors of diabetes risk.
  ![image](https://github.com/user-attachments/assets/30e69b9c-6b8d-4ee5-9281-fb7c6fb22044)
  ![image](https://github.com/user-attachments/assets/002aa904-c3e1-4ee8-a6d5-c9ff2c6c8a89)


## Recommendations 

Based on the findings, the optimised Logistic Regression model is recommended for scenarios where recall is prioritised, such as screening programs aiming to minimise missed diabetes cases. 

For a more balanced approach across various metrics, the Random Forest model is suggested.

## Project Significance and Transferable Skills

This project demonstrates valuable data science skills applicable across various domains:

1. **Data Preprocessing**: Techniques for handling class imbalance and preparing complex health data.
2. **Feature Selection**: Methods to identify significant predictors, applicable in various predictive scenarios.
3. **Machine Learning Model Comparison**: Approach to developing and comparing multiple models, valuable in any predictive analytics scenario.
4. **Data Visualisation**: Skills in creating informative visualisations to communicate complex health data insights.
5. **Healthcare Analytics**: Showcases an approach adaptable to analysing and predicting other health conditions.

## Improvement / Future Development 
* Feature Selection / Engineering: Reduce the number of features selected or try a different subset
* Models: Explore more advanced models / ensemble methods
* Deployment: Consider developing a real-time risk assessment tool for healthcare providers.
* Broader Application: Expand the model to predict other chronic diseases.

## Conclusion

This project showcases the application of data science and machine learning techniques to a critical public health issue. The skills demonstrated here are versatile and can be adapted to solve complex problems in various industries, highlighting my capability to turn data into actionable insights.

---

### How to Use This Repository

1. **Jupyter Notebook**: Contains the full analysis, from data cleaning to model evaluation.
2. **Dataset**: The original dataset used in this analysis.
3. **Presentation**: A PowerPoint summarising the project's objectives, methodologies, and key findings.

---
### About the Author
Emily Huang - Data Science enthusiast with a passion for turning data into actionable insights.

Feel free to connect with me via my [LinkedIn Profile](https://www.linkedin.com/in/emily-huang-3021212a)
