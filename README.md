# 📊 Sales Performance Analysis Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-FF6600?style=for-the-badge&logo=dax&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

## 📋 Project Overview

An interactive Power BI dashboard designed to provide comprehensive insights into sales performance, profitability, and operational metrics across multiple products, countries, and market segments. This project demonstrates advanced data visualization, DAX calculations, and business intelligence storytelling.

---

## 🎯 Business Problem

Management required a centralized view of sales operations to:
- Identify top-performing products and regions
- Analyze profitability trends over time
- Optimize inventory and manufacturing decisions
- Track COGS (Cost of Goods Sold) efficiency
- Support data-driven strategic planning

---

## 📊 Dashboard Preview

![Sales Dashboard](images/sales-dashboard.png)

*Interactive dashboard featuring drill-down capabilities, dynamic filtering, and real-time metric updates*

---

## 🔍 Key Insights

### Financial Performance
- **Total Sales**: ₦118.73M
- **Total Profit**: ₦16.89M (14.2% profit margin)
- **COGS**: ₦101.83M
- **Active Operations**: 5 countries, 6 products

### Product Analysis
- **VTF** emerges as the highest profit contributor
- **Paseo** leads in total sales volume
- Manufacturing price variations indicate optimization opportunities

### Geographic Performance
- Multi-country presence across North America and Europe
- Regional performance clustering visible through interactive map

### Temporal Trends
- Profit peaked in early months with gradual decline
- Seasonal patterns suggest strategic timing for campaigns

---

## 🛠️ Technologies & Tools

- **Power BI Desktop**: Primary dashboard development
- **DAX (Data Analysis Expressions)**: Advanced calculations and measures
- **Power Query**: Data transformation and cleaning
- **Excel**: Initial data exploration and validation

---

## ✨ Features

✅ **Interactive Filtering**: Dynamic slicers for Country, Year, and Segment  
✅ **Geographic Visualization**: Interactive map with drill-down capability  
✅ **Time-Series Analysis**: Monthly profit trends with forecasting potential  
✅ **Product Comparison**: Side-by-side performance metrics  
✅ **Cost Analysis**: COGS breakdown by product category  
✅ **KPI Cards**: Real-time summary metrics

---

## 📈 Key Metrics & Calculations

### Custom DAX Measures Created:

```dax
Total Profit = SUM(Sales[Profit])

Profit Margin % = 
DIVIDE(
    [Total Profit],
    [Total Sales],
    0
) * 100

YoY Growth = 
DIVIDE(
    [Total Sales] - [Previous Year Sales],
    [Previous Year Sales],
    0
)
```

---

## 🔄 Data Methodology

1. **Data Collection**: Aggregated sales data from multiple sources
2. **Data Cleaning**: Handled missing values, standardized formats
3. **Data Modeling**: Created star schema with fact and dimension tables
4. **DAX Calculations**: Built measures for KPIs and analytical insights
5. **Visualization**: Designed user-friendly, interactive dashboard
6. **Validation**: Cross-checked calculations with source data

---

## 💡 Business Recommendations

Based on the analysis, I recommend:

1. **Focus on VTF Product Line**: Highest profitability warrants increased marketing investment
2. **Investigate Profit Decline**: Address the downward trend in monthly profits
3. **Regional Expansion**: Leverage strong performance in top regions
4. **Cost Optimization**: Review manufacturing prices for underperforming products
5. **Seasonal Strategy**: Align inventory with identified seasonal patterns

---

## 📂 Project Structure

```
sales-analysis-dashboard/
│
├── images/
│   └── sales-dashboard.png
│
├── data/
│   └── sales_data.xlsx (sample data)
│
├── documentation/
│   └── data-dictionary.md
│
└── README.md
```

---

## 🚀 How to Use

1. Download the `.pbix` file from this repository
2. Open with Power BI Desktop (latest version recommended)
3. Refresh data connections if using live data sources
4. Interact with filters and visuals to explore insights

**Note**: If you don't have Power BI Desktop, you can [download it for free from Microsoft](https://powerbi.microsoft.com/desktop/)

---

## 📧 Contact

**Stella**  Data Analyst 
💼 [LinkedIn](your-linkedin-url)  
📧 [Email](your-email@example.com)  
🌐 [Portfolio](your-portfolio-url)

---

## 🙏 Acknowledgments

This project was created as part of my data analytics portfolio to demonstrate proficiency in business intelligence and data visualization.

---

*⭐ If you found this project interesting, please consider giving it a star!*
