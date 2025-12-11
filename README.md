Telecom Customer Churn Prediction

End-to-End Machine Learning Project | Jupyter Notebook

Predicting whether a customer will leave a telecom company (churn) is one of the most important problems in the telecom industry.
This project builds a complete machine learning pipeline to analyze customer behavior and accurately predict churn.

🚀 Project Overview

Customer churn happens when customers stop using a company’s service.
Telecom companies lose millions every year due to sudden customer churn — predicting it early allows companies to:

Retain high-value customers

Improve service experience

Reduce business losses

Build targeted retention campaigns

In this project, we use real-world telecom customer data to:

✔ Understand why customers leave
✔ Build ML models to predict churn
✔ Identify the most important features
✔ Generate actionable insights for business teams

📊 Dataset Information

Dataset: Telco Customer Churn
Source: IBM (Public Dataset)
Rows: 7,043 customers
Columns: 21 features (services, charges, contract, demographics, churn label)

Download/Load Link:
https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv

🧹 Data Cleaning & Preprocessing

Performed the following steps:

Convert TotalCharges from string → numeric

Fix empty and missing values

Drop non-essential fields (customerID)

Encode categorical data (Label Encoding & One-Hot)

Scale numeric features

Train–Test Split (80/20)

🔍 Exploratory Data Analysis (EDA)

Visualized insights include:

Churn Rate Distribution

Tenure vs Churn → Short-tenure customers churn the most

Contract Type vs Churn → Month-to-month contracts have highest churn

Monthly Charges vs Churn → High-paying customers churn more

Senior Citizens Churn More

These insights help build better business strategies.

🤖 Machine Learning Models Used

Trained multiple models to compare performance:

Model	Accuracy	Notes
Logistic Regression	Good baseline	Fast & interpretable
Random Forest	High accuracy	Best feature importance
XGBoost	Highest accuracy	Handles imbalance well
📈 Model Evaluation Metrics

Each model is evaluated using:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

ROC-AUC Curve

⭐ Best Performing Model

XGBoost performed the best with the highest accuracy and balanced recall, making it the final selected model.

🔑 Feature Importance (Key Drivers of Churn)

Top factors causing churn:

Contract type

Monthly charges

Tenure

Online security / tech support

Payment method

These are the most powerful predictors of churn.

🔮 Predicting a New Customer

The notebook includes an example where you input a new customer's details and the model outputs:

✔ Will the customer churn?
✔ Confidence level

💾 Model Export

Saved the trained model as:

churn_model.pkl


This can be used directly in:

Streamlit apps

Flask / FastAPI deployment

Power BI ML integration

Web dashboards

🏗 Project Structure
📁 telecom-churn-prediction
 ├── telecom_churn.ipynb
 ├── churn_model.pkl
 ├── README.md
 └── requirements.txt

🧠 Tech Stack Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

XGBoost

Jupyter Notebook / Deepnote

📘 How to Run the Project

Clone the repository

Install dependencies

Open the .ipynb in Jupyter, Deepnote, or Colab

Run all cells

📝 Conclusion

This project demonstrates:

Full ML lifecycle (EDA → Modeling → Evaluation)

Clear understanding of customer churn behavior

Business insights telecom companies can apply

Deployment-ready ML model

It is a strong portfolio project for:

Data Analyst

Data Scientist

ML Engineer

Business Analyst



Just tell me!

Do you like this personality?
