Telecom Customer Churn Prediction

📌 Project Overview

This project focuses on predicting customer churn in the telecom industry using machine learning techniques. By analyzing customer data, we aim to identify patterns that indicate potential churn and help businesses implement retention strategies. Additionally, we developed an interactive dashboard using Power BI and deployed a Streamlit web application that utilizes multiple machine learning models to provide churn predictions.

📁 Project Structure

📂 Telecom-Customer-Churn
│-- 📁 data                  # Dataset and preprocessing scripts
│-- 📁 notebooks             # Jupyter notebooks for analysis
│-- 📁 models                # Trained models and scripts
│-- 📁 src                   # Source code for preprocessing, training, and evaluation
│-- 📁 deployment            # Streamlit app and deployment files
│-- 📁 dashboard             # Power BI dashboard files
│-- 📜 README.md             # Project documentation (this file)
│-- 📜 requirements.txt      # Dependencies
│-- 📜 main.py               # Main script to run the model

🚀 Installation & Setup

Clone the repository:

git clone https://github.com/your-username/telecom-churn.git

Navigate to the project directory:

cd telecom-churn

Install dependencies:

pip install -r requirements.txt

📊 Dataset Description

The dataset used in this project is derived from telecom customer records. Key attributes include:

Customer Demographics: Gender, senior citizen status, partner and dependent status.

Service Details: Type of phone service, internet service, online security, and tech support.

Account Information: Contract type, billing method, payment details, and monthly charges.

Churn Status: Indicates whether the customer has left the service (Yes/No).

🔬 Methodology

1. Data Preprocessing

Handled missing values and outliers.

Encoded categorical variables using One-Hot Encoding.

Normalized numerical features using StandardScaler.

2. Exploratory Data Analysis (EDA)

Analyzed customer behavior trends.

Visualized correlations between features and churn.

3. Model Selection & Training

We implemented 10 different machine learning models, including:

Logistic Regression

Decision Trees

Random Forest

Support Vector Machines (SVM)

Gradient Boosting (XGBoost)

Stacking Model (Combining multiple models for better performance)

For final predictions, we used an ensemble approach that selects the most repeated prediction among the models or the most common result.

4. Model Evaluation

Performance was measured using:

Best Accuracy (Stacking Model): 84.5%

Precision: 87%

Recall: 85%

ROC-AUC Score: 92%

📈 Results & Insights

Tenure and contract type are strong indicators of churn.

Customers with month-to-month contracts are more likely to churn.

High monthly charges correlate with higher churn rates.

The stacking model provided the most reliable predictions, achieving 84.5% accuracy.

🌍 Deployment & Dashboard

Streamlit Deployment: We deployed a web-based application where users can input customer details and get churn predictions based on the ensemble model.

Power BI Dashboard: An interactive dashboard was developed to visualize key insights, trends, and churn factors dynamically.
