# E-commerce Data Analysis
Hello! My name is Gregorio Gonzalez, and I'm a industrial engineer. 
I made this project to showcase some of my skills of SQL and Python for data analysis. The goal is to perform all data manipulation using only SQL, and use python to visualize the results.

The dataset I'll be analyzing is from Olist, a Brazilian e-commerce platform that links small businesses with larger product marketplaces. 
This dataset, published by Olist, includes 99,441 orders spanning from March 2016 to August 2018. 
The data is anonymized, meaning it doesn't include names of buyers, sellers, or products.

- In the 'Queries' folder you can find all the SQL queries used in the analysis.
- In the notebook file called "Olist_analysis.ipynb" we will have the complete project, but in the 'notebooks' folder it is divided by items.
- You can find all the documents in this [Google Drive](https://drive.google.com/drive/folders/1SbxLV-Djng8Qbxqcp2OLFPQR_yiRycxu?usp=sharing).
  
These are the different items analyzed for this project.

  1. [Number of orders](https://github.com/GregorioEG/Olist-E-Commerce-Analysis/blob/main/Notebooks/1.%20Number_of_orders.ipynb)
      - Count the number total number of daily orders.
      - Distribution of sales over the week and hours with a heatmap.
      - Geographic distribution. Top 10 cities by number of orders.
        
  2. [Order Prices](https://github.com/GregorioEG/Olist-E-Commerce-Analysis/blob/main/Notebooks/2.%20Order_prices.ipynb)
      - Average order price, min and max order price
      - Product cost and shipping cost by order
        
  3. [Product Categories](https://github.com/GregorioEG/Olist-E-Commerce-Analysis/blob/main/Notebooks/3.%20Product_categories.ipynb)
      - First 18th categories by sales
      - Sales by category summary
      - Distribution of product weight by category
        
  4. [Sales Prediction](https://github.com/GregorioEG/Olist-E-Commerce-Analysis/blob/main/Notebooks/4.%20Sales_prediction.ipynb)
      - Total sales per month for some example categories
      - Calculate the linear regresion, slope and intercept
      - Forecast for daily sales for December 2018
        
  5. [Order Reviews](https://github.com/GregorioEG/Olist-E-Commerce-Analysis/blob/main/Notebooks/5.%20Order_reviews.ipynb)
      - Distribution of sellers scores

  6. [Customer Segmentation](https://github.com/GregorioEG/Olist-E-Commerce-Analysis/blob/main/Notebooks/6.%20Customer_segmentation.ipynb)
      - Customers segmentation grouping them by recency, frecuency and monetary value. This is called RFM method
      - RFM Segmentation graph
      - Customers porpotion, one-time vs repeat customers
        
  7. [Product affinity](https://github.com/GregorioEG/Olist-E-Commerce-Analysis/blob/main/Notebooks/7.%20Product_affinity.ipynb)
      - What products are usually bought together
      - List of products that apear in more than 5 orders
      - Count the number of orders each pair of products appears
      - Graph of products frequently bought together
        
  8. [Sellers](https://github.com/GregorioEG/Olist-E-Commerce-Analysis/blob/main/Notebooks/8.%20Sellers.ipynb)
      - Average review score, total sales and number of orders by seller
      - Review scores vs Sales
      - Number of sellers by orders size
      - Seller shipping time by seller order volume
  9. [Lead Conversion](https://github.com/GregorioEG/Olist-E-Commerce-Analysis/blob/main/Notebooks/9.%20Leads.ipynb)
      - Closed leads vs leads qualified
      - Which are the largest sources of closed leads
      - LEad conversion rate by origin

[Data source: Olist E-Commerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

The Dataset has the following schema.

![db-schema](https://github.com/user-attachments/assets/e874f2ae-0cc4-4cc8-bb16-eec86b94bb04)
