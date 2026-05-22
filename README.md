# Smart Air Quality Prediction and Pollution Pattern Analysis

## Overview
This project analyzes real-world air quality data from India and predicts pollution levels using Machine Learning techniques in Python.

The system performs:
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Machine Learning Prediction
- K-Means Clustering
- PCA Visualization
- Model Deployment using Joblib

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## Machine Learning Models
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- KNN Regressor

Random Forest achieved the best performance with an R² score of approximately 0.92.

---

## Dataset
Source:
Open Government Data Platform India (data.gov.in)

Dataset includes:
- PM2.5
- PM10
- NO2
- SO2
- CO
- NH3
- OZONE

---

## Project Structure

├── 01_Data_Understanding.ipynb
├── 02_Data_Preprocessing.ipynb
├── 03_EDA_Visualization.ipynb
├── 04_MachineLearning_StatisticalAnalysis.ipynb
├── 05_Final_Prediction_System.ipynb
├── 06_Model_Deployment_Test.ipynb
├── cleaned_air_quality.csv
├── air_quality_model.pkl
├── scaler.pkl
└── README.md

---

## Key Features
- Pollution trend analysis
- Top polluted city detection
- Correlation heatmaps
- Outlier detection
- K-Means clustering
- PCA dimensionality reduction
- AQI prediction pipeline

---

## Results
- Random Forest was the best-performing model
- Strong correlation found between pollution variables
- NCR cities showed highest pollution levels
- PCA successfully visualized pollution clusters

---

## Future Improvements
- Real-time AQI API integration
- Streamlit/Flask web app deployment
- Deep Learning models
- Live pollution dashboard

---

## Author
Ujjwal Singh
M.Tech Data Science
Lovely Professional University
