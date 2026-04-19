👇

💳 Credit Card Fraud Detection
A machine learning project focused on detecting fraudulent credit card transactions using data analysis, preprocessing, and modeling techniques.

📌 Project Overview
Credit card fraud causes billions of dollars in losses every year. This project aims to:


Analyze real-world transaction data


Perform data cleaning and preprocessing


Conduct exploratory data analysis (EDA)


Prepare data for fraud detection models


This repository currently focuses on CE-1: Exploratory Data Analysis & Data Cleaning Pipeline.

📂 Project Structure
fraud-detection/│├── fraud_detection/│   └── CE1_IEEE_Fraud_Detection_FINAL.ipynb│├── .gitignore└── README.md

📊 Dataset


Dataset Name: IEEE-CIS Fraud Detection Dataset


Source: Kaggle Competition


Provider: Vesta Corporation


⚠️ Note: Large dataset files (like train_transaction.csv) are not included in this repository due to size limitations.
👉 You can download the dataset from Kaggle:
https://www.kaggle.com/competitions/ieee-fraud-detection

⚙️ Technologies Used


Python 🐍


Pandas


NumPy


Matplotlib


Seaborn


SciPy


Jupyter Notebook



🔍 Key Steps Performed
1. Data Loading


Imported dataset and inspected structure


2. Data Cleaning


Handling missing values


Removing duplicates


Fixing data types


3. Exploratory Data Analysis (EDA)


Distribution analysis


Correlation analysis


Fraud vs non-fraud comparison


4. Feature Understanding


Identified important variables


Detected anomalies and patterns



📈 Sample Code
import pandas as pdimport numpy as npimport matplotlib.pyplot as pltimport seaborn as snsdf = pd.read_csv("train_transaction.csv")df.head()

🚀 How to Run


Clone the repository


git clone https://github.com/your-username/fraud-detection.git


Navigate to the project folder


cd fraud-detection


Open Jupyter Notebook


jupyter notebook


Run the notebook file



🎯 Future Work


Build machine learning models (Logistic Regression, Random Forest, XGBoost)


Handle class imbalance


Model evaluation using precision, recall, F1-score





