
# Olist E-Commerce Project

## Project Overview

This project aims to analyze key performance indicators (KPIs) related to the Olist E-commerce dataset. The dataset provides comprehensive insights into customer behavior, order timelines, and reviews. Various tools such as Excel, Power BI, Tableau, and MySQL were used to process and visualize the data.

---
## Google Drive 
[Olist eCommerce Drive](https://drive.google.com/drive/u/1/folders/1SN7gVIBWpI0Hu4GBcB8uSz-Pw3xzpSvK)
## Key Performance Indicators (KPIs)

### 1. **Weekday Vs Weekend Payment Statistics**
   - **Description**: Analyze the payment patterns based on the `order_purchase_timestamp`. This metric compares orders placed on weekdays versus weekends to identify trends in customer purchase behavior.
   - **Data Column**: `order_purchase_timestamp`

### 2. **Number of Orders with Review Score 5 and Payment Type as Credit Card**
   - **Description**: Filter orders with the highest review score of 5, and where the payment type is 'credit card'.
   - **Data Columns**: `review_score`, `payment_type`

### 3. **Average Number of Days for Order Delivery for Pet Shop Category**
   - **Description**: Calculate the average time taken to deliver orders in the `pet_shop` category by analyzing the difference between `order_delivered_customer_date` and `order_purchase_timestamp`.
   - **Data Columns**: `order_delivered_customer_date`, `order_purchase_timestamp`

### 4. **Average Price and Payment Values from Customers of São Paulo City**
   - **Description**: Compute the average product price and total payment values for customers located in São Paulo.
   - **Data Columns**: `price`, `payment_value`, `customer_city`

### 5. **Relationship Between Shipping Days and Review Scores**
   - **Description**: Analyze the relationship between shipping days (`order_delivered_customer_date` - `order_purchase_timestamp`) and the review scores provided by customers.
   - **Data Columns**: `order_delivered_customer_date`, `order_purchase_timestamp`, `review_score`
---

## Tools Used

1. **Excel**: For preliminary data cleaning and analysis.
2. **Power BI**: Used to create interactive visualizations for exploring KPIs.
3. **Tableau**: Data visualization to explore trends and relationships.
4. **MySQL**: For querying and validating data, especially large datasets.
5. **PowerPoint**: Final presentation summarizing key findings and insights.

---

## Challenges Faced

- **Large Dataset**: The dataset was extensive, making the import process into MySQL difficult due to memory and size limitations.
- **CSV Import Issues**: Faced numerous challenges while importing the dataset into MySQL, including dealing with encoding errors, column misalignment, and data inconsistencies.

---

## Conclusion

This analysis provides a detailed look at customer purchasing behaviors, review score trends, and delivery performance. By leveraging multiple data analysis tools, the project delivers actionable insights for the Olist E-commerce platform.
