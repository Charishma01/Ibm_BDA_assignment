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

   ![Example Image](grouping.png)

  ### 3.Joining Orders with Customer Information
  
   **Scenario:** Combine customer details with order information for a detailed view.
   
   **Query:** Join the dataset with itself on customer_id to display order_id, name, location, and order_date.

   ![Example Image](joining.png)

  ### 4.Removing Duplicate Orders
  
   **Scenario:** Remove duplicate records due to potential system errors.

   **Query:** Load the dataset and remove any duplicate entries based on order_id.

   ![Example Image](duplicate_removal.png)

  ### 5.Sorting Orders by Amount
  
   **Scenario:** Identify the highest value orders.

   **Query:** Load the dataset, sort by amount in descending order, and display the top 3 highest orders.

   ![Example Image](sorting.png)

  ### 6.Aggregating and Filtering Data (Total Purchases Above $500)

   **Scenario:** Identify customers whose total purchases exceed $500.

   **Query:** Group orders by customer_id, calculate the total purchase amount, and filter for customers who spent more than $500.

    ![Example Image](Aggregation.png).

  

   
 
 
   
