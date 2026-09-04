# Dataset

## Overview

This project uses the **Brazilian E-Commerce Public Dataset by Olist**, a real-world e-commerce dataset containing information about customers, sellers, products, payments, and order deliveries from one of Brazil's largest online marketplaces.

The dataset enables the development of a machine learning model that predicts **delivery duration** using only the information available **at the moment an order is placed**. This reflects a real-world logistics scenario where future delivery events are unknown during prediction.

Unlike traditional delivery prediction systems that output a single estimated date, this project predicts a **delivery time interval** with an associated confidence level, providing a more realistic estimate of delivery uncertainty.

---

## Dataset Source

- **Dataset:** Brazilian E-Commerce Public Dataset by Olist
- **Provider:** Olist
- **Original Source:** https://www.olist.com/
- **Kaggle:** https://www.kaggle.com/datasets/enzoschitini/brazilian-e-commerce-public-dataset-by-olist

The dataset is distributed under the **CC0: Public Domain** license, allowing free use for research, educational, and commercial purposes.

---

## About Olist

Olist is one of Brazil's largest e-commerce platforms. It connects thousands of small and medium-sized businesses with multiple online marketplaces through a unified logistics and sales infrastructure.

The dataset contains anonymized records of real customer orders, including information about:

- Customers
- Sellers
- Products
- Payments
- Shipping
- Order lifecycle
- Delivery information

---

## Why This Dataset?

Delivery time prediction depends on multiple factors rather than a single variable.

This dataset contains rich information describing both the customer and seller, along with product characteristics and purchasing behavior, making it well suited for developing predictive logistics models.

Using this dataset allows the project to model realistic delivery scenarios while remaining completely reproducible for research purposes.

---

## Features Available

The dataset contains information from several business domains, including:

### Customer Information

- Customer ID
- Customer location
- City
- State
- ZIP code

### Seller Information

- Seller ID
- Seller location
- Seller city
- Seller state

### Product Information

- Product category
- Weight
- Dimensions
- Product description length
- Product name length
- Number of product images

### Order Information

- Order ID
- Purchase timestamp
- Order approval time
- Shipping deadline
- Estimated delivery date
- Actual delivery date
- Order status

### Payment Information

- Payment method
- Number of installments
- Product price
- Freight value
- Total payment amount

### Engineered Features

The dataset also includes several engineered attributes that simplify analysis, including:

- Shipping duration
- Purchase day
- Purchase month
- Purchase year
- Purchase month/year

---

## Target Variable

The primary prediction target used in this project is:

**Shipping Duration**

This represents the total delivery time between order placement and successful customer delivery.

The target is later transformed into prediction intervals to estimate both:

- Expected delivery duration
- Prediction uncertainty

---

## Dataset Characteristics

- Real-world e-commerce transactions
- Multiple interconnected business entities
- Rich temporal information
- Geographic information
- Product metadata
- Payment information
- Delivery lifecycle events

These characteristics make the dataset suitable for machine learning, feature engineering, statistical analysis, and uncertainty-aware prediction.

---

## Project Usage

This dataset serves as the foundation for the complete machine learning pipeline:

1. Data exploration
2. Data preprocessing
3. Feature engineering
4. Model training
5. Prediction interval estimation
6. Performance evaluation
7. Interactive prediction application

---

## Citation

If you use this dataset in academic or research work, please cite the original Olist dataset and acknowledge the creators who made the data publicly available.

---

## License

**CC0: Public Domain**

The dataset is publicly available and can be freely used under the Creative Commons CC0 License.