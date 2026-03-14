# Customer Segmentation using RFM Analysis

# Overview

This project performs Customer Segmentation using RFM (Recency, Frequency, Monetary) Analysis to identify different groups of customers based on their purchasing behavior.

RFM analysis helps businesses understand:

# Recency – How recently a customer made a purchase

# Frequency – How often a customer makes purchases

# Monetary – How much money a customer spends

By analyzing these three metrics, companies can create targeted marketing strategies and improve customer retention.

# Project Objectives

The main goals of this project are:

Analyze customer purchasing behavior

Calculate RFM metrics

Segment customers into meaningful groups

Identify high-value customers

Provide insights for business decision making

# Dataset

The dataset contains transaction records with the following fields:

CustomerID

InvoiceNo

InvoiceDate

Quantity

UnitPrice

TotalPrice

Each row represents a purchase transaction made by a customer.

# RFM Metrics Calculation
1. Recency

Measures how recently a customer made their last purchase.

Recency = Current Date - Last Purchase Date

Lower recency value → more recent customer.

2. Frequency

Number of transactions made by a customer.

Frequency = Total number of purchases

Higher frequency → more loyal customer.

3. Monetary

Total amount spent by a customer.

Monetary = Sum of all purchase amounts

Higher monetary value → higher spending customer.

# Segmentation Process

Data Cleaning

Feature Engineering

Calculate RFM values

Assign RFM scores using quantiles

Combine scores to create RFM segments

Example segment groups:

Segment	Description
Champions	Recent, frequent, high spenders
Loyal Customers	Frequent buyers
Potential Loyalists	Recent customers with moderate spending
At Risk	Haven't purchased recently
Lost Customers	Long time since last purchase

# Technologies Used

Python

Pandas

NumPy

Matplotlib / Seaborn

Jupyter Notebook

Project Workflow
Data Collection
      ↓
Data Cleaning
      ↓
Feature Engineering
      ↓
RFM Calculation
      ↓
Customer Scoring
      ↓
Customer Segmentation
      ↓
Visualization & Insights
Sample Insights

Identified top high-value customers

Detected customers at risk of churn

Found potential loyal customers for targeted campaigns

Improved understanding of customer purchasing patterns

How to Run the Project

Clone the repository

git clone https://github.com/yourusername/rfm-customer-segmentation.git

Install required libraries

pip install pandas numpy matplotlib seaborn

Run the notebook

jupyter notebook
Project Structure
rfm-segmentation/
│
├── data/
│   └── dataset.csv
│
├── notebooks/
│   └── rfm_analysis.ipynb
│
├── images/
│   └── rfm_visualizations.png
│
└── README.md
Future Improvements

Apply Machine Learning clustering (K-Means)

Build an interactive dashboard

Automate segmentation pipeline

Deploy as a web application

Author

Tuhin Alam Bijoy

CSE Student | Data Science & Machine Learning Enthusiast
