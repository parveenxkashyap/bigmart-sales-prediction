# 🛒 BigMart Sales Prediction Analysis - Regression

A machine learning regression project aimed at predicting the sales of products at BigMart stores. The goal is to analyze the features of products and store attributes to build a model that can accurately forecast item-level sales.

---

## 📊 Project Overview

BigMart collected 2013 sales data for 1,559 products across 10 different stores in various cities. Each product and store is described by several attributes. The objective is to build a predictive model that identifies patterns in sales behavior across stores and products, helping BigMart improve sales strategy.

---

## 🧾 Dataset Description

| Variable                      | Description                                         |
| ----------------------------- | --------------------------------------------------- |
| **Item_Identifier**           | Unique product ID                                   |
| **Item_Weight**               | Weight of the product                               |
| **Item_Fat_Content**          | Whether the product is low fat or not               |
| **Item_Visibility**           | % of display area allocated to the product          |
| **Item_Type**                 | Category of the product                             |
| **Item_MRP**                  | Maximum Retail Price of the product                 |
| **Outlet_Identifier**         | Unique store ID                                     |
| **Outlet_Establishment_Year** | Year the store was established                      |
| **Outlet_Size**               | Physical size of the store                          |
| **Outlet_Location_Type**      | City type of the store                              |
| **Outlet_Type**               | Type of outlet (grocery, supermarket, etc.)         |
| **Item_Outlet_Sales**         | Target variable – product sales in a specific store |

---

## 🧪 Libraries Used

- pandas
- matplotlib
- seaborn
- scikit-learn

---

## 🧠 Algorithms Applied

- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree Regressor
- Random Forest Regressor
- Extra Trees Regressor

---

## 📉 Evaluation Metric

- **Mean Squared Error (MSE):** 0.28  
  _(Note: This value is in log scale; apply exponentiation to convert back to original scale.)_
