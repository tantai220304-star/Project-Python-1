# 🐍📊 BDM200 – Group Project (Python) | 👥 Group 6 – 🛒 SuperStore Sales EDA

## 🌟 Overview
This project analyzes the **SuperStore Sales** dataset using **Python** to uncover patterns in **sales performance** 💰 and **profitability** 📈.  
The dataset contains **9,994 rows** and **19 usable variables** (after removing empty “Unnamed” columns) 🧹. Each row represents a **transaction line item** 🧾, so one order can appear multiple times when it contains multiple products.

It includes:
- 🧹 **Data Cleaning & Preparation** (remove unused columns, check missing values, validate dates, fix data types)
- 🧠 **Feature Engineering** (`ship_days` = ship_date − order_date ⏳)
- 📌 **Descriptive Statistics** (mean/median/min/max/std, distributions, outliers)
- 🔗 **Correlation Analysis** (relationships between sales, profit, discount, quantity)
- 🧮 **Pivot / Groupby Summaries** (category, sub-category, segment, region performance)
- 📊 **Visual Insights** (discount vs profit, category profitability, shipping patterns)

## 🗂️ Dataset Entities (Columns Used)
- 🆔 `order_id`
- 📅 `order_date`, 🚚 `ship_date`
- 🧍 `customer`, 🏭 `manufactory`
- 🏷️ `product_name`
- 👥 `segment`
- 🗃️ `category`, `subcategory`
- 🌎 `region`, `city`, `state`, `country`, 📮 `zip`
- 🧾 `quantity`, 💵 `sales`, 💰 `profit`, 🏷️ `discount`, 📈 `profit_margin`
- ⏳ `ship_days` 

## 🛠️ Tools & Technologies
- 🐍 Python
- 🧮 pandas, numpy
- 📊 matplotlib (and/or seaborn)
- 📓 Jupyter Notebook / ☁️ Google Colab



