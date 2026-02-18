Frequency-Recency Customer Analytics for Financial Insurance Services

Predicting Customer Engagement and Optimizing Marketing Campaigns with RFM Modeling, Predictive Analytics, and LLM Insights

Project Overview

This project demonstrates how to leverage Frequency-Recency (RFM) analysis to segment customers in a financial insurance context. By combining historical transaction data with predictive modeling, explainable AI, and an optional LLM-powered narrative layer, this framework enables marketing teams to:

Identify high-value customers

Detect at-risk or dormant customers

Deliver targeted re-engagement campaigns

Translate analytics into actionable insights

This is a public-facing, end-to-end portfolio project showcasing data science skills in customer intelligence and marketing analytics.

Problem Statement

Insurance companies often struggle to prioritize outreach and retention campaigns due to large volumes of customer data and varying engagement patterns.

This project aims to:

Quantify customer engagement using frequency, recency, and monetary metrics

Segment customers based on behavior and predicted engagement

Provide actionable insights for targeted campaigns and business strategy

Data

The project uses synthetic transaction data for privacy reasons. Each record contains:

Column	Description
Customer_ID	Unique identifier for each customer
Transaction_Date	Date of policy purchase, claim, or engagement
Transaction_Type	Type of activity (policy purchase, claim, etc.)
Transaction_Amount	Premium paid or claim value

Note: You can replace synthetic data with real company data if available.

Methodology
1. Feature Engineering

Recency: Days since last transaction

Frequency: Number of transactions in a given period

Monetary: Total premium paid or claims processed

Customer Lifetime Value (optional)

2. RFM Segmentation

Clusters customers into segments like High-Value, At-Risk, Dormant, New

Heatmaps and visualizations highlight engagement patterns

3. Predictive Modeling

Build LightGBM / Logistic Regression models to predict customer engagement or churn probability

Evaluate using ROC-AUC, Precision, Recall

4. Explainability

Use SHAP to identify key drivers of engagement

Understand which behaviors or attributes influence customer segments

5. Interactive Dashboard

Streamlit/Dash dashboard enables exploration of customer segments and metrics

Optional LLM integration generates natural-language insights for executives
