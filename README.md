🛍️ Customer Personality Analysis for Grocery Retail
📈 Overview
This project focuses on customer segmentation to improve campaign targeting and marketing strategies for a grocery retailer. By applying unsupervised clustering techniques to customer records, we identified distinct customer profiles based on demographics, purchase behavior, and response to promotions.

🎯 Problem Statement
The goal of this analysis is to:

Group customers into meaningful segments using clustering algorithms.

Understand purchasing patterns and promotion engagement within each segment.

Provide actionable recommendations to improve marketing efficiency and personalization.

Instead of marketing to all customers, the business can focus resources on those most likely to respond to specific campaigns.

🗂️ Dataset Information
The dataset includes demographic, transactional, and behavioral data for each customer, such as:

Customer Information:

Year of Birth

Education Level

Marital Status

Income

Household Composition

Recency of Last Purchase

Complaints History

Product Spend:

Amount spent on wine, meat, fruits, fish, sweets, and gold over the last 2 years.

Promotion Response:

Accepted Campaigns (1–5)

Overall Response

Purchase Channels:

Web, Catalog, Store Purchases

Web Visits Last Month

🧰 Tools & Libraries
Python

pandas

scikit-learn

matplotlib

seaborn

🛠️ Approach
Data Cleaning & Preprocessing

Handled missing values

Encoded categorical features

Scaled numeric variables

Created derived features (e.g., total spending)

Exploratory Data Analysis

Distribution of spending across product categories

Customer demographics breakdown

Correlation analysis

Clustering Methods

K-Means Clustering

Hierarchical Clustering (Ward linkage)

Silhouette and Elbow methods to determine optimal number of clusters

Cluster Profiling

Summarized each segment’s characteristics

Identified high-value customer groups and their behaviors

Recommendations

Tailored marketing strategies for each segment

Suggestions for targeted promotions and communication channels

📊 Results & Insights
Identified 4 customer segments with distinct purchasing behaviors and promotion responsiveness.

Highlighted a segment with high spending on premium products and frequent web purchases, ideal for targeted online campaigns.

Provided recommendations to improve campaign ROI by focusing resources on responsive customer groups.

✨ Future Work
Incorporate Recency, Frequency, Monetary (RFM) analysis.

Test additional clustering algorithms (DBSCAN, Gaussian Mixture Models).

Explore predictive modelling for campaign acceptance.

