# E-Commerce Customer Churn Analysis

# Project Overview

This project focuses on analyzing customer churn behavior in an e-commerce platform using Exploratory Data Analysis (EDA). The main objective is to identify the key factors that influence customer churn and understand customer behavior patterns that impact retention.

The analysis uses customer transactional, behavioral, engagement, and satisfaction-related features to discover important churn indicators and provide business-driven insights.

# Objective

The main goals of this project are:

Understand customer churn behavior

Identify important churn-driving factors

Analyze customer engagement and purchasing patterns

Discover business insights for customer retention

Build a strong foundation for future churn prediction models

# Dataset Information

The dataset contains:

6000 customer records

16 columns

Numerical and categorical features

No missing values

# Features Used

Customer Information

Customer_ID

Behavioral Features

browsing_frequency_per_week

engagement_score

cart_abandonment_rate

Transactional Features

avg_order_value

total_orders

days_since_last_purchase

Customer Experience Features

satisfaction_score

product_review_score_avg

customer_support_tickets

Pricing & Loyalty Features

discount_usage_rate

price_sensitivity_index

loyalty_member

Target Variable

churned

# Project Workflow

1. Data Loading
Imported dataset using Pandas
Checked dataset structure and size

3. Data Understanding
Verified data types
Checked missing values
Reviewed statistical summary using describe()

5. Data Cleaning
Removed unnecessary column:

Customer_ID

# 7  Univariate Analysis

Analyzed individual feature distributions using:

Countplots

Histograms

Boxplots

# Main focus areas:

Customer activity

Satisfaction

Engagement

Cart abandonment

Price sensitivity

# 5  Bivariate Analysis

Compared features with churn status using:

Boxplots

Countplots

Correlation heatmap

# Key comparisons:

Satisfaction vs Churn

Engagement vs Churn

Loyalty Membership vs Churn

Cart Abandonment vs Churn

# 6  Multivariate Analysis

Analyzed relationships among multiple features using:

Scatterplots

Pairplots

Focus:

Combined customer behavior patterns

Churn-related interactions

# Key Insights
Major Churn Indicators

Customers are more likely to churn when they show:

High inactivity

Low engagement

Low satisfaction

High cart abandonment

High price sensitivity

Fewer total orders

Loyalty Impact

Loyalty members are less likely to churn compared to non-members.

Customer Experience Impact

Customers with more support issues and lower satisfaction scores show higher churn probability.

Purchasing Behavior

Frequent buyers and active customers are more likely to remain loyal to the platform.

Business Recommendations

Improve Customer Engagement

Personalized recommendations

Notifications and offers

Reward-based activities

Reduce Cart Abandonment

Simplify checkout process

Use cart reminder emails

Offer discounts for incomplete purchases

Strengthen Loyalty Programs

Reward points

Membership benefits

Exclusive offers

Re-Engage Inactive Customers

Personalized campaigns

Limited-time offers

Retention-focused communication

# Final Conclusion

The analysis reveals that customer churn is strongly connected with customer inactivity, low engagement, low satisfaction, and weak purchasing behavior. Customers who frequently abandon carts and show high price sensitivity are more likely to leave the platform.

Improving customer experience, engagement strategies, loyalty programs, and personalized retention campaigns can help businesses reduce churn and improve long-term customer retention.

# Tools & Libraries Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

# Project Type

Exploratory Data Analysis (EDA)

Customer Churn Analysis

Business Analytics

Data Science Project
