# 📊 Mid-D Hub — Finance Tracker Intelligence

> A dynamic Power BI dashboard designed to give end-to-end visibility into sales trends, product metrics, and client-staff relationships within the distribution sector.

---

## 👁️ Visual Showcase

<div align="center">
  <table>
    <tr>
      <td align="center"><b>Executive Financials</b></td>
      <td align="center"><b>Product Intelligence</b></td>
      <td align="center"><b>Customer & Team Hub</b></td>
    </tr>
    <tr>
      <td>
        <img src="./Screenshots/Main.png" alt="Main Dashboard" width="300"/>
      </td>
      <td>
        <img src="./Screenshots/Products.png" alt="Products Dashboard" width="300"/>
      </td>
      <td>
        <img src="./Screenshots/Customers.png" alt="Customers Dashboard" width="300"/>
      </td>
    </tr>
  </table>
</div>

---

## 📁 Repository Contents

```text
A_Business_Analytics_Project/
│
├── 📁 Datasets/
│   ├── 📁 Raw Data/                     # Unprocessed source files
│   └── 📊 Mid D-Hub Cleaned.xlsx        # The 6 underlying relational data tables
│
├── 📁 Power BI Project/
│   └── 📈 Mid D-Hub.pbix                # Core Power BI dashboard file
│
├── 📁 Screenshots/
│   ├── 🖼️ Main.png
│   ├── 🖼️ Products.png
│   └── 🖼️ Customers.png
│
└── 📝 README.md                         # Project documentation
```

---

## 📌 Dashboard Overview & Analytical Domains

The robust data model is split across **3 interactive tabs**, each focused on a distinct business domain and powered by customized DAX formulations:

---

### 1. 💰 Main Dashboard (Sales & Financials)

Tracks overall revenue performance, geographic distribution, and performance against targets.

| KPI | Value |
|-----|-------|
| Total Sales | $22.9M |
| # Orders | 8,188 |
| Units Sold | 1.03M |
| Net Profit | $9.9M |

**Core DAX Measures:**

* **`Income Progress %`**: Evaluates real-time performance against strategic benchmarks.
* **`Balance Variance`**: Calculates absolute deviations in financial accounts.
* **`Income MoM % Display`**: Configured as a precise numeric value to drive dynamic conditional formatting (font colors) while preserving visual indicator arrows for trend analysis.

**Visuals Included:**

* Sales & COGS trend by quarter (2013 Q1 – 2016 Q2)
* COGS %, Gross Profit Margin (GPM), and Average Transaction (AVG T) donut gauges
* Top 20 Sales Cities treemap
* % Sales by State horizontal bar chart (California 44.4%, Washington 21.3%, Alaska 15.1%)

---

### 2. 📦 Products Dashboard

Analyzes product catalog health, demand, and profitability.

| KPI | Value |
|-----|-------|
| # Products | 671 |
| # Active Products | 227 |
| AVG Dry Lead Day | 13 Days |
| AVG Chilly Lead Day | 3 Days |

**Visuals Included:**

* Active / ADP ratio donut charts
* Sales by Product Size treemap (50m, 20m, L, XL, M, S, 1/12 scale, 10m, N/A)
* Sales & Profit by Product bubble chart
* Profit by **Product Price Category** matrix (ensuring highly accurate financial and margin tracking across the portfolio)
* Sales by Product Color bar chart (Blue $6.5M · N/A $5.1M · Black $3.8M)
* Top 20 Demand Products ranked list

---

### 3. 👥 Customers & Employees Dashboard

Monitors customer activity, buying group performance, and salesperson rankings.

| KPI | Value |
|-----|-------|
| # Customers | 401 |
| # Active Customers | 49 |
| Avg. Order Price | $2.8K |
| AVG Delivery Days | 1 Day |
| # Employees | 211 |
| # Salespersons | 122 |

**Visuals Included:**

* Active Customer % donut (12.2%)
* ASP gauge (81%)
* Sales by Buying Group Venn diagram (Independent $7.8M · Tailspin Toys $9.3M · Wingtip Toys $5.8M)
* Top 15 Customers lollipop chart (Customer IDs, max $409K)
* Top 20 Sales Persons ranked bar chart, driven by a dynamic **`Salesperson Rank`** measure (Archer leads).

---

## 📊 Key Insights at a Glance

- **California dominates** with 44.4% of total sales.
- **Tailspin Toys** is the top buying group at $9.3M in sales and $4.0M net profit.
- **Blue** is the best-selling product color at $6.5M.
- Only **12.2%** of customers are active — significant retention opportunity.
- **Archer** leads the salesperson rankings with the highest revenue contribution.

---

## 🛠️ Requirements

| Tool | Version |
|------|---------|
| **Power BI Desktop** | Latest Version (for DAX compatibility) |
| **Microsoft Excel** | 2016 or later (for source data) |
