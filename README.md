Customer Data Analysis for Business Insights is a Python-based project that cleans, processes, and analyzes retail customer and transaction data to generate actionable business insights. Using Pandas and NumPy, the project performs RFM (Recency, Frequency, Monetary) analysis to segment customers into categories such as Champions, Loyal, At-Risk, and Lost. Visualizations with Matplotlib and Seaborn highlight customer behavior, revenue contribution, and top-performing segments, enabling targeted marketing, improved customer retention, and data-driven business decisions for a mid-sized retail company.

The project uses a synthetic dataset of 23,050 transactions from 1,000 unique customers, split into two datasets:

1. Customer Master Data
   
| Column Name   | Description                                  |
| ------------- | -------------------------------------------- |
| CustomerID    | Unique identifier for each customer          |
| Name          | Customer's full name                         |
| Email         | Customer's email ID                          |
| Gender        | Male, Female, or Not Disclosed               |
| Age           | Customer's age (18–75)                       |
| City          | Customer's city (Indian metro/tier-2 cities) |
| MaritalStatus | Single, Married, Divorced, Widowed           |
| NumChildren   | Number of children in household              |
| JoinDate      | Customer registration date                   |

2. Transaction Data
   
| Column Name       | Description                   |
| ----------------- | ----------------------------- |
| CustomerID        | Links to Customer Master Data |
| TransactionDate   | Date of transaction           |
| TransactionAmount | Amount spent (₹)              |

**RFM Analysis**
RFM (Recency, Frequency, Monetary) is used to segment customers based on:
| Metric    | Meaning                           |
| --------- | --------------------------------- |
| Recency   | How recently a customer purchased |
| Frequency | How often a customer purchases    |
| Monetary  | How much a customer spends        |

**Key Goals Achieved**

Identified high-value, loyal, and at-risk customers

Improved data quality by cleaning and validating datasets

Enabled targeted marketing and customer retention strategies

Generated visual insights to support business decisions



Applied RFM analysis for actionable segmentation



