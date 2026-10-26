# RETAIL SALES AND PROFITABILITY ANALYSIS (2014-2017)

> Comprehensive Superstore analysis covering $2.3M in sales, profitability deep-dive, state performance and 4-year profit forecasting.

### 🔍 Dashboard Preview

**Page 1 - Executive Overview (KPIs + Trends):**
- Total Sales $2.3M, Total Profit $286K, Margin 12.03% (below healthy benchmark)
- Yearly Sales Trend, Sales by Category, Profit by Category
  <img width="1040" height="655" alt="Retail Sales Dashbaord 1 tableau" src="https://github.com/user-attachments/assets/1743b3f7-a7d2-457a-88f2-ea7db86af393" />


**Page 2 - Deep Dive (Geography + Forecast + Product):**
- State Map, Yearly Profit Forecast to 2021, Sales vs Profit by Sub-Category
  <img width="1043" height="654" alt="Retail Sales Dashboard 2 tableau" src="https://github.com/user-attachments/assets/4a8d55a9-4a9a-4c61-a6af-dce4eac0498b" />


### 📌 Business Problem
Management needed to answer:
- Why is profit margin only 12.03% (below healthy benchmark)?
- Which states, categories and sub-categories are profitable?
- What will profit look like by 2021?

### 📂 Dataset Overview
- **Source:** US Superstore Retail (2014-2017) - 9,994 orders
- **Total Sales:** $2,297,200.86 (approx $2.3M)
- **Total Profit:** $286,397.02 (approx $286K)
- **Overall Margin:** 12.03%
- **Date Range:** 2014-2017 actuals, 2018-2021 forecasted

### 🛠️ Tools & Techniques
- **BI Tool:** Tableau 
- **Analysis:** Time-Series Forecasting, Geospatial Mapping, Profitability Matrix (Sales vs Profit), Category Benchmarking, Margin Analysis
- **Visuals:** Choropleth Map, Forecast Line with CI, Scatter Plot, Bar Charts, KPI Cards, Slicers (Year/Category/State)

### 📈 Key Insights & Results - Page 1: Overview

**KPIs (2014-2017):**
- **Total Sales:** $2.3M
- **Total Profit:** $286K
- **Forecast Peak:** $152K profit projected by 2021
- **Profit Margin:** 12.03% - flagged as *Below Healthy Benchmark* (typically 15%+ for retail)

**Yearly Sales Trend - Strong Growth:**
- 2014: $484,247.50
- 2015: $470,532.51 (-2.8% dip)
- 2016: $609,205.60 (+29% recovery)
- 2017: $733,215.26 (+20% growth) - **Best year**
- **Insight:** Despite 2015 dip, business grew 51% from 2014 to 2017.

**Category Performance - The Margin Gap:**
| Category | Sales | Profit | Margin | Verdict |
| :--- | :--- | :--- | :--- | :--- |
| Technology | $836,154.03 | $145,454.95 | 17.4% | **Best** - Drives both sales & profit |
| Office Supplies | $719,047.03 | $122,490.80 | 17.0% | Healthy |
| Furniture | $741,999.80 | $18,451.27 | 2.5% | **Problem** - High sales, almost no profit |

> **Finding:** Furniture generates $742K sales but only $18K profit - pricing or shipping cost issue.

### 📈 Key Insights & Results - Page 2: Deep Dive

**1. State Performance - Extreme Concentration:**
- California: $457,687.63 (19.9% of total sales) - #1 state
- Texas: $170,188.05
- Washington: $138,641.27
- Bottom 3: South Dakota $1,315, DC $2,865, Montana $5,589
- **Risk:** Over-dependence on West Coast.

**2. Yearly Profit Forecast - Optimistic:**
- 2014: $49,543.97
- 2015: $61,618.60
- 2016: $81,795.17
- 2017: $93,439.27
- **Forecast 2018-2021:** $110K -> $124K -> $138K -> **$152,665.87 in 2021**
- Trend: Profit expected to 3x from 2014.

**3. Sales vs Profit by Sub-Category - Stars vs Dogs:**

- **STARS (High Profit):** Copiers - $149K sales, $55,617 profit (37% margin) - Most profitable
- **CASH COWS (High Sales):** Phones - $330K sales, $44,515 profit
- **High Margin Gems:** Paper - $78K sales, $34K profit (43% margin), Accessories - $167K / $41K (25%)
- **DOGS (Loss Makers):**
    - Bookcases: $114,880 sales, **-$3,472.56 loss**
    - Supplies: $46,673 sales, **-$1,189.10 loss**
- **Low Margin Trap:** Machines: $189,238 sales but only $3,384 profit (1.8% margin)

### 💡 Strategic Recommendations

1.  **Fix Furniture Category:** Audit shipping costs & discounting - 2.5% margin is unsustainable despite $742K sales.
2.  **Eliminate Loss Makers:** Discontinue Bookcases & Supplies sub-categories or increase price by 15%.
3.  **Invest in Technology:** Highest sales ($836K) + high profit ($145K) - expand marketing.
4.  **Geographic Diversification:** Reduce CA risk - replicate CA strategy in low-performing states.
5.  **Profit Margin Improvement:** Current 12.03% is below benchmark - pushing Paper & Copiers can lift to 15%+.

Taableau Public Link: https://public.tableau.com/views/RetailSalesandProfitabilityAnalysis/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link<img width="468" height="84" alt="image" src="https://github.com/user-attachments/assets/eab4c431-08a2-4704-aee0-8191c61b3b66" />

