# eCommerce Transactions Dataset Analysis

## Overview
This project analyzes an eCommerce transactions dataset to extract insights, build predictive models, and perform customer segmentation. It demonstrates skills in exploratory data analysis (EDA), machine learning, and business insight generation.

## Dataset
The dataset consists of three files:
1. **Customers.csv**:
   - `CustomerID`: Unique identifier for each customer.
   - `CustomerName`: Name of the customer.
   - `Region`: Continent where the customer resides.
   - `SignupDate`: Date when the customer signed up.

2. **Products.csv**:
   - `ProductID`: Unique identifier for each product.
   - `ProductName`: Name of the product.
   - `Category`: Product category.
   - `Price`: Product price in USD.

3. **Transactions.csv**:
   - `TransactionID`: Unique identifier for each transaction.
   - `CustomerID`: ID of the customer who made the transaction.
   - `ProductID`: ID of the product sold.
   - `TransactionDate`: Date of the transaction.
   - `Quantity`: Quantity of the product purchased.
   - `TotalValue`: Total value of the transaction.
   - `Price`: Price of the product sold.

## Tasks

### Task 1: Exploratory Data Analysis (EDA)
- Perform EDA to uncover patterns and trends in the dataset.
- Derive at least 5 business insights from the analysis.
- Deliverables:
  - Jupyter Notebook/Python script for EDA.
  - PDF report summarizing the insights.

### Task 2: Lookalike Model
- Develop a model to recommend 3 similar customers based on their profile and transaction history.
- Use both customer and product information to compute similarity scores.
- Deliverables:
  - Jupyter Notebook/Python script for the model.
  - `Lookalike.csv` containing top 3 similar customers for CustomerIDs `C0001-C0020`.

### Task 3: Customer Segmentation/Clustering
- Perform customer segmentation using clustering techniques on profile and transaction data.
- Calculate metrics like the Davies-Bouldin Index and visualize the clusters.
- Deliverables:
  - Jupyter Notebook/Python script for clustering.
  - PDF report summarizing the clustering results.

## Folder Structure
```
|-- clustering/              # Scripts and results for customer segmentation.
|-- data/                    # Provided datasets (Customers.csv, Products.csv, Transactions.csv).
|-- eda/                     # Exploratory Data Analysis scripts.
|-- lookalike_model/         # Scripts and results for the lookalike model.
|-- README.md                # Project overview and instructions.
|-- requirements.txt         # List of dependencies.
```

## Setup Instructions

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/samsomsabu/eCommerce_Assignment.git
   cd eCommerce_Assignment
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebooks:**
   - Open Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
   - Navigate to the respective folders (`eda`, `lookalike_model`, `clustering`) and execute the notebooks.

## Results
### EDA
- Uncovered key trends and patterns in customer behavior, product categories, and transactions.

### Lookalike Model
- Successfully recommended similar customers for the first 20 customers.

### Customer Segmentation
- Identified clusters of customers with similar characteristics, aiding targeted marketing strategies.

## Authors
- **Samson Sabu**

