# Summary
Developed unsupervised and supervised machine learning models to predict customer segmentation based on consumption habits using an E-commerce dataset from an actual UK retailer that contains 541,909 transactions made by 4339 customers

## Database
The E-commerce dataset is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail
### Content of 8 variables 
- InvoiceNo: Invoice number. A 6-digit integral number uniquely assigned to each transaction. InvoiceNo starts with letter 'C' indicates a cancellation.
- StockCode: Product code. A 5-digit integral number uniquely assigned to each distinct product.
- Description: Description of product.
- Quantity: The quantities of each product (item) per transaction. Numeric.
- InvoiceDate: Invoice Date and time. Day and time when each transaction was generated.
- UnitPrice: Product price per unit in sterling.
- CustomerID: Customer number. A 5-digit integral number uniquely assigned to each customer.
- Country: Name of the country where each customer resides.

## Data Preparation
1. Remove missing values
2. Delete canceled orders

## Product Categories
Converted product description to categorical variables, and grouped products using K-Means Clustering

## Customer Categories
Modified data and performed K-means clustering on the first 6 principal component score vectors to group customers

## Classification of customer segments
Used Random Forest and Support Vector Machines to classify customers in different clusters
