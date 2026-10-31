# Homework 4 — DML, DDL and Advanced SQL

This homework uses the **Olist Brazilian E-Commerce** dataset to practice PostgreSQL data loading, schema design, DML, JOINs, and analytical queries.

## Dataset

- **Source:** [Olist on Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

- **Size:** 99,441 orders; 96,096 unique buyers (based on `customer_unique_id`)

- **Tables:** customers, orders, order items, products, sellers, and order reviews

- **Download:** The notebook retrieves the original CSV files with `kagglehub.dataset_download("olistbr/brazilian-ecommerce")`.

## Repository Structure

- `hw4_olist_Kalashnikov_Mykola.ipynb` — notebook with SQL queries, outputs, and explanations

- `README.md` — project information and run instructions

- `data/olist/` — optional copy of the six source CSV files

The notebook downloads the dataset through KaggleHub even if local CSV copies are included.

## How to Run

1. Open the notebook in **Google Colab** (tested with runtime **2026.07**).

2. Select **Runtime → Restart session and run all**.

3. The notebook installs dependencies, downloads the data, starts local PostgreSQL using `pgserver==0.1.4`, and runs the SQL analysis.

Internet access is required for installation and download. No external PostgreSQL server is needed.
