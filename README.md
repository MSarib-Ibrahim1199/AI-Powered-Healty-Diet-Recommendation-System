# AI-Powered Healthy Diet Recommendation System
This project is part of the UWE Essentials and Applications of AI module and is made by Group 1.

## Team members
- Sarib
- Saung
- Treasure
- LPF
- Xia
- Lawrence

## Project overview
This repository contains a Jupyter notebook, `healthy_diet_recommendation.ipynb`, that demonstrates building a healthy diet recommendation system using Instacart shopping data. The system:
- Classifies products as healthy or unhealthy using department/aisle heuristics
- Builds a collaborative filtering item-item similarity matrix (cosine similarity)
- Recommends healthier alternatives for an order basket

## Dataset source
We used the Kaggle dataset:
- **Instacart Market Basket Analysis**
- URL: https://www.kaggle.com/c/instacart-market-basket-analysis/data

## Setup
1. Download data from Kaggle link above.
2. Place CSV files in `raw_data/`:
   - `products.csv`
   - `aisles.csv`
   - `departments.csv`
   - `orders.csv`
   - `order_products__prior.csv`
   - `order_products__train.csv`
3. Open and run `healthy_diet_recommendation.ipynb` in Jupyter.
