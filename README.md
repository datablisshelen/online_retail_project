# Online Retail Customer Segmentation and Sales Analysis

This project analyses an online retail transactional dataset to understand customer behaviour, identify revenue drivers and create actionable customer segments. The work includes data cleaning, exploratory analysis, segmentation, and recommendations to support marketing, retention and commercial decision-making.


# Project Overview

The Online Retail dataset contains over half a million transactions from a UK-based retailer. The project investigates overall sales patterns, customer purchasing behaviour, product trends and frequency-based insights. It then applies segmentation logic to group customers into meaningful behavioural categories.


# Deliverables include:

Cleaned dataset
Exploratory data analysis
Customer segmentation files
Sales and product performance summaries
Documentation and a well-structured project layout


# Repository Structure

online_retail_project/
├── data/
│   ├── raw/
│   │   └── online_retail_raw_dataset.csv
│   └── processed/
│       ├── online_retail_cleaned_final_v2.csv
│       ├── Customer_Segments_with_basket_value_heavy_multibuy.csv
│       ├── high_value_customers.csv
│       ├── regular_buyers.csv
│       ├── steady_buyers.csv
│       ├── at_risk_accounts.csv
│       ├── dormant_customers.csv
│       └── top_customers.csv
│
├── notebooks/
│   └── Helen_Bliss_Online_Retail.ipynb
│
├── reports/
│   └── HelenBliss_Online_Retail_Transaction_Analysis_Project_Documentation.pdf
│
├── scripts/
│   └── (placeholder for future Python scripts)
│
├── tests/
│   └── (placeholder for future test files)
│
└── README.md


# Data Cleaning and Preparation

The dataset includes issues such as:
Missing customer IDs
Negative quantities from cancelled orders
Duplicate stock codes
Large outlier purchases
A mix of numeric and text-based datatypes

# Key cleaning steps completed:

Converted datatypes for Quantity, UnitPrice, InvoiceDate and CustomerID
Removed extreme outlier transactions (such as Invoice 581483)
Handled negative quantities
Added fields such as SalesTotal, BasketValue and time-based columns
Ensured dataset consistency and accuracy
The cleaned file is stored in data/processed/online_retail_cleaned_final_v2.csv

# Exploratory Data Analysis

Analysis covered:
Global and UK revenue trends
Average revenue over time
Quantity versus revenue
Seasonality and monthly behaviour
Basket order values

# Main insights:

Revenue shows strong seasonal peaks, particularly toward the end of the year
The UK represents the majority of sales
Larger basket sizes tend to create significantly higher revenue
Weekly purchasing behaviour is consistent and predictable
Product Analysis
Product-level analysis includes:
Top 10 products by revenue
Unit price band distributions

# Observations:

Low-priced, high-volume products drive a large proportion of revenue
Many items fall into a narrow price range, reflecting the retailer’s business model

# Customer Behaviour Analysis

The project explores customer metrics such as:
Recency
Frequency
Monetary value
Basket value
Heavy multibuy behaviour
Day-of-week preferences

# Visual outputs include:

Frequency vs order analysis
Top 10 customers by spend
Segment distribution charts
RFM comparisons

# Customer Segmentation

Using behavioural patterns, several clear customer segments were created:

1. High Value Customers: High spend and frequent purchasing	
Retention-focused activity such as early access or loyalty incentives

2. Steady Buyers:	Moderate spend with consistent transactions	
Introduce product recommendations and personalised suggestions

3. Regular Buyers:	Reasonably active but not top spenders	
Encourage loyalty sign-ups and cross-selling

4. At Risk Accounts: Previously active but show declining activity	
Win-back offers and targeted reminders

5. Dormant Customers:	No activity for a long period	
Light-touch seasonal or reactivation campaigns

6. Heavy Multibuy Customers: 	Frequently purchase in volume
Volume-based offers and bundle promotions

Each segment is exported in data/processed/.

# Key Findings and Recommendations

Retaining high value customers has a much greater impact than acquiring new ones
Increasing basket size is a strong lever for revenue growth
Seasonal behaviour should influence marketing scheduling
Dormant and at-risk customers show potential for recovery with the right incentives
Two distinct purchasing patterns exist: high-frequency/low-basket customers and low-frequency/high-basket customers

# Outputs Included

Fully cleaned dataset
Customer segmentation exports
A Jupyter notebook containing detailed analysis
Documentation in the reports folder


# Future Development

Potential areas for project expansion:
Apply clustering algorithms for automated segmentation
Build predictive models for customer churn or lifetime value
Implement dashboards in Power BI or Tableau
Add modular data-cleaning and feature-engineering scripts
Add test scripts for validation

# Author

Helen Bliss
Data Analytics and Digital Marketing
Focused on customer insights, retail analytics and data-driven decision-making.
