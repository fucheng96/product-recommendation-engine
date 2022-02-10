## Table of Contents

1. [Overview](#Overview)
2. [Installation](#Installation)
3. [Folder Directory](#Folder-Directory)
4. [Acknowledgements](#Acknowledgements)

## Overview

The main objective of this project is to create recommendation engine to recommend products to customers on the Brazilian E-Commerce platform [Olist](https://olist.com/pt-br/) using Collaborative Filtering. This is crucial to increase average spend of the customers and drive sales for the sellers and Olist itself.

The dataset contains information of 100k orders from 2016 to 2018 such as order status, price, payment and freight performance to customer location, product attributes, etc.

More details can be found in the [Jupyter Notebook here](https://github.com/fucheng96/product-recommendation-engine/blob/main/product-recommendation-engine.ipynb).

## Installation

Clone this git repository to your local workspace.

`https://github.com/fucheng96/product-recommendation-engine.git`

## Folder Directory

- [data](https://github.com/fucheng96/product-recommendation-engine/tree/main/data)<br>
  Consists of Olist's public dataset downloaded from Kaggle and an Excel table that maps Brazilian state abbreviation to its full name. 
   - olist_customers_dataset.csv
   - olist_order_items_dataset.csv
   - olist_order_reviews_dataset.csv
   - olist_orders_dataset.csv
   - olist_products_dataset.csv
   - product_category_name_translation.csv
   - customer_state_name.xlsx
- [product-recommendation-engine.ipynb](https://github.com/fucheng96/product-recommendation-engine/blob/main/product-recommendation-engine.ipynb)<br>
  This notebook contains all the details of this project from Problem Statement and Strategy to Exploratory Data Analysis. 
- [customer_matrix.pkl](https://github.com/fucheng96/product-recommendation-engine/blob/main/customer_matrix.pkl)<br>
  A pickled customer matrix as a result of the Funk SVD algorithm.
- [product_matrix.pkl](https://github.com/fucheng96/product-recommendation-engine/blob/main/product_matrix.pkl)<br>
  A pickled product matrix as a result of the Funk SVD algorithm.

## Acknowledgements

Kudos to Olist for releasing a [public dataset](https://www.kaggle.com/olistbr/brazilian-ecommerce). It contains multiple datasets an e-commerce platform may store, which provide many exciting areas to explore apart from NLP such as sales prediction, customer segmentation etc.
