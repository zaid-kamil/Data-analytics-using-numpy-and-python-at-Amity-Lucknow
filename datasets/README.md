# Two small datasets, many big questions

These are made-up datasets for practice. They do not contain real customers or
real business information, so no accountant will chase us if the numbers look
strange. All money values are in Indian rupees (INR).

## 1. Retail sales: notebooks, pens, and profit

**File:** `retail_sales_practice.csv`

**What are we looking at?** Each row is one shop order. It tells us what was
sold, where it was sold, how many units escaped from the shelf, and the price
and cost of one unit.

| Column | Simple meaning | Example |
|---|---|---|
| `Order_ID` | The unique name of an order—its roll number | `R001` |
| `Date` | The day the order was placed (`YYYY-MM-DD`) | `2026-09-01` |
| `Product` | The item that was sold | `Notebook` |
| `Region` | The city where the sale happened | `Lucknow` |
| `Units` | How many items found a new home | `20` |
| `Unit_Price` | What the customer pays for one item | `100` |
| `Unit_Cost` | What one item costs the business | `60` |

This dataset contains shop orders from three cities. It can be used to find
which products and cities bring in the most sales and profit—and whether pens
are secretly carrying the entire business.

Useful calculations:

- Revenue = `Units × Unit_Price`
- Cost = `Units × Unit_Cost`
- Profit = `Revenue − Cost`

Practice questions:

- Which city sold the most units?
- Which product earned the most revenue?
- What is the total profit?
- What is the average order value?
- Which suspicious-looking orders need cleaning before analysis?

The file has **20 rows**. It also has two data-quality problems to find and
clean: `R003` appears twice, and `R010` has a missing `Units` value. One is a
copycat; the other has forgotten how many items it sold.

## 2. Marketing campaigns: clicks, customers, and cash

**File:** `marketing_campaigns_practice.csv`

**What are we looking at?** Each row is one advertising campaign. It shows where
the ad ran, how much was spent, how many people saw or clicked it, and how much
revenue it produced. In short: did the ad earn money, or just collect clicks?

| Column | Simple meaning | Example |
|---|---|---|
| `Campaign_ID` | The unique name of a campaign—another roll number | `C001` |
| `Channel` | Where the ad ran | `Search` |
| `Spend` | Money spent on the campaign | `12000` |
| `Impressions` | Times the ad appeared on a screen | `50000` |
| `Clicks` | Times someone thought, “Fine, I’ll look” | `2500` |
| `Leads` | People interested enough to take the next step | `200` |
| `Customers` | People who finally opened their wallets | `40` |
| `Revenue` | Sales money linked to the campaign | `40000` |

This dataset compares ads on Search, Social, Email, and Display. It can be used
to find which channel gives the best results for the money spent. A million
views may look impressive, but revenue pays for the snacks.

Useful calculations:

- Click-through rate (CTR) = `Clicks ÷ Impressions × 100`
- Cost per click (CPC) = `Spend ÷ Clicks`
- Cost per lead (CPL) = `Spend ÷ Leads`
- Customer acquisition cost (CAC) = `Spend ÷ Customers`
- Return on ad spend (ROAS) = `Revenue ÷ Spend`

Practice questions:

- Which channel gets the most clicks?
- Which campaign has the highest ROAS?
- Which campaign has the lowest cost per customer?
- Does higher spending always produce more revenue?
- Which rows might make a division calculation cry?

The file has **20 rows**. Two rows need special attention: `C011` has a missing
`Spend` value, and `C008` has no clicks, leads, customers, or revenue. When
dividing by zero, the result is undefined, not zero. Even Python refuses to
pretend otherwise.
