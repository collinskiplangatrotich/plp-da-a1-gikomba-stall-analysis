# Gikomba Stall Sales Analysis (`plp-da-a1-gikomba-stall-analysis`)

**Student Name:** Collins Kiplangat Rotich  
**Cohort:** Data Analytics with Python - PLP Academy  

---

## 📌 Business Problem Summary
Wanjiku operates a busy retail clothing stall in Gikomba Market selling dresses, t-shirts, and jeans. While revenue comes in daily, Wanjiku struggles with inventory management, tracking product profitability, and identifying stockout risks before running out of popular items. This project analyzes her weekly sales data using core Python data structures to calculate item-level totals, weekly revenue (**KES 417,400**), overall profit (**KES 186,900**), daily performance tiers, and automated inventory reorder recommendations.

---

## 🚀 How to Run

Click the badge below to run the analysis notebook directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/collinskiplangatrotich/plp-da-a1-gikomba-stall-analysis/blob/main/stall_analysis.ipynb)

Alternatively, clone this repository and run locally:
```bash
git clone https://github.com/collinskiplangatrotich/plp-da-a1-gikomba-stall-analysis.git
cd plp-da-a1-gikomba-stall-analysis
jupyter notebook stall_analysis.ipynb
```

---

## 📊 Top Three Findings

1. **Weekend Sales Dominance:** Saturday was the best-performing day generating **KES 121,000**, while Sunday recorded the lowest sales at **KES 28,500**. Friday and Saturday together accounted for nearly 50% of the stall's total weekly revenue.
2. **Critical Inventory Stockout Risk for T-Shirts:** T-shirts are Wanjiku's highest volume item (200 units sold over 7 days), but her current inventory of 30 units leaves only **1.1 days** of stock remaining, requiring immediate restocking.
3. **High Unit Margin on Jeans:** Although T-shirts lead in sheer volume, Jeans generate the highest unit profit margin (**KES 800 profit per pair** vs. **KES 250 per T-shirt** and **KES 500 per dress**), contributing KES 74,400 in profit.
