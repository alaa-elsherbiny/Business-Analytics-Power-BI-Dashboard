# 📊 End-to-End Business Performance & Analytics Dashboard (Power BI)

An interactive, multi-page Power BI dashboard designed to evaluate overall business performance, track sales metrics across regions, and perform deep-dive profit margin and profitability analysis.

---

## 🚀 Key Project Highlights
* *Data Modeling & DAX:* Implemented custom DAX measures for Year-over-Year (YoY) metrics, statistical summaries (Sum, Average, Min, Max, Variance), and cross-filtering data models.
* *Interactive Features:* Bookmark navigation between report pages, category icons, dynamic page slicers, and dynamic map visual filters.

---

## 🖥️ Dashboard Overview & Pages

### 1. Summary Report 📈
* *Goal:* High-level overview of key business KPIs and operational metrics.
* *Key Metrics:* 
  * Total Sales: *$3.34M*
  * Total Profit: *$917.32K*
  * Total Quantity Sold: *84K units*
* *Visuals:* Sales breakdown by customer segment, monthly profit trends, top 10 customers by quantity, and quantity distribution by shipping mode.
* *Snapshot:*
  ![Summary Report](./summary-dashboard.png)

---

### 2. Sales Details Report 🛒
* *Goal:* Granular analysis of revenue drivers, order performance, and geographic distribution.
* *Key Metrics:* 
  * Average Order Value: *$151.02*
  * Total Orders: *22.1K*
  * Distinct Order Count: *5.76K*
* *Visuals:* Sales breakdown by category & year matrix, top 5 performing regions (Eastern, Western, Central, etc.), geographical mapping of top 10 cities, and Sales vs. Profit distribution scatter plots.
* *Snapshot:*
  ![Sales Details](./sales-dashboard.png)

---

### 3. Profit Details Report 💰
* *Goal:* In-depth financial profit distribution, regional variance, and risk drivers.
* *Key Metrics:* 
  * Max Profit (Single Order): *$8.40K*
  * Min Profit (Loss Driver): *-$6.60K*
  * Profit Variance: *25.03K*
* *Visuals:* Profitability breakdown by shipping mode, quarterly profit distribution pie chart, geographic profit density map, and detailed slicers (Region, Segment, Category, Sub-category).
* *Snapshot:*
  ![Profit Details](./profit-dashboard.png)

---

## 🛠️ Tools & Technologies
* *Power BI Desktop:* Advanced data visualization, bookmarks, report layout & page navigation.
* *DAX (Data Analysis Expressions):* Custom measures (YoY Growth, Aggregations, Filter context manipulation).
* *Power Query:* Data extraction, transformation, and cleansing.
