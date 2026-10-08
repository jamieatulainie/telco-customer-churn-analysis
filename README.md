# Telco Customer Churn Analysis

## Project Overview

This project analyzes customer churn in a telecommunications company using MySQL and Power BI.

The objective is to identify customer segments with higher churn rates and understand the factors associated with customer churn.

## Tools Used

- MySQL
- Power BI
- SQL
- DAX

## Dataset

The dataset contains information about 7,043 telecommunications customers, including:

- Customer demographics
- Contract type
- Tenure
- Internet service
- Payment method
- Monthly charges
- Customer churn status

## Data Preparation

The data was imported into MySQL for data checking and analysis.

Data preparation included:

- Checking total records
- Checking missing customer IDs
- Checking blank values
- Cleaning the TotalCharges field
- Creating a cleaned TotalCharges column
- Validating the cleaned data

## Key Analysis

The analysis focused on:

1. Overall customer churn rate
2. Churn rate by contract type
3. Churn rate by customer tenure
4. Churn rate by internet service
5. Churn rate by payment method

## Key Findings

### 1. Overall Churn

- Total customers: 7,043
- Churned customers: 1,869
- Overall churn rate: 26.5%

### 2. Contract Type

Month-to-month customers had the highest churn rate at **42.7%**, compared with 11.3% for one-year contracts and 2.8% for two-year contracts.

### 3. Customer Tenure

Customers with less than 12 months of tenure had the highest churn rate at **48.3%**.

Churn rate decreased as customer tenure increased.

### 4. Internet Service

Fiber optic customers had the highest churn rate at **41.9%**, compared with 18.9% for DSL and 7.4% for customers without internet service.

### 5. Payment Method

Customers using electronic check had the highest churn rate at **45.3%**.

## Business Insights

The analysis suggests that customer churn is particularly high among:

- Month-to-month contract customers
- New customers with less than 12 months of tenure
- Fiber optic customers
- Customers using electronic check

These customer segments could be prioritized for customer retention strategies.

## Dashboard

The Power BI dashboard provides an interactive view of:

- Total customers
- Churned customers
- Overall churn rate
- Churn rate by contract
- Churn rate by tenure
- Churn rate by internet service
- Churn rate by payment method

## Project Outcome

This project demonstrates practical skills in:

- SQL data analysis
- Data cleaning
- DAX measures
- Power BI dashboard development
- Business insight generation
- Data visualization

## Note

The analysis identifies associations between customer characteristics and churn. The findings should not be interpreted as proof of causation.
