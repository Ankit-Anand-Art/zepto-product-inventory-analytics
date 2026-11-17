# Zepto Product & Inventory Analytics

## 📌 Project Overview

This project uses MySQL to analyze a Zepto e-commerce product
dataset containing product-level information such as categories,
pricing, discounts, inventory, stock availability, and product weight.

The objective is to identify product, pricing, inventory, and
assortment insights that can support data-driven product decisions.

## 🛠️ Tools & Technologies

- MySQL 8.0
- MySQL Workbench
- SQL

## 📊 Dataset

The dataset contains information on 3,700+ product SKUs across
multiple product categories.

Key attributes include:

- Product category
- Product name
- MRP
- Discount percentage
- Discounted selling price
- Available quantity
- Weight
- Stock availability
- Product quantity

## 🔍 Analysis Performed

### Data Cleaning
- Checked for missing values
- Identified duplicate product names
- Identified zero-price products
- Converted product prices from paise to rupees
- Examined stock availability

### Product & Pricing Analysis
- Identified products with the highest discounts
- Analyzed high-MRP products with low discounts
- Compared average discounts across categories
- Calculated price per gram

### Inventory Analysis
- Compared in-stock and out-of-stock products
- Identified high-MRP products that are out of stock
- Calculated estimated inventory value by category
- Analyzed total inventory weight across categories

## 💡 Key Product Questions

1. Which products offer the highest discounts?
2. Which high-value products are currently out of stock?
3. Which categories hold the highest inventory value?
4. Which categories provide the highest average discounts?
5. Which products provide the best price-to-weight value?
6. Which categories have the largest inventory weight?

## 📁 Repository Structure

```text
zepto-product-inventory-analytics/
│
├── README.md
├── Zepto_Analysis.sql
└── data/
    └── zepto_v2.csv



### 4. Important: don't overclaim

Since your current dataset is **product/inventory-level**, don't write things like:

- Customer retention
- Conversion rate
- Revenue
- Customer lifetime value
- Repeat purchase rate

unless you actually have the underlying order/customer data.

Your current SQL supports pricing, discount, inventory, stock availability, category and product-value analysis. :chatgpt-content-reference{index="2"}

### 5. GitHub presentation

Once uploaded, your repository should immediately show:

**Zepto Product & Inventory Analytics**

> MySQL project analyzing 3,700+ product SKUs across multiple categories to derive pricing, inventory, stock availability, and assortment insights.

Then a recruiter can open `Zepto_Analysis.sql` and see the actual SQL.

If you want, I can also **create a polished `README.md` and a cleaned final `Zepto_Analysis.sql` for you as downloadable files**, ready to drag-and-drop into GitHub.
