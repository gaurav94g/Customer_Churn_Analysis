# Customer_Churn_Analysis
## Project Summary
This project focuses on a comprehensive analysis of bank churn data, where churn indicates customers who have left the bank. Using a sample dataset, this project aims to practice report creation and enhance data analysis skills using Power BI.

## Objectives
- Identify and understand the factors leading to customer churn.
- Derive actionable insights to help reduce the churn rate.

## Project Workflow

### 1. Data Connection
Establish a stable connection to the source of the bank churn data.

### 2. Data Preparation
Accurate analysis starts with proper data cleaning and preparation. The key steps include:

- Verifying data types and column names.
- Removing the 'Estimated Salary' column.
- Standardizing column names to start with capital letters:
  - Credit Score
  - Credit Card Status
  - Activity Status
  - Churn Status
- Adding an example column for products (e.g., Prod 1).
- Modifying values for clarity:
  - Churn Status: 1 – Churned, 0 – Not Churned
  - Activity Status: 1 – Active, 0 – Inactive
  - Credit Card Status: 1 – Owned, 0 – Not Owned
- Introducing conditional columns based on existing data:
  - Age Group (from Age)
  - Credit Scores (from Credit Score)
  - Account Balance (from Balance)

### 3. Data Modeling and Analysis
Create reference tables and develop conditional columns:

- Create a reference table from the customer data table, name it 'Age Groups', retain only the 'Age Group' column, and remove duplicates.
- Add an 'Age Group ID' conditional column to the 'Age Groups' table.
- Similarly, create reference tables for 'Account Balance' and 'Credit Scores'. Add respective IDs as conditional columns.

### 4. Creating Measures
Develop measures to enhance the analysis:

- Measure to count the number of customers.
- Measure to count the number of lost customers.
- Measure to calculate the churn rate.

### 5. Data Visualization
Visual representations provide intuitive insights. The report will include the following visuals:

**Cards**:
- Displaying the total number of customers.
- Showcasing the churn rate.
- Representing the number of lost customers.

**Charts**:
- Donut charts showing:
  - Number of customers by gender.
  - Number of customers by activity status.
  - Number of customers by credit card status.
  - Number of customers by country.
  - Number of customers by churn rate.
- Line clustered bar chart displaying customers and churn rate by age group.
- Line and stacked column chart showing customers and churn rate by credit score.
- Line chart illustrating customer losses by country.
- Stacked column chart representing customers by products.

## Conclusion
This Power BI project provides a detailed analysis of bank customer churn, identifying key factors that contribute to customer attrition. By leveraging data preparation, modeling, and visualization techniques, actionable insights can be derived to help reduce the churn rate and improve customer retention strategies.
