# Zen EliteStride Maison — Sales Analysis & Business Insights

## Project overview
This project analyzes **500 sales records** for Zen EliteStride Maison using Excel. The workflow focuses on data cleaning, calculated sales/profit metrics, PivotTables, dashboard reporting, and business recommendations.

**Reporting period:** 1 January–14 August 2026  
**Dataset size:** 500 records  
**Tools:** Microsoft Excel (data cleaning, formulas, PivotTables, dashboard analysis)

> **Data note:** The currency unit is not specified in the dataset, so financial values are shown without a currency symbol. August is a partial month through August 14.

## Key performance indicators

| KPI | Result |
|---|---:|
| Transaction records | 500 |
| Units sold | 4,012 |
| Total revenue | 355,048 |
| Total cost | 192,713 |
| Total profit | 162,335 |
| Overall profit margin | 45.72% |
| Average revenue per record | 710.10 |
| Average profit per record | 324.67 |

## Business insights

### 1. Overall business performance
The dataset records **355,048 revenue** and **162,335 profit**, with an aggregate profit margin of **45.72%**. This indicates positive profitability in the recorded sales. Performance should be monitored using revenue, profit, margin, and units together.

### 2. Revenue and profit over time
| Month | Records | Units | Revenue | Profit |
|---|---:|---:|---:|---:|
| 2026-01 | 68 | 538 | 43,801 | 20,299 |
| 2026-02 | 53 | 461 | 40,664 | 18,698 |
| 2026-03 | 73 | 542 | 45,492 | 20,869 |
| 2026-04 | 61 | 474 | 44,204 | 20,067 |
| 2026-05 | 63 | 501 | 44,578 | 20,407 |
| 2026-06 | 87 | 763 | 70,771 | 32,123 |
| 2026-07 | 68 | 553 | 49,497 | 22,517 |
| 2026-08 (partial) | 27 | 180 | 16,041 | 7,355 |

June was the strongest complete month, with **70,771 revenue** and **32,123 profit**. Revenue increased **58.76%** from May to June and declined **30.06%** from June to July. The underlying cause cannot be established from sales totals alone. August is incomplete and should not be compared directly with full months.

### 3. Products driving sales
| Product | Units | Revenue | Profit |
|---|---:|---:|---:|
| Canvas | 496 | 63,488 | 27,776 |
| Oxford | 561 | 58,905 | 26,367 |
| Brogues | 523 | 58,576 | 25,104 |
| Monk Straps | 575 | 51,175 | 24,150 |
| Boots | 540 | 41,040 | 19,980 |
| Slippers | 342 | 40,698 | 17,784 |
| Loafers | 453 | 24,462 | 11,778 |
| Derby | 522 | 16,704 | 9,396 |

**Insight:** Canvas leads revenue with **63,488**. Monk Straps leads by units sold, showing why both sales value and volume matter.

### 4. Products driving profitability
| Product Cleaned   |   Transactions |   Units |   Revenue |   Profit |
|:------------------|---------------:|--------:|----------:|---------:|
| Canvas            |             61 |     496 |     63488 |    27776 |
| Oxford            |             62 |     561 |     58905 |    26367 |
| Brogues           |             63 |     523 |     58576 |    25104 |

**Insight:** Canvas contributes the highest total profit (**27,776**), followed by Oxford (**26,367**). Maintain availability of leading profit contributors while monitoring margins and demand.

### 5. Categories and brands
**Category performance**

| Category | Units | Revenue | Profit | Profit margin |
|---|---:|---:|---:|---:|
| Formal | 2,025 | 179,935 | 82,274 | 45.72% |
| Casual | 935 | 82,917 | 37,753 | 45.53% |
| Open | 569 | 53,035 | 24,172 | 45.58% |
| Utility | 483 | 39,161 | 18,136 | 46.31% |

Formal is the leading category, generating **179,935 revenue** and **82,274 profit**.

**Brand performance**

| Brand | Units | Revenue | Profit | Profit margin |
|---|---:|---:|---:|---:|
| Clarks | 1,408 | 123,543 | 56,574 | 45.79% |
| Zara | 1,052 | 94,797 | 43,424 | 45.81% |
| Nike | 596 | 54,029 | 24,513 | 45.37% |
| Steve Madden | 485 | 43,855 | 19,932 | 45.45% |
| Timberland | 471 | 38,824 | 17,892 | 46.08% |

Clarks leads brand revenue (**123,543**) and profit (**56,574**), contributing **34.80% of total revenue**.

### 6. Country contribution
| Country | Units | Revenue | Profit | Revenue share |
|---|---:|---:|---:|---:|
| USA | 429 | 39,127 | 17,892 | 11.02% |
| UK | 416 | 32,871 | 15,393 | 9.26% |
| Ghana | 338 | 32,026 | 14,468 | 9.02% |
| Zimbabwe | 311 | 30,124 | 13,584 | 8.48% |
| India | 338 | 29,392 | 13,441 | 8.28% |
| Kenya | 266 | 26,595 | 11,974 | 7.49% |
| Cyprus | 319 | 26,531 | 12,210 | 7.47% |
| Uganda | 291 | 25,851 | 11,798 | 7.28% |
| Philippines | 255 | 20,810 | 9,548 | 5.86% |
| Nigeria | 244 | 20,798 | 9,638 | 5.86% |
| Germany | 209 | 20,204 | 9,010 | 5.69% |
| Australia | 211 | 18,562 | 8,476 | 5.23% |
| Canada | 202 | 17,565 | 8,102 | 4.95% |
| Albania | 183 | 14,592 | 6,801 | 4.11% |

The **USA** is the top country by revenue (**39,127**). The five leading countries account for **46.06%** of total revenue. Consider targeted retention and marketing, while including fulfillment and operating costs in future market comparisons.

### 7. Payment method and product preferences
| Payment method | Records | Units | Revenue | Profit | Revenue share |
|---|---:|---:|---:|---:|---:|
| Card | 137 | 1,108 | 99,257 | 45,373 | 27.96% |
| Bank Transfer | 135 | 1,043 | 94,100 | 42,792 | 26.50% |
| Cash | 125 | 1,049 | 93,540 | 42,784 | 26.35% |
| Mobile Money | 103 | 812 | 68,151 | 31,386 | 19.19% |

**Card** is the largest payment method by revenue (**99,257**, 27.96% of total revenue). Revenue totals alone do not prove customer preference; transaction value and customer mix can influence the result. Keep payment options available while measuring fees, failed payments, conversion, and average order value.

Highest-revenue product by payment method:
- **Bank Transfer:** Canvas
- **Card:** Oxford
- **Cash:** Canvas
- **Mobile Money:** Brogues

### 8. Recommended management actions
1. **Protect high-performing products:** Monitor stock and sales velocity for leading products, especially Canvas, Oxford, and Brogues.
2. **Investigate June's peak:** Review promotions, marketing, stock availability, and customer mix before repeating tactics.
3. **Strengthen the leading category:** Support Formal footwear while testing campaigns for smaller categories.
4. **Manage brand concentration:** Build on Clarks' performance while tracking the growth and margins of other brands.
5. **Focus on key markets:** Use country-level sales to guide retention and marketing, but include delivery and operating costs.
6. **Evaluate payment methods:** Compare conversion, fees, transaction failures, and order value by payment type.
7. **Track balanced KPIs:** Monitor revenue, profit, margin, units, average transaction revenue, and month-on-month movement.
8. **Improve future analysis:** If available, add customer IDs, discounts, returns, inventory, shipping costs, and marketing spend to explain sales drivers and estimate net profitability more accurately.

## Data limitations
- The dataset covers January 1–August 14, 2026; August is partial.
- Currency is not specified, so financial values are shown without a currency symbol.
- The analysis is descriptive and does not prove the causes of observed trends.
- Aggregate profit margin is calculated as total profit divided by total revenue.

## Conclusion
Zen EliteStride Maison recorded **{fmt(total_revenue)} revenue**, **{fmt(total_profit)} profit**, and a **{pct(margin)} overall profit margin** during the period. Canvas, Formal footwear, and Clarks are the top contributors in their respective product, category, and brand groups, while the USA leads by country revenue. The next step is to present these findings in an interactive dashboard and monitor them as new data arrives.

---
*Prepared as a portfolio case study demonstrating Excel data cleaning, analysis, business intelligence, and insight communication.*

