# MetroPT-3 Failure Prediction Project

## Overview
This project focuses on developing and evaluating machine learning models for predicting failures in metro train operations using the MetroPT-3 dataset. The dataset contains readings from critical parameters within a compressor's Air Production Unit (APU), including pressure, temperature, motor current, and air intake valves.

## Dataset Description
- **Name**: MetroPT-3
- **Size**: 1,516,948 instances
- **Features**: 15 parameters
- **Characteristics**: Tabular, Multivariate, Time-Series data
- **Target Variable**: Binary classification (0: normal operation, 1: failure)

## Project Structure
1. **Exploratory Data Analysis**
   - Correlation analysis
   - Outlier detection
   - Feature distribution analysis

2. **Data Preprocessing**
   - Removal of unnecessary columns
   - Timestamp formatting
   - Label data creation
   - Subsampling for balanced dataset
   - Outlier removal

3. **Feature Selection**
   - Lasso regularization
   - Correlation coefficient analysis
   - Bidirectional elimination

4. **Models Implemented**
   - Traditional Machine Learning:
     - Linear Regression
     - Naive Bayes
     - K-Nearest Neighbors (KNN)
     - Random Forest
     - Support Vector Machine (SVM)
   - Advanced Models:
     - XGBoost
     - Extreme Learning Machine (ELM)
     - Neural Network
     - Ensemble Method

## Results
| Model                     | Precision | Recall | F1-Score |
|--------------------------|-----------|---------|-----------|
| Linear Regression        | 0.98      | 0.98    | 0.98      |
| Naive-Bayes             | 0.95      | 0.95    | 0.95      |
| KNN                      | 0.99      | 0.99    | 0.99      |
| SVM                      | 0.99      | 0.99    | 0.99      |
| Random Forest           | 1.00      | 1.00    | 1.00      |
| XGBoost                 | 1.00      | 1.00    | 1.00      |
| Extreme Learning Machine | 1.00      | 1.00    | 1.00      |
| Neural Network          | 1.00      | 1.00    | 1.00      |
| Ensemble Method         | 1.00      | 1.00    | 1.00      |

## Key Findings
- Dataset exhibits high linearity in feature relationships
- Strong performance across multiple models indicates robust pattern recognition
- Preprocessing steps (scaling and feature selection) significantly improved model performance
- Advanced models (XGBoost, ELM, Neural Network) achieved perfect accuracy
- Ensemble method combining top models showed excellent stability and performance

## Installation
1. Clone the repository:
```bash
git clone https://github.com/harveyphm/MetroPT-3-Anomaly-Detection.git
```