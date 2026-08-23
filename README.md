# Excel_Project_Hub
# 📊 UPI Transaction Analytics Dashboard
 
**An interactive Excel dashboard analyzing 500K+ UPI transactions across India — built to surface real-time payment trends, fraud signals, and platform performance.**
 
![Dashboard Preview]([dashboard-preview.png](https://github.com/luv-saluja/Excel_Project_Hub/blob/main/DASHBOARD_UPI_PROJECT.png))
 
---
 
## 🔍 Overview
 
This dashboard provides a real-time overview of UPI (Unified Payments Interface) transaction activity across India, analyzing **502.89K transactions** worth **₹44.25 Cr** in total volume. It was built entirely in Excel using pivot tables, DAX-style calculated fields, dynamic slicers, and advanced chart types to turn a raw transaction-level dataset into a decision-ready operational and fraud-monitoring tool.
 
The dashboard covers **7 payment apps**, **8 banks**, and **28 states**, with multi-dimensional filtering across city, gender, merchant category, and merchant name — enabling stakeholders to drill from a national view down to a single city/merchant in seconds.
 
---
 
## ✨ Key Features
 
- **KPI Command Center** — five headline metrics at a glance: Total Transactions (502.89K), Total Amount (₹44.25 Cr), Total Cashback (₹34.63 L), Success Rate (91.00%), and Suspected Fraud count (17.09K)
- **Time-Series Trend Analysis** — daily transaction amount trend line to spot volume spikes/dips across the month
- **Platform Market Share** — donut chart breaking down transaction share across PhonePe, Google Pay, Paytm, Amazon Pay, BHIM, Cred Pay, and WhatsApp Pay
- **Transaction Status Breakdown** — Success/Failed/Pending/Refunded distribution to monitor platform health
- **Geo-Mapped State Analysis** — a choropleth map of India combined with a ranked state-wise revenue table (Maharashtra, Karnataka, Delhi, etc.)
- **Bank-wise Performance** — transaction amount ranked by issuing bank (HDFC, SBI, Kotak, Canara, ICICI, Axis, BOB, PNB)
- **Root-Cause Failure Analysis (Pareto Chart)** — ranks failure reasons (insufficient balance, server down, wrong UPI PIN, transaction timeout, bank server issue, etc.) to prioritize fixes by impact
- **Cashback ROI View** — cashback burn vs. total revenue by platform, exposing which apps are cashback-heavy relative to revenue generated
- **Age-wise Transaction Variation** — heatmap of transaction behavior across age bands (18–24 through 55+) by category
- **Hour × Day Heatmap** — transaction density matrix across all 24 hours and all 7 weekdays, identifying peak usage windows for operational planning and fraud monitoring
- **Dynamic Filter Panel** — synchronized slicers for City, Gender, Merchant Category, and Merchant Name driving every visual on the dashboard simultaneously
---
 
## 🛠️ Tech Stack
 
| Tool | Purpose |
|---|---|
| **Microsoft Excel** | Data modeling, pivot tables, dashboard build |
| **Excel Charts** (Line, Donut, Bar, Pareto, Heatmap, Map) | Visualization layer |
| **Slicers & Timeline Controls** | Interactive, cross-filtered exploration |
| **Conditional Formatting** | Heatmap and status color-coding |
 
---
 
## 📁 Dataset
 
- **Scope:** 502,890 UPI transaction records
- **Period:** May 2026
- **Dimensions:** City, State, Gender, Age Band, Merchant Category, Merchant Name, Bank, Payment App, Transaction Status, Failure Reason, Hour/Day of Transaction
- **Metrics:** Transaction Amount (INR), Cashback Amount, Success/Failure Status
---
 
## 📈 Key Insights Surfaced
 
- Identified **peak transaction windows by hour and day-of-week**, supporting operational load planning and fraud-monitoring prioritization
- Ranked the **top failure root-causes** by frequency (Pareto view), directing engineering/ops attention to the highest-impact fixes first
- Surfaced **cashback-to-revenue efficiency by platform**, flagging apps where cashback spend isn't proportionally converting to transaction revenue
- Mapped **state-level revenue concentration**, showing Maharashtra, Karnataka, and Delhi as the top three revenue-contributing states
---
 
## 🚀 How to Use
 
1. Download `UPI_Transaction_Dashboard.xlsx`
2. Open in Microsoft Excel (2016 or later recommended for full slicer/chart support)
3. Use the **Filter Panel** on the left to slice by City, Gender, Merchant Category, or Merchant Name
4. All KPIs, charts, and the map update live based on your filter selection
---
 
## 👤 Author
 
**Luv Singh Saluja**
B.Tech Mechanical Engineering, National Institute of Technology, Raipur
 
---
 
## 📜 License
 
This project is released for portfolio and educational purposes. Feel free to fork and adapt for your own learning.
 
