FUTURE_ML_02 — Churn Prediction System
Machine Learning Task 2 – Future Interns
It is implemented for the Future Interns – Machine Learning Internship (Task 2).
The goal of this project is to build a Customer Churn Prediction System that identifies customers who are likely to stop using a service and provide actionable business insights using Machine Learning and Power BI.
________________________________________
PROJECT OBJECTIVE
The objective of this work is to:
•	Analyze customer behavior data
•	Identify factors influencing customer churn
•	Build a classification model to predict churn probability
•	Evaluate model performance using standard metrics
•	Visualize churn drivers using an analytics dashboard
•	Provide meaningful business insights & recommendations
________________________________________
Tools & Technologies Used
•	Python (Google Colab)
•	Scikit-learn – Machine Learning
•	Pandas, NumPy – Data Processing
•	Matplotlib – Model Evaluation Visuals
•	Power BI Desktop – Dashboard Visualization
________________________________________
Dataset Overview
The dataset represents customer information from the Telecom industry.
Dataset Used:
Telco Customer Churn Dataset (Kaggle)
Important Columns:
•	customerID – Unique customer identifier
•	tenure – Number of months customer stayed
•	MonthlyCharges – Monthly billing amount
•	Contract – Contract type
•	Churn – Whether customer left (Yes / No)
________________________________________
Project Workflow
1️. Data Cleaning & Preparation
•	Loaded dataset in Google Colab
•	Handled missing values
•	Converted categorical variables using encoding
•	Prepared data for machine learning
________________________________________
2️. Feature Engineering
•	Encoded contract type, payment method, and services
•	Selected relevant features impacting churn
•	Scaled numerical variables
________________________________________
3️. Machine Learning Model
•	Split data into training and testing sets
•	Built Logistic Regression classification model
•	Trained model to predict customer churn
________________________________________
4️. Model Evaluation
Evaluated model performance using:
•	Confusion Matrix
•	Precision, Recall, F1-Score
•	ROC-AUC Curve
The model successfully identified churn patterns with reliable accuracy.
________________________________________
5️. Churn Probability Prediction
•	Generated churn probability for each customer
•	Identified high-risk customers for retention strategies
________________________________________
6️. Power BI Dashboard
Imported processed data into Power BI and created interactive visuals showing:
•	Total Customers
•	Churned Customers
•	Churn vs Non-Churn Customers
•	Churn by Contract Type
•	Monthly Charges vs Churn
•	Tenure vs Churn
•	Interactive slicers for contract analysis
________________________________________
Key Findings
•	Month-to-month contracts have the highest churn
•	Customers with higher monthly charges are more likely to churn
•	Long-tenure customers show higher loyalty
•	Early-stage customers are at higher churn risk
________________________________________
Business Insights & Recommendations
•	Encourage long-term contracts to reduce churn
•	Offer discounts for high-billing customers
•	Focus retention strategies on new customers
•	Use churn probability scores for targeted marketing
________________________________________
How to Use
🔹 Run the Churn Prediction Model
•	Open the Google Colab notebook
•	Run all cells to train and evaluate the model
🔹 View the Power BI Dashboard
•	Open the Power BI file or screenshots
•	Use slicers to explore churn patterns
________________________________________
Conclusion
This project demonstrates how Machine Learning and Data Analytics can help businesses proactively identify customer churn, understand key churn drivers, and take data-driven actions to improve customer retention.
