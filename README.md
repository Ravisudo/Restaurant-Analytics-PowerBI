# 🍽️ Restaurant Analytics Dashboard

<div align="center">

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logoColor=white)](https://learn.microsoft.com/en-us/dax/)
[![SQL](https://img.shields.io/badge/SQL-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)](https://www.microsoft.com/en-us/sql-server/)
[![Power Query](https://img.shields.io/badge/Power%20Query-00A4EF?style=for-the-badge&logoColor=white)](https://powerquery.microsoft.com/)

**An interactive, end-to-end business intelligence solution for restaurant performance analysis and strategic decision-making.**

[Overview](#-project-overview) • [Features](#-dashboard-features) • [Pages](#-dashboard-pages) • [Structure](#-folder-structure) • [Technologies](#-technologies-used)

</div>

---

## 📊 Project Overview

This comprehensive Power BI dashboard provides restaurant operators, managers, and stakeholders with deep, actionable insights into business performance across multiple dimensions. The project demonstrates advanced data analytics capabilities including data modeling, complex DAX calculations, dynamic dashboarding, and time-series analysis.

The solution processes multi-source data through SQL-based transformations and Power Query ETL pipelines, enabling executives to monitor KPIs in real-time and identify growth opportunities across customer segments, restaurant locations, and delivery channels.

**Key Metrics Tracked:**
- Revenue trends and forecast analysis
- Customer acquisition and retention
- Order patterns and basket size analysis
- Restaurant-level performance benchmarking
- Delivery operations efficiency
- Seasonal trends and anomalies

---

## ✨ Dashboard Features

| Feature | Description | Business Value |
|---------|-------------|-----------------|
| 🎯 **Interactive KPI Cards** | Real-time key performance indicators with visual indicators | Quick performance assessment at a glance |
| 🔄 **Dynamic Slicers** | Multi-dimensional filtering across date ranges, locations, and segments | Drill-down analysis without manual report creation |
| 📊 **Drill-Through Pages** | Contextual navigation to detailed restaurant-level analytics | Investigate performance anomalies rapidly |
| 📈 **Time Intelligence** | YTD, Previous Month, Growth %, and YoY comparisons | Temporal trend analysis and forecasting |
| 🎨 **Responsive Design** | Mobile-friendly layouts optimized for different screen sizes | Stakeholder access on any device |
| 💾 **Power Query ETL** | Automated data transformations and data quality checks | Reduced manual data preparation time |
| 📐 **Advanced DAX Measures** | 50+ calculated measures for business logic implementation | Complex business rules encapsulated in formulas |
| 🔗 **Relational Data Model** | Star schema design with optimized relationships | Fast query performance and reduced redundancy |

---

## 📄 Dashboard Pages

### 1️⃣ **Executive Overview**
High-level business performance dashboard for C-suite stakeholders. Displays total revenue, customer count, order volume, and key growth metrics with visual trend indicators and comparison against targets.

**Key Elements:** Revenue cards, Order volume trends, Customer growth rate, Geographic heatmap

### 2️⃣ **Customer Analytics**
Comprehensive customer behavior and segmentation analysis. Includes customer lifetime value, acquisition channels, repeat purchase rates, and cohort analysis.

**Key Elements:** Customer segments, Repeat purchase trends, Acquisition source analysis, Revenue by customer type

### 3️⃣ **Restaurant Performance**
Location-level operational dashboard comparing restaurants across revenue, order count, average ticket size, and efficiency metrics. Identify high-performing and underperforming locations.

**Key Elements:** Restaurant ranking table, Location performance cards, Comparative benchmarking, Growth drivers

### 4️⃣ **Delivery Operations**
Delivery channel efficiency and logistics analysis. Monitor delivery times, order fulfillment rates, and delivery cost margins.

**Key Elements:** Delivery time analysis, Order status breakdown, Driver efficiency metrics, Cost-per-delivery trends

### 5️⃣ **Advanced Insights**
Deep-dive analytics for strategic planning. Includes seasonality patterns, product performance, market basket analysis, and predictive indicators.

**Key Elements:** Seasonal decomposition, Product performance matrix, Cross-sell opportunities, Trend forecasting

### 6️⃣ **Restaurant Details (Drill-Through)**
Contextual detail page accessed via drill-through from other pages. Provides comprehensive operational overview for a selected restaurant including all relevant KPIs, trends, and diagnostics.

**Key Elements:** Restaurant-specific KPIs, Historical performance trends, Operational diagnostics, Action items

---

## 📁 Folder Structure

```
Restaurant-Analytics-PowerBI/
├── 📊 Restaurants_Analysis.pbix          # Main Power BI workbook
├── 📂 Dataset/
│   ├── restaurants_master.csv            # Restaurant dimension table
│   ├── customers.csv                     # Customer information
│   ├── orders.csv                        # Transaction records
│   ├── order_items.csv                   # Line-level order details
│   ├── menu_items.csv                    # Product catalog
│   └── delivery_logistics.csv            # Delivery performance data
├── 🗄️ SQL/
│   ├── data_extraction.sql               # Source system queries
│   ├── data_validation.sql               # Data quality checks
│   ├── feature_engineering.sql           # Derived metrics calculation
│   └── aggregation_queries.sql           # Reporting layer views
├── 📐 DAX/
│   ├── time_intelligence_measures.dax    # YTD, YoY calculations
│   ├── kpi_calculations.dax              # Core business metrics
│   ├── customer_analytics.dax            # Customer-focused measures
│   └── advanced_measures.dax             # Complex business logic
├── 🖼️ Images/
│   ├── executive_overview.png            # Dashboard screenshot
│   ├── customer_analytics.png            # Dashboard screenshot
│   ├── restaurant_performance.png        # Dashboard screenshot
│   ├── delivery_operations.png           # Dashboard screenshot
│   ├── advanced_insights.png             # Dashboard screenshot
│   └── drill_through_detail.png          # Dashboard screenshot
└── 📋 README.md                          # This file
```

---

## 🛠️ Technologies Used

### Core BI Platform
- **Power BI Desktop** – Interactive dashboard development and visualization
- **Power BI Service** – Cloud deployment and sharing

### Data Processing & ETL
- **Power Query** – Data extraction, transformation, and loading
- **SQL Server / SQL** – Advanced data extraction and aggregation
- **Excel** – Supporting data preparation and validation

### Analytics & Calculations
- **DAX (Data Analysis Expressions)** – 50+ calculated measures
- **Power Query M Language** – Advanced transformations

### Data Modeling
- **Star Schema Design** – Optimized for analytics queries
- **Relationships & Cardinality** – Proper many-to-one configurations
- **Hierarchies** – Geographic and time-based dimensions

---

## 💼 Skills Demonstrated

| Category | Skills |
|----------|--------|
| **BI & Analytics** | Power BI, DAX, Power Query, Data Modeling, Dimensional Modeling |
| **Data Management** | SQL queries, ETL pipelines, Data validation, Data quality |
| **Business Analysis** | KPI definition, Requirements gathering, Stakeholder communication |
| **Visualization** | Dashboard design, UX/UI principles, Color theory, Visual hierarchy |
| **Problem Solving** | Performance optimization, Troubleshooting, Root cause analysis |
| **Technical** | Relationships, Hierarchies, Calculated columns, Conditional formatting |

---

## 🚀 Installation & Usage

### Prerequisites
- Power BI Desktop (Latest Version) - [Download Here](https://powerbi.microsoft.com/en-us/downloads/)
- SQL Server or compatible SQL database (Optional - for data refresh)
- Access to the data sources

### Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Ravisudo/Restaurant-Analytics-PowerBI.git
   cd Restaurant-Analytics-PowerBI
   ```

2. **Open the Power BI File**
   - Launch Power BI Desktop
   - Open `Restaurants_Analysis.pbix`

3. **Configure Data Sources** (if needed)
   - In Power BI, go to **File > Options & Settings > Data Source Settings**
   - Update connection strings to match your environment
   - Refresh data if connecting to live SQL sources

4. **Explore the Dashboard**
   - Navigate through the 6 dashboard pages using the navigation pane
   - Use slicers to filter data by date range, location, and customer segment
   - Click on data points to drill through to the Restaurant Details page

5. **Publish to Power BI Service** (Optional)
   - Click **Publish** in the Power BI Desktop ribbon
   - Share with stakeholders via Power BI Service workspace

### Refresh Data
- **Desktop:** Click **Refresh** in the Home ribbon to reload data from sources
- **Service:** Configure scheduled refresh in dataset settings (up to 8x daily for Pro license)

---

## 📊 Dashboard Screenshots

### Executive Overview
![Executive Overview](./Images/executive_overview.png)
*High-level KPI summary for executive stakeholders with revenue trends and growth indicators*

### Customer Analytics
![Customer Analytics](./Images/customer_analytics.png)
*Customer segmentation, acquisition channels, and lifetime value analysis*

### Restaurant Performance
![Restaurant Performance](./Images/restaurant_performance.png)
*Location-level comparison with performance rankings and operational metrics*

### Delivery Operations
![Delivery Operations](./Images/delivery_operations.png)
*Logistics efficiency, delivery time analysis, and order fulfillment tracking*

### Advanced Insights
![Advanced Insights](./Images/advanced_insights.png)
*Seasonal patterns, product performance, and predictive indicators*

### Restaurant Details (Drill-Through)
![Restaurant Details](./Images/drill_through_detail.png)
*Comprehensive restaurant-specific operational dashboard with all relevant KPIs*

---

## 📈 Key Business Insights

This dashboard enables stakeholders to:

✅ **Identify Growth Opportunities** – Pinpoint underperforming restaurants and high-potential markets  
✅ **Optimize Operations** – Monitor delivery efficiency and operational metrics in real-time  
✅ **Understand Customers** – Analyze purchase patterns, preferences, and lifetime value by segment  
✅ **Track Progress** – Monitor KPIs against targets and historical trends  
✅ **Make Data-Driven Decisions** – Replace gut-feel decisions with evidence-based insights  
✅ **Forecast Demand** – Anticipate seasonal trends and plan inventory accordingly  

---

## 🔮 Future Enhancements

Potential additions to extend the analytics capabilities:

- [ ] **Predictive Analytics** – ML models for demand forecasting and churn prediction
- [ ] **Real-time Data Integration** – Streaming data from POS systems via Azure Event Hubs
- [ ] **Mobile App** – Power BI mobile integration for on-the-go executive dashboards
- [ ] **Budget vs. Actual Analysis** – Financial planning and variance analysis
- [ ] **Competitive Benchmarking** – Market-wide performance comparisons
- [ ] **Customer 360 View** – Integrated customer data platform with RFM analysis
- [ ] **Automated Alerts** – Anomaly detection and threshold-based notifications
- [ ] **What-If Scenarios** – Simulation tools for strategic planning
- [ ] **Staff Analytics** – Employee performance and scheduling optimization
- [ ] **Sustainability Metrics** – Environmental impact tracking and reporting

---

## 👨‍💼 Author

**Ravisudo**

- 📊 Business Intelligence & Data Analytics Professional
- 💡 Specializing in Power BI, DAX, and SQL-based analytics solutions
- 🎯 Passionate about transforming data into actionable business insights
- 🔗 Portfolio: [GitHub Profile](https://github.com/Ravisudo)

---

## 📝 License

This project is open source and available under the MIT License - see the LICENSE file for details.

---

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements or enhancements:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/enhancement`)
3. Commit your changes (`git commit -m 'Add enhancement'`)
4. Push to the branch (`git push origin feature/enhancement`)
5. Open a Pull Request

---

## ❓ FAQ

**Q: Can I modify the dashboard for my own restaurant business?**  
A: Absolutely! The dashboard structure and DAX calculations can be adapted to your specific data schema and business requirements. Update the data connections and adjust measures as needed.

**Q: What's the typical file size and performance impact?**  
A: The PBIX file ranges from 5-20 MB depending on data volume. For optimal performance with large datasets (>1M rows), consider using DirectQuery mode or aggregations.

**Q: How often should I refresh the data?**  
A: Refresh frequency depends on your business needs. Real-time dashboards may require hourly refreshes, while strategic dashboards may refresh daily or weekly.

**Q: Can this be deployed to Power BI Service for sharing?**  
A: Yes! Publish to Power BI Service and share with your organization. Apply Row-Level Security (RLS) to restrict data access by restaurant manager or region.

---

<div align="center">

**⭐ If you find this project helpful, please consider starring it!**

*Built with ❤️ using Power BI*

</div>