# FUTURE_DS_01 – Business Sales Performance Analytics

**Future Interns – Data Science & Analytics Internship (Task 1)**
Intern: Satyam | CIN: FIT/OCT26/DS24259

## Project: Mobile Sales Dashboard (Power BI)

An interactive Power BI dashboard that analyses mobile phone sales to show revenue trends, top brands and models, regional performance, and customer payment behaviour.

![Dashboard](screenshots/dashboard.png)

## Files

| File | Description |
| --- | --- |
| `Mobile_Sales_Dashboard.pbix` | Power BI report (open with Power BI Desktop) |
| `screenshots/dashboard.png` | Dashboard screenshot |
| `README.md` | Project summary, insights and recommendations |

## Dashboard contents

- **KPI cards:** Total Sales (769M), Total Quantity (19K), Transactions (4K), Average selling price (40K)
- **Slicers:** Mobile Model, Payment Method, Brand, Day Name, and Month buttons
- **Visuals:** Sales by City (map), Quantity by Month (line), Customer Ratings (funnel), Transactions by Payment Method (pie), Brand summary (table), Sales by Mobile Model (bar), Sales by Day Name (area)

## Key figures

| Brand | Total Sales | Share | Quantity | Transactions |
| --- | --- | --- | --- | --- |
| Apple | 161,615,730 | 21.0% | 3,932 | 783 |
| Samsung | 160,038,055 | 20.8% | 3,923 | 775 |
| OnePlus | 153,719,439 | 20.0% | 3,830 | 768 |
| Vivo | 150,078,428 | 19.5% | 3,801 | 766 |
| Xiaomi | 143,753,337 | 18.7% | 3,664 | 743 |
| **Total** | **769,204,989** | **100%** | **19,150** | **3,835** |

## Insights

1. **Balanced market:** Apple leads with 21.0% of sales, Xiaomi trails with 18.7%; no brand dominates.
2. **Premium edge:** Apple has the highest sales per unit (41,103), Xiaomi the lowest (39,234).
3. **Top models:** iPhone SE (60M), OnePlus (58M) and Galaxy N (56M) lead sales by model.
4. **Seasonality:** Quantity peaks in July (1,700) and March (1,696); February is lowest (1,451, about 9% below the monthly average of 1,596).
5. **Weekdays:** Saturday is strongest (115M), Wednesday weakest (105M), a gap of about 9.5%.
6. **Payments:** UPI 26.25%, Debit 25.89%, Cash 25.03%, Credit 22.83%; digital methods are about 75% of transactions.

## Recommendations

1. Run promotions and add staff on Saturdays and Mondays; use midweek offers (Wed/Thu) to lift the weakest days.
2. Build stock for March and July; use discounts or festival bundles to lift February and September.
3. Offer no-cost EMI or card offers on premium models to raise credit card usage; use UPI cashback to grow the largest channel.
4. Protect Apple and Samsung premium lines; give Xiaomi value bundles or accessory offers.
5. Next version: add year-on-year comparison and profit margin data so decisions can be ranked by profit.

## Tools

Microsoft Power BI Desktop, DAX measures, GitHub.
