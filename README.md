📊 Customer Segmentation & Behavioral Clustering — Olist E-commerce Dataset
📌 Project Overview
This project develops a data-driven customer segmentation framework using transactional e-commerce data from Olist (Brazil). The objective is to identify distinct customer groups based on purchasing behavior and translate insights into targeted marketing and retention strategies.
The analysis integrates multiple relational datasets and applies unsupervised learning techniques to uncover customer heterogeneity.
🎯 Business Objective
Identify high-value and repeat customers
Detect at-risk and low-engagement users
Support targeted marketing and retention strategy
Improve revenue optimization through segmentation
📂 Dataset
100K+ orders
Multiple relational tables (customers, orders, payments, reviews, geolocation)
1M+ geolocation records
Data was merged and transformed to create customer-level behavioral profiles.
🛠 Feature Engineering
Engineered customer-level features including:
Recency (days since last purchase)
Frequency (number of purchases)
Monetary value (total spend)
Payment behavior
Review sentiment proxy
Geographic attributes
Applied scaling and dimensionality reduction (PCA) for clustering stability.
🤖 Modeling Approach
Unsupervised learning techniques:
K-Means Clustering
DBSCAN
HDBSCAN
Principal Component Analysis (PCA)
Model performance evaluated using:
Silhouette Score (Best: 0.43)
Cluster interpretability
Business coherence
📈 Key Findings
Identified distinct customer segments:
High-value loyal customers
Price-sensitive repeat buyers
Low-engagement / one-time purchasers
At-risk customers
Clear behavioral differences were observed across spending patterns, purchase frequency, and recency.
💡 Business Impact
Segmentation insights support:
Targeted retention campaigns
Personalized promotions
Resource allocation toward high-LTV segments
Early detection of churn-risk customers
🧠 Skills Demonstrated
SQL-style relational data integration
Advanced feature engineering
Unsupervised machine learning
Dimensionality reduction
Model evaluation
Business translation of analytics
🚀 Future Improvements
Incorporate supervised churn prediction
Estimate customer lifetime value (CLV)
Apply Bayesian clustering methods
Deploy segmentation as a production pipeline
