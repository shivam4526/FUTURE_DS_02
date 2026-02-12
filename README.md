📊 Customer Churn & Retention Analysis Dashboard
🚀 Overview
Customer churn is one of the biggest challenges in subscription-based businesses. Acquiring new customers is significantly more expensive than retaining existing ones.
This project analyzes the Telco Customer Churn Dataset (Kaggle) to:
📉 Identify churn patterns
📈 Analyze customer lifetime trends
🔍 Detect key churn drivers
💰 Evaluate revenue impact
🎯 Provide actionable retention strategies
The final output is a retention analysis dashboard/report with business insights and recommendations.
📂 Dataset Information
Dataset: Telco Customer Churn
Source: Kaggle
🔗 https://www.kaggle.com/datasets/blastchar/telco-customer-churn
Key Features:
Customer demographics (gender, senior citizen, partner, dependents)
Services subscribed (internet, phone, streaming, etc.)
Contract type (Month-to-month, One year, Two year)
Payment method
Monthly and total charges
Tenure (customer lifetime in months)
Churn status (Yes/No)
🎯 Business Objectives
This analysis answers the following key questions:
What is the overall churn rate?
When are customers most likely to churn?
Which contract types drive higher retention?
How do pricing and billing impact churn?
What customer segments are high-risk?
How can churn be reduced strategically?
🛠 Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Plotly
Jupyter Notebook
🧹 Data Processing Steps
Converted TotalCharges to numeric
Removed missing values
Encoded Churn as binary variable
Created Customer Lifetime Value (CLV)
Performed grouping and aggregation analysis
📊 Analysis Performed
1️⃣ Churn Distribution
Overall churn rate calculation
Visual representation of churn vs retained customers
2️⃣ Tenure-Based Retention Trend
Identified higher churn during early months
Lifetime pattern analysis
3️⃣ Contract Type Impact
Month-to-month contracts show significantly higher churn
Long-term contracts increase retention
4️⃣ Payment Method Analysis
Electronic check customers show higher churn probability
5️⃣ Revenue & CLV Analysis
Higher monthly charges linked to higher churn
Long-term customers generate greater lifetime value
6️⃣ Correlation Analysis
Identified numerical relationships with churn
📈 Key Insights
Majority of churn occurs within early tenure months.
Month-to-month contract customers have the highest churn rate.
Customers using electronic check payments churn more frequently.
High monthly charges increase churn likelihood.
Long-term contracts significantly improve customer lifetime value.
💡 Actionable Recommendations
🎯 Improve Early Customer Experience
Onboarding engagement programs
First-month incentives
🎯 Promote Long-Term Contracts
Discounts for annual plans
Loyalty benefits
🎯 Target High-Risk Segments
High monthly charge + month-to-month contract customers
Personalized retention offers
🎯 Improve Payment Experience
Encourage auto-payment enrollment
Simplify electronic billing process
📊 Key KPIs Delivered
Overall Churn Rate
Total Customers
Total Churned Customers
Average Tenure
Average Monthly Revenue
Customer Lifetime Value (CLV)
📁 Project Structure
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── churn_analysis.ipynb
├── churn_analysis.py
├── README.md
▶️ How to Run the Project
1️⃣ Install Dependencies
pip install pandas numpy matplotlib seaborn plotly
2️⃣ Download Dataset
Download from Kaggle and place in project folder.
3️⃣ Run Notebook or Script
python churn_analysis.py
Or open Jupyter Notebook and run all cells.
🔥 Future Enhancements
Machine Learning churn prediction model
Feature importance ranking
SHAP explainability
Cohort analysis
Survival analysis
Streamlit interactive dashboard
Automated retention scoring system
👨‍💻 Author
Shivam Kumar
Data Analyst | AI & ML Enthusiast
📌 Project Impact
This project demonstrates:
Business problem understanding
Customer behavior analytics
Revenue impact analysis
Data-driven decision making
Client-ready reporting skills
