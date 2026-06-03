# capstone_ALMA
Port Congestion Classification
Overview

This project uses Machine Learning and Neural Networks to classify port congestion levels based on shipping and port operation data. The objective is to identify whether congestion is Low, Medium, or High, helping improve supply chain planning and logistics management.

Dataset

The project uses the port_congestion.csv dataset.

The original congestion index was transformed into three congestion categories:

Low Congestion
Medium Congestion
High Congestion

The dataset contains a mixture of numerical and categorical features related to port activities and shipping operations.

Technologies Used
Python
Pandas
NumPy
Scikit-Learn
TensorFlow / Keras
Matplotlib
Seaborn
Machine Learning Models

The following machine learning algorithms were implemented:

Logistic Regression
Random Forest
K-Nearest Neighbors (KNN)

A Neural Network model was also developed using TensorFlow.

Data Preparation

Before training:

Categorical variables were encoded.
Features were standardized when necessary.
The dataset was divided into training and testing sets.
The target variable was converted into congestion categories.
Model Performance
Model	F1-Score
Random Forest	0.960
Logistic Regression	0.945
Neural Network	0.932
KNN	0.922

The Random Forest model achieved the best overall performance.

Project Structure
project/
│
├── port_congestion.csv
├── capstone.ipynb
├── README.md
└── report.pdf
Key Findings
Port congestion levels can be predicted with high accuracy using machine learning techniques.
Random Forest provided the most reliable results among all tested models.
Proper data preprocessing significantly improved model performance.
Neural Networks performed well but did not outperform Random Forest on this dataset.
Future Improvements
Use larger real-world port datasets.
Add more supply chain indicators.
Deploy the model as a web application.
Integrate real-time shipping and port data.
Author

Alma
Machine Learning & Neural Network Project
Supply Chain Analytics and Port Congestion Classification Project.
