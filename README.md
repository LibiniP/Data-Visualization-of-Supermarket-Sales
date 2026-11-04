# Data Visualization of Supermarket Sales

An interactive Power BI dashboard analyzing supermarket sales data — covering sales performance, customer behavior, product trends, and customer feedback, with KPIs, filters, and page navigation for a complete retail insight experience.

## Overview

This project transforms 1,000+ raw supermarket transaction records into a two-page, decision-ready Power BI dashboard. It answers core retail questions — who's buying, how they're paying, what they're buying, and how satisfied they are — through a mix of KPI cards, geographic mapping, trend lines, and rating breakdowns.

## Dashboard Preview

### Page 1: Overview

![Overview Page](Supermarketsales (1).png)

**Key metrics at a glance:**
- **Total Transactions:** 1K
- **Total Sales:** 322.97K
- **Total Profit:** 15.38K
- **Total Quantities Sold:** 6K

**Visuals included:**
- Count of transactions by gender
- Customer locality map (city-level)
- Customer type split (Member vs. Normal)
- Product line filter panel
- Payment method breakdown (E-wallet, Cash, Credit card)
- Transaction-level detail table (Invoice ID, customer type, gender, time)
- Total sales trend over time, with AM/PM sales view toggle
- Tax (5%) collected by product line

### Page 2: Customer Feedback

![Customer Feedback Page](Supermarketsales (2).png)

**Key metrics at a glance:**
- **Average Rating:** 6.97 / 10

**Visuals included:**
- Average rating by gender
- Average rating gauge (overall)
- Average rating by city
- Average rating by product line

## Key Insights

- Sales are fairly evenly split by gender (501 female / 499 male transactions) and customer type (501 Member / 499 Normal).
- Payment method usage is balanced across E-wallet (34.5%), Cash (34.4%), and Credit card (31.1%), suggesting no single dominant channel.
- Customer satisfaction is consistently high and stable across segments — average ratings by gender (6.96–6.98), city (6.82–7.07), and product line (6.8–7.1) all cluster tightly around 7/10.
- Naypyitaw leads slightly in customer satisfaction (7.07) compared to Yangon (7.03) and Mandalay (6.82).
- Food and beverages is the top-rated product line (7.1), while Home and lifestyle trails slightly (6.8).

## Dataset

- **Source file:** `supermarket_sales.csv`
- **Records:** 1,000+ transactions
- **Fields:** Invoice ID, branch/city, customer type, gender, product line, unit price, quantity, tax, total, date, time, payment method, cost of goods sold, gross margin, gross income, rating

## Tech Stack

- **Power BI Desktop** — dashboard design, DAX measures, page navigation
- **DAX** — KPI calculations (totals, averages, tax aggregation)
- **CSV** — source data format

## Files in this Repository

| File | Description |
|---|---|
| `Supermarket_Sales.pbix` | Power BI source file (dashboard + data model) |
| `supermarket_sales.csv` | Raw transaction dataset |
| `Supermarketsales_1.png` | Screenshot — Overview page |
| `Supermarketsales_2.png` | Screenshot — Customer Feedback page |

## How to Use

1. Clone or download this repository.
2. Open `Supermarket_Sales.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free).
3. Use the **Overview** and **Customer Feedback** navigation buttons to switch between pages.
4. Apply the **Product Line** filter panel to slice all visuals by category.
5. Toggle **AM Sales Overview / PM Sales Overview** to compare sales trends by time of day.

## Author

**P. Libini**
[GitHub](https://github.com/LibiniP) · [LinkedIn](https://linkedin.com/in/libini-p)
