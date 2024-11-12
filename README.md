# Customer Orders Dataset Analysis

This repository provides a sample dataset of customer orders and includes queries for analyzing customer purchasing behaviors. Each query addresses a specific scenario, showcasing data filtering, grouping, joining, deduplication, sorting, and aggregation.

## Dataset Structure
The dataset consists of customer order records with the following columns:
| Column      | Data Type | Description                                         |
|-------------|-----------|-----------------------------------------------------|
| customer_id | int       | Unique ID for each customer                         |
| name        | chararray | Name of the customer                                |
| age         | int       | Age of the customer                                 |
| location    | chararray | Location of the customer                            |
| order_id    | int       | Unique order ID                                     |
| order_date  | chararray | Date the order was placed (YYYY-MM-DD)              |
| amount      | float     | Order amount in dollars                             |

## Analysis Scenarios and Queries

### 1. Filtering Customers by Age
 **Scenario:** Analyze customers who are adults (age 18 and above).
 
 **Query:** Load the dataset and filter out customers with age < 18.
 
 ![Example Image](filtering.png)

 ### 2.Grouping by Customer and Calculating Total Sales
   **Scenario:** Calculate the total order amount for each customer.

   **Query:** Group the data by customer_id and calculate the total sales (sum of amount) for each customer.

   ![Example Image](filtering.png)
 
 
   
