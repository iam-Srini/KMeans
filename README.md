# Customer Segmentation Using K-Means Clustering in Retail Data

## Project Overview

This project involves using K-Means clustering to segment customers based on their purchasing behavior from an online retail dataset. The goal is to identify distinct customer groups to create targeted marketing strategies and enhance customer engagement.

## Data Description

- **Dataset**: Online retail transaction data.
- **Key Features**: `CustomerID`, `UnitPrice`, `Quantity`, `InvoiceDate`.

## Process

1. **Data Cleaning**:
   - Handled missing values.
   - Calculated `TotalSales` from `UnitPrice` and `Quantity`.

2. **Feature Engineering**:
   - Created features: `TotalContribution`, `Frequency`, and `Since_Last_Visit`.
   - Applied log transformation to address skewed data.
   - Standardized features for consistency.

3. **Clustering Analysis**:
   - Applied K-Means clustering with 5 clusters.
   - Used the Elbow Method to determine the optimal number of clusters.

4. **Results**:
   - Identified three main customer groups:
     - **High-Value Customers**: High spending and frequent visits.
     - **Low-Value Customers**: Low engagement and spending.
     - **Moderately Active Customers**: Moderate engagement and recent activity.

## Skills Demonstrated

- Data Cleaning and Transformation
- Feature Engineering
- Clustering Analysis
- Data Visualization
- Insight Generation
