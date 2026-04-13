## Governance Note

**What this analysis does:**  
Examines discount depth patterns across 27,553 BigBasket grocery and household products using descriptive statistics, OLS log-log regression, and sub-category segmentation.

**Data used:**  
Publicly available BigBasket product catalogue data. Contains product names, categories, brands, market prices, sale prices, and ratings. No personal customer data. No transaction data. No identifiable individual information.

**What this analysis cannot do:**  
- Cannot establish causal relationships — all findings are correlational
- Cannot determine whether discounts drive sales volume
- Cannot reflect current real-time pricing (this is a historical catalogue snapshot)
- Cannot account for seasonal pricing patterns or promotional campaigns

**Potential biases:**  
- Products with missing prices are excluded — may systematically exclude certain brands
- Sub-categories with fewer than 20 products excluded — small niches may have distinct pricing patterns not captured here
- Round-number clustering finding assumes catalogue data is current — if prices are updated algorithmically, the finding may not reflect current state

**DPDPA 2023 compliance:**  
Fully compliant with India's Digital Personal Data Protection Act 2023.  
No personal data of any individual is processed, stored, or analysed in this notebook.  
No consent framework is required — only publicly available product data is used.

**Appropriate use:**  
- Exploratory business strategy discussion  
- Portfolio demonstration of analytical methodology  
- Hypothesis generation for further studies using transaction-level data  

- Not appropriate for live pricing decisions without transaction data  
- Not appropriate for drawing conclusions about current BigBasket strategy without verifying data currency
