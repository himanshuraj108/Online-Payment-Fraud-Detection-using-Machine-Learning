Online Payment Fraud Detection (Machine Learning Project)
Overview

This project presents a machine learning-based fraud detection system designed to identify fraudulent financial transactions. It focuses on handling highly imbalanced datasets and improving detection performance for rare fraud cases using advanced classification techniques.

Problem Statement

Fraudulent transactions represent a very small fraction of total transactions, making them difficult to detect using standard models.

The objectives of this project are:

Accurately identify fraudulent transactions
Minimize false negatives (undetected fraud cases)
Effectively handle class imbalance
Tech Stack
Programming Language: Python
Libraries: Scikit-Learn, XGBoost, Pandas, NumPy
Visualization: Seaborn, Plotly, Matplotlib
Techniques: SMOTE (Synthetic Minority Oversampling Technique), Exploratory Data Analysis, Feature Importance
Dataset
Large-scale financial transaction dataset
Contains anonymized transaction features
Highly imbalanced with very few fraud cases
Key Features
Performed end-to-end data preprocessing and cleaning
Conducted exploratory data analysis using statistical summaries and visualizations
Handled class imbalance using SMOTE oversampling
Trained multiple models including Random Forest and XGBoost
Compared model performance using evaluation metrics suited for imbalanced data
Analyzed feature importance to identify key fraud indicators
Model Evaluation

Models were evaluated using metrics appropriate for imbalanced classification:

Precision
Recall
F1-Score
Confusion Matrix
Precision-Recall Curve

The focus was on maximizing fraud detection (recall) while maintaining strong precision.

Results
Achieved strong performance on fraud detection using ensemble models
Improved minority class prediction using SMOTE
Reduced false negatives significantly compared to baseline models
Project Structure
├── data/                # Dataset files
├── notebooks/           # Jupyter notebooks (EDA, training)
├── src/                 # Source code (preprocessing, models)
├── outputs/             # Plots and evaluation results
├── requirements.txt     # Dependencies
└── README.md
How to Run
Clone the repository
git clone https://github.com/himanshuraj108/Online-Payment-Fraud-Detection-using-Machine-Learning.git
cd fraud-detection-ml
Install dependencies
pip install -r requirements.txt
Run the notebook or scripts
jupyter notebook
Future Improvements
Deploy the model using Flask or FastAPI
Add real-time fraud detection pipeline
Perform hyperparameter tuning for further optimization
Integrate with a dashboard for visualization
