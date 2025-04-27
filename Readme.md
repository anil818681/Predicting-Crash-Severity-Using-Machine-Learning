# Data-Driven Approach to Predicting Crash Severity Using Machine Learning Techniques

## Overview
This project explores the application of machine learning (ML) models to predict the severity of road traffic accidents. With the rise in global road traffic accidents, which cause significant human and economic losses, the goal is to develop predictive tools that can assist in mitigating crash severity. Various machine learning algorithms, including Linear Regression, Random Forest, Gradient Boosting, and Convolutional Neural Networks (CNN), are employed to analyze crash data and identify key factors contributing to crash severity. This research aims to find the most accurate predictive model and understand the factors that drive accident severity.

## Table of Contents
1. [Introduction](#introduction)
2. [Background Information](#background-information)
3. [Problem Definition](#problem-definition)
4. [Literature Review](#literature-review)
5. [Roles and Responsibilities](#roles-and-responsibilities)
6. [Data Preprocessing and Feature Engineering](#data-preprocessing-and-feature-engineering)
7. [Model Selection and Evaluation](#model-selection-and-evaluation)
8. [Results and Discussion](#results-and-discussion)
9. [Conclusion](#conclusion)

## Introduction
Road traffic accidents are a leading cause of global fatalities and injuries. In this study, machine learning is applied to predict car crash severity based on a variety of influencing factors, such as driver behavior, weather conditions, vehicle features, and road infrastructure. Through an extensive dataset, this research evaluates the effectiveness of different machine learning models and their ability to predict the severity of crashes.

## Background Information
### The Global Challenge of Road Safety
According to the World Health Organization (WHO), nearly 1.3 million people die annually due to road traffic accidents, with millions more suffering from injuries. The economic losses from these accidents are staggering, making it crucial to find methods for predicting and mitigating crash severity.

### The Complexity of Crash Severity Prediction
Crash severity is influenced by numerous factors such as road conditions, vehicle characteristics, and driver behavior. These complex interactions make it difficult to predict crash outcomes using traditional statistical models. Machine learning offers an advanced approach to analyze and uncover hidden patterns within the data.

### The Role of Machine Learning
Machine learning can handle large datasets, discover nonlinear relationships, and provide predictive insights into crash severity. The use of ML models can improve road safety policies, assist in risk assessment for insurance companies, and aid in designing preventive measures such as speed limits and traffic signage.

## Problem Definition
This project seeks to address two primary issues:
1. **Prediction of Crash Severity:** Develop machine learning models that can predict the severity of a car crash based on various factors.
2. **Identification of Key Predictors:** Identify the most significant variables that influence crash severity to aid in designing targeted safety measures.

## Literature Review
The field of crash severity prediction using machine learning has seen various studies, each contributing valuable insights into the effectiveness of different algorithms. Some key studies reviewed include:
- **Transparent Deep Learning Framework (Sattar et al., 2023):** Proposed a deep learning model for crash severity prediction with a focus on interpretability.
- **Deep Learning Framework for Injury Severity (Ma et al., 2021):** Highlighted the superiority of deep learning models in capturing complex relationships in crash data.
- **Crash Severity Analysis of Rear-End Crashes (Ahmadi et al., 2020):** Focused on classification techniques to identify factors influencing crash severity.

## Roles and Responsibilities
The project involved a collaborative effort from four team members, each taking on specific responsibilities:
1. **Pranathi Chirumamilla:** Led the project, managed overall progress, and handled dataset preprocessing and Linear Regression model implementation.
2. **Jahnavi Gandu:** Focused on developing Random Forest and Gradient Boosting models, along with contributing to the report and presentation.
3. **Sadwika Poondla:** Responsible for report writing, CNN model development, and performance evaluation using metrics like MSE and R².
4. **Sravanthi Kasimsetty:** Developed scripts for exploratory data analysis (EDA), created visualizations, and worked on feature engineering.

## Data Preprocessing and Feature Engineering
Data preprocessing involved cleaning and normalizing the dataset to ensure consistency and scalability across the models. Feature selection techniques were applied to identify the most relevant predictors of crash severity, and various exploratory data analysis methods (such as heatmaps and pair plots) were used to uncover patterns in the data.

## Model Selection and Evaluation
The project employed several machine learning algorithms:
- **Linear Regression:** A simple yet effective model for predicting continuous outcomes.
- **Random Forest:** An ensemble learning method that handles both regression and classification tasks.
- **Gradient Boosting:** A boosting technique that iteratively improves model performance.
- **Convolutional Neural Networks (CNN):** While typically used for image data, CNN was explored for its potential in learning from tabular data.

Model performance was evaluated using Mean Squared Error (MSE) and R-squared (R²) scores, with the aim of finding the model that best predicts crash severity.

## Results and Discussion
Initial results indicate that traditional machine learning models, such as Linear Regression and Random Forest, outperformed CNN in terms of predictive accuracy. Random Forest, in particular, showed the best performance across the board, with higher R² values and lower MSE. The study suggests that while CNN has potential in handling complex datasets, it may not be the best fit for tabular data like crash severity datasets.

## Conclusion
This research demonstrates the potential of machine learning to predict car crash severity with high accuracy. By comparing various machine learning models, it identifies Random Forest and Gradient Boosting as the most effective algorithms for this task. The findings can inform road safety policy, insurance risk assessment, and the design of safety interventions. This study contributes to the broader field of road safety and highlights the importance of data-driven approaches to tackling global traffic safety challenges.
