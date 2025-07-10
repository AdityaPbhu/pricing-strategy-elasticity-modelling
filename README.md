# Pricing Strategy Analysis Using Price Elasticity Modelling

## Project Overview

In this project, I analysed the **Olist Brazilian E-commerce dataset** to understand how product prices affect quantities sold. Using **price elasticity of demand modelling**, I identified strategic pricing opportunities to maximise revenue without significant sales volume loss.

---

## Objective

- Estimate the price elasticity of demand for products
- Simulate revenue under different pricing scenarios
- Recommend data-driven pricing strategies to optimise revenue

---

## Dataset

- **Source:** Olist Brazilian E-commerce Dataset (Kaggle)
- **Files Used:**
  - `order_items_dataset.csv`
  - `products_dataset.csv`

---

## Analysis Steps

1. Imported and explored datasets
2. Merged order items with product details
3. Aggregated data to calculate total quantity sold and average price per product
4. Conducted exploratory data analysis with scatterplots
5. Built a **log-log regression model** to estimate price elasticity
6. Simulated revenue changes under **5%, 10%, and 20% price increases**

---

## Key Results

- **Price Elasticity Coefficient:** -0.0592
  - Demand is **inelastic**, indicating customers are relatively insensitive to price changes.

- **Revenue Simulations:**

| Price Increase | Revenue Change (%) |
| -------------- | ------------------ |
| 5%             | *4.7%*             |
| 10%            | *9.4%*             |
| 20%            | *18.6%*            |

---

## Business Recommendations

1. **Increase prices by 5-10%** on inelastic products to improve revenue and margins.
2. **Monitor sales post-implementation** to validate model assumptions and adjust strategies if needed.
3. **Conduct category-specific elasticity analysis** for more granular pricing decisions in future.

---

## Conclusion

This project demonstrates how **data-driven pricing strategies** can drive profitability in e-commerce businesses. By understanding the price elasticity of demand, brands can set optimal prices that balance competitiveness with revenue growth.

---

## Tools Used

- Python (Pandas, NumPy)
- Matplotlib, Seaborn for visualisation
- Statsmodels for regression modelling
- Jupyter Notebook (VS Code)

---

## Repository Structure

- `pricing_strategy_elasticity.ipynb` – Main analysis notebook
- `images/` – Plots and visual outputs (insert your scatterplot here)

---

## Author

[Aditya Prabhu](https://github.com/AdityaPbhu)

---

**Feel free to connect if you have questions about this project or pricing strategy analytics.**
