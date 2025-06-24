#Churn Prediction for Subscription Businesses.

This project aims to predict customer churn in a subscription-based business using machine learning. Early identification of customers likely to leave enables businesses to take proactive retention measures and improve overall customer satisfaction.
1. Project Overview
Goal
Build a predictive model that classifies whether a customer will churn based on behavioral and subscription data.
Tech Stack

Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)
Jupyter Notebook
Machine Learning (Classification)
Power BI / Data Visualization (optional)

Dataset
A custom dataset with customer attributes such as:

gender
SeniorCitizen
tenure
Contract
MonthlyCharges
etc.
Two added columns: isPremium (Yes/No), serviceCalls (float)

2. Files



File Name
Description



Churn_Prediction_for_Subscription_Businesses.ipynb
Main Jupyter notebook containing all steps of the ML pipeline


churn_prediction_dataset.csv
Dataset used for training and evaluation


README.md
Project documentation (this file)


3. Workflow
3.1 Data Preprocessing

Handling missing values
Encoding categorical variables
Feature engineering (e.g., isPremium, serviceCalls)

3.2 Exploratory Data Analysis (EDA)

Visualizing churn trends
Understanding feature distributions

3.3 Modeling

Train/Test split
Model training (Logistic Regression, Random Forest, etc.)
Evaluation with metrics (Accuracy, Precision, Recall, F1 Score)

3.4 Interpretation & Insights

Feature importance analysis
Actionable insights for business decisions

4. Model Performance
(To be updated after completing training)



Model
Accuracy
Precision
Recall
F1 Score



Random Forest
0.86
0.83
0.79
0.81


5. Key Takeaways

Long-tenure customers and premium users are less likely to churn.
Monthly charges and type of contract play a major role in customer retention.
The model can be integrated into a customer management dashboard for proactive outreach.

6. Future Improvements

Incorporate time-series or sequential behavior data.
Fine-tune with SMOTE or advanced resampling.
Deploy the model using FastAPI or Streamlit.
Dashboard creation in Power BI or Tableau.
