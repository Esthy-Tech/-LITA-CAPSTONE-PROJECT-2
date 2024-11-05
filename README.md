# -LITA-CAPSTONE-PROJECT-2

## Customer subscription Analysis

## Project Overview
This report provides an analysis of subscription data with the following columns: CustomerID, CustomerName, Region, SubscriptionType, SubscriptionStartDate, SubscriptionEndDate, Canceled (true/false), Revenue, and SubscriptionDuration.It presents an in-depth analysis of customer subscription service data, focusing on key aspects such as customer segmentation, cancellation trends, and overall subscription patterns. The primary objective is to understand customer behavior, track the performance of different subscription types, and identify critical trends in cancellations and renewals.

Using a combination of MS Excel, SQL, and Power BI, the data was meticulously cleaned, organized, analyzed, and visualized to uncover valuable insights that can inform strategic decisions related to customer retention, subscription growth, and market segmentation.

## Data Preparation and Methodology
The data was imported from the Excel file into a data analysis tool (e.g., SQL & Power BI). The following steps were performed:

Data Cleaning: Ensured there were no missing or erroneous values in the key columns.

Data Transformation: Calculated the Subscription Duration in days based on the SubscriptionStartDate and SubscriptionEndDate.

Analysis Techniques:MS Excel was employed for preliminary analysis and data transformation. SQL queries were used to extract and aggregate relevant data from the database. Power BI was used to create detailed visualizations and track trends over time.

## Data Overview

The dataset consists of the following columns:

CustomerID: Unique identifier for each customer.

CustomerName: Name of the customer.

Region: Geographic region where the customer is located.

SubscriptionType: Type of subscription.

SubscriptionStartDate: Date when the subscription started.

SubscriptionEndDate: Date when the subscription ended.

Canceled: Indicates if the subscription was canceled (true/false).

Revenue: Total revenue generated from the subscription.

SubscriptionDuration: Duration of the subscription.

## Exploratory Data Analysis

EDA involved the exploratory of the Data to answer some questions about the data such as;
For Customer Data
Retrieve the total number of customers from each region.

Find the most popular subscription type by the number of customers.

Find customers who canceled their subscription within 6 months.

Calculate the average subscription duration for all customers.

Find customers with subscriptions longer than 12 months.

Calculate total revenue by subscription type.

Find the top 3 regions by subscription cancellations.

Find the total number of active and canceled subscriptions.

