# 🍽️ Restaurant Orders SQL Analysis

## 📌 Project Overview

This project analyzes restaurant order data from Maven Analytics to uncover
insights about menu performance and customer behavior using SQL.

**Tools:** PostgreSQL, DBeaver  
**Source:** Maven Analytics (Free Project)  
**Dataset:** 2 tables — `menu_items` (32 items) & `order_details` (~12,000 rows)  
**Date Range:** January – March 2023

---

## 🎯 Objectives

### Objective 1 — Explore the Menu

- The menu has **32 items** across 4 categories
- Cheapest item: **Edamame** ($5.00) | Most expensive: **Shrimp Scampi** ($19.95)
- **Italian** has the highest average price ($16.75), **American** the lowest ($10.07)
- There are **9 Italian dishes** on the menu

### Objective 2 — Explore Order Patterns

- Date range: **January 1 – March 31, 2023**
- **5,370 total orders** | **12,234 total items ordered**
- Several orders contained the maximum of **14 items**
- **20 orders** had more than 12 items

### Objective 3 — Customer Behavior

- 🏆 Most ordered item: **Hamburger** (American)
- 📉 Least ordered item: **Chicken Tacos** (Mexican)
- 💸 Top 5 highest spend orders: #440, #2075, #1957, #330, #2675
- 💰 Most expensive order (#440): **$192.15**

---

## 📂 Files

| File                              | Description                   |
| --------------------------------- | ----------------------------- |
| `data/create_restaurant_db.sql`   | Database schema + raw data    |
| `queries/restaurant_analysis.sql` | All SQL queries with comments |

---

## 💡 Key Insights

1. **Italian food dominates high-spend orders** — the top order was almost entirely Italian dishes
2. **American food is the most popular category** but has the lowest average price
3. Most orders are moderate in size, but outliers with 12+ items contribute significantly to revenue
