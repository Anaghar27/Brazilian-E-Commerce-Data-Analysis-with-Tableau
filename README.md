# 🇧🇷 Brazilian E-Commerce Data Analysis & Visualization

This project explores Brazil’s largest e-commerce dataset through advanced data visualization using Tableau. The dataset, contains detailed records of orders, products, sellers, payments, customer reviews, and geographical data.

## 📁 Repository Contents

- **Data Files**:
  - `olist_customers_dataset.csv`
  - `olist_geolocation_dataset.csv`
  - `olist_order_items_dataset.csv`
  - `olist_order_payments_dataset.csv`
  - `olist_order_reviews_dataset.csv`
  - `olist_orders_dataset.csv`
  - `olist_products_dataset.csv`
  - `olist_sellers_dataset.csv`
  - `product_category_name_translation.csv`

- **Dashboard**:
  - `Payment_across_Geo_Locations.twbx`: Tableau workbook that presents interactive visualizations on payment behavior across geographic regions.

## 📊 Dataset Overview

This dataset captures over 100,000 orders between 2016 and 2018 and includes:

| Dataset                          | Description                                                  |
|----------------------------------|--------------------------------------------------------------|
| `customers`                      | Customer location and metadata                              |
| `geolocation`                    | Zip code-based geolocation coordinates                      |
| `order_items`                    | Product-level data per order                                |
| `order_payments`                 | Payment installments and types                              |
| `order_reviews`                  | Customer feedback and review scores                         |
| `orders`                         | Order-level metadata including status and timestamps        |
| `products`                       | Product metadata and categories                             |
| `sellers`                        | Seller information and locations                            |
| `product_category_name_translation` | English translation of product categories               |

## 📌 Key Insights from Tableau Dashboard

The **"Payment Across Geo-Locations"** dashboard uncovers spatial and behavioral trends in payment types and order distribution:

### 🔹 Geographic Payment Trends
- **Southeast Region (São Paulo, Rio de Janeiro)** dominates in total transaction volume.
- **North and Northeast** regions show lower transaction counts but relatively higher reliance on installment payments.

### 🔹 Payment Type Analysis
- **Credit Card** is the most frequently used method, accounting for a majority of total orders.
- **Boleto (bank slip)** and **voucher** usage is higher in less urbanized areas.

### 🔹 Installment Patterns
- Customers in urban regions typically choose **3–6 installment plans**, showing financial planning behavior.
- **Single installment** purchases are common in high-income zones and for low-ticket items.

### 🔹 Order Distribution
- Order density closely follows population density, with clear clustering in metropolitan areas.
- The use of **geolocation coordinates** enables granular mapping of transactions down to the zip code level.

## 🚀 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/brazilian-ecommerce-dashboard.git

2. Open the Tableau workbook using:
- Tableau Desktop or Tableau Public
- File: Payment_across_Geo_Locations.twbx

3. Interact with filters to explore:
- Payment type by region
- Installment usage patterns
- Zip code-level transaction heatmaps

## 🌐 Data Source
This dataset was sourced from Kaggle:
👉 [Brazilian E-Commerce Public Dataset by Olist]([https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce])
