# BigBasket Discount Strategy Analysis

## Business Question
Which grocery categories on BigBasket offer the deepest discounts 
from MRP — and what structural patterns reveal how BigBasket actually 
uses discounting as a competitive strategy?

## Key Findings
- Discounting is targeted not blanket — 50% of products sell at full MRP
- Kitchen & Garden (22.2%) and Fruits & Vegetables (21.1%) discounted deepest
- Discount levels cluster at exactly 10%, 20%, 15% — confirming 
  manual round-number pricing, not algorithmic optimisation
- MRP explains only 5% of discount variation (R² = 0.048) — 
  category and brand drive the rest

## Dataset
BigBasket Products — 27,553 grocery and household products, 
11 categories. Source: Kaggle.

## Tools
Python · pandas · statsmodels · matplotlib · seaborn

## Links
Kaggle Notebook: [(https://www.kaggle.com/code/hegdeguruganesh/how-bigbasket-discounts-indian-grocery)]

## Governance
See GOVERNANCE.md for data handling, limitations, and 
DPDPA 2023 compliance.
