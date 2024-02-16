# Online Retail Data Analysis 

This project focuses on analyzing the UCI Machine Learning Repository dataset regarding online retail transactions. The dataset covers transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The primary objectives of this project are data cleaning, exploratory data analysis (EDA), and customer segmentation.

## Data Cleaning

The **[Online Retail Data Cleaning Notebook](Notebooks/Online%20Retail%20Data%20Cleaning.ipynb)** notebook addresses the crucial task of refining and preparing the dataset for analysis. Various techniques are employed to handle missing values, outliers, and inconsistencies, ensuring the creation of a clean and reliable dataset. The cleaned dataset serves as a robust foundation for subsequent data analysis and modeling tasks.

## Exploratory Data Analysis (EDA)

The **[Online Retail Exploratory Data Analysis](Notebooks/Online%20Retail%20Exploratory%20Data%20Analysis.ipynb)** notebook represents a critical phase in understanding the dataset's intricacies. Through meticulous examination and the application of statistical techniques, the notebook aims to extract meaningful patterns and correlations. The EDA phase encompasses Customer Analysis, Product Analysis, Time Analysis, and Country Analysis, providing insights into customer behavior, product dynamics, temporal trends, and country-specific insights.

## Customer Segmentation

The **Online Retail Customer Segmentation(Notebooks/Online%20Retail%20Customer%20Segmentation.ipynb)** notebook delves into uncovering latent patterns and customer segments within the dataset. By amalgamating RFM analysis and K-Means clustering, distinct customer segments are delineated based on Recency, Frequency, and Monetary Value. This phase aims to identify high-value customers and tailor strategies for optimal business outcomes.

### Dataset Overview

The dataset comprises the following key features:

- **InvoiceNo:** A unique identifier for each transaction.
- **StockCode:** Identifies each distinct product.
- **Description:** Holds the product or item name.
- **Quantity:** Represents the quantities of each product per transaction.
- **InvoiceDate:** Indicates the date and time of each transaction.
- **UnitPrice:** Denotes the unit price of each product.
- **CustomerID:** Serves as a unique identifier for each customer.
- **Country:** Indicates the country where a customer resides.
- **TotalPrice:** Represents the total monetary value of each transaction.
- **Hour:** Specific hour of the day when each transaction occurred.
- **Day:** Day of the week when each transaction took place.
- **Month:** Month when each transaction occurred.
- **IsRepeatCustomer:** Binary flag indicating repeat customers.

### Source

The dataset is sourced from the [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Online+Retail).

