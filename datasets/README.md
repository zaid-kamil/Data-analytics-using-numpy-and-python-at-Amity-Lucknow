# Fictional practice datasets

These datasets are synthetic teaching records, not real business data. Currency: INR.

| File | Grain | Rows | Intentional quality issue |
|---|---|---|---|
| retail_sales_practice.csv | One transaction per Order_ID | 13 | Repeated R003; missing Units for R010 |
| marketing_campaigns_practice.csv | One campaign per Campaign_ID | 12 | Missing Spend for C011; zero-result C008 |

Retail: Date uses YYYY-MM-DD; Units is quantity; Unit_Price and Unit_Cost are per unit. Revenue and profit must be calculated.

Marketing: Spend is campaign expense; Impressions counts displays; Clicks, Leads, and Customers are counts; Revenue is attributed campaign revenue. ROAS = Revenue / Spend. A zero denominator means the corresponding ratio is undefined, not zero. No customer-level or personally identifying records are included.
