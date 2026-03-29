# Day 4 - KNN | Employee Turnover Prediction

## Overview
This project is part of my **30 Days of Machine Learning Challenge**.

In this notebook, I applied the **K-Nearest Neighbors (KNN)** algorithm to predict employee turnover and analyzed the impact of different values of K.

##Model Performance

- **Best Accuracy:** (81.85%)
- **Optimal K Value:** 8
- precision_score (87.2%)
- recall_score (71.2%)


## 📁 Dataset
- Employee Turnover Dataset

## ⚙️ Steps Performed
- Data Cleaning & Preprocessing  
- Encoding of categorical variables  
- Feature Scaling using StandardScaler  
- Train-Test Split  
- Model Training using KNN  
- Hyperparameter tuning (K value selection)  
- Model Evaluation  

## 📈 Key Insights
- KNN is highly sensitive to feature scaling  
- Best performance achieved at **K = 8**  
- Lower K values led to overfitting, while higher values caused underfitting  
- Performance depends on distance-based similarity
  
## Conclusion
The KNN model achieved its best performance at **K = 8**, demonstrating the importance of selecting an optimal number of neighbors. Proper scaling significantly improved the model's performance.
