# Business Performance Dashboard

> **Pizza My Heart** - Interactive Power BI Dashboard for Sales & Revenue Analysis

## Project Overview

"Pizza My Heart" is a comprehensive business intelligence project that analyzes pizza sales performance through an interactive Power BI dashboard. This project transforms raw order data into actionable insights, helping businesses understand customer behavior, identify top-performing products, and optimize their operations.

## Business Objectives

- **Product Performance**: Identify most popular and highest-grossing pizza types and categories
- **Customer Insights**: Understand ordering patterns by time periods and customer preferences  
- **Market Analysis**: Compare vegetarian vs. non-vegetarian preferences
- **Order Behavior**: Analyze single vs. multiple-quantity order trends
- **Strategic Planning**: Provide data-driven recommendations for marketing and inventory decisions

## 📁 Project Structure

```
Business-Performance-Dashboard/
├── data/
│   ├── raw_data/
│   └── processed_data/
├── dashboard/
│   ├── Pizza_My_Heart_Dashboard.pbix
│   └── dashboard_screenshots/
├── documentation/
│   ├── key_findings_report.pdf
│   └── analysis_methodology.md

└── README.md
```

## Dataset Overview

The analysis is based on comprehensive order-level data containing:

| Column | Description |
|--------|-------------|
| **Order_ID** | Unique identifier for each order |
| **Pizza_Name** | Name of the pizza ordered |
| **Pizza_Category** | Category (Classic, Supreme, etc.) |
| **Size** | Pizza size (S, M, L, XL) |
| **Price** | Unit price of the pizza |
| **Qty** | Quantity ordered |
| **Date** | Order date |
| **Vegetarian** | Vegetarian or Non-Vegetarian classification |
| **Order_Type** | Single or Multiple quantity orders |
| **Day_of_Week** | Day the order was placed |
| **Month_Name** | Month for temporal analysis |
| **Weekend_Weekday** | Weekend or weekday classification |

## Methodology

### 1. Data Preprocessing
- **Data Cleaning**: Removed missing values and duplicates
- **Standardization**: Normalized pizza name formats
- **Quality Assurance**: Validated data integrity

### 2. Feature Engineering
- **Temporal Features**: Day of week, weekend indicators
- **Categorization**: Size groupings, vegetarian classifications  
- **Aggregations**: Revenue and quantity metrics

### 3. Dashboard Development
- **Two-Page Design**: Revenue Analysis & Order Trends
- **Interactive Elements**: Dynamic slicers and filters
- **Visual Variety**: Bar charts, line charts, pie charts, KPI cards
- **Navigation**: Bookmark implementation for seamless user experience

## Key Performance Insights

### Revenue Analysis Dashboard
- ** Top Performer**: Barbecue Chicken Pizza leads in revenue generation
- ** Category Leaders**: Classic and Supreme pizzas dominate sales
- ** Size Preference**: Large (L) pizzas show highest unit sales
- ** Diet Split**: Non-vegetarian pizzas account for 75% of sales
- ** Order Patterns**: 47.4K single-quantity vs 1.89K multiple-quantity orders

### Order Trends Dashboard  
- ** Seasonal Peaks**: April, July, and November show revenue spikes
- ** Weekly Pattern**: Sunday emerges as the most popular ordering day
- ** Timing Split**: Weekdays drive 75% of total sales volume
- ** Category Performance**: Classic pizzas lead in both quantity and revenue

##  Strategic Recommendations

###  Marketing Optimization
- **Promote Top Performers**: Create combo deals for Barbecue Chicken and Classic pizzas
- **Weekend Strategy**: Launch Sunday-specific promotions and family deals

###  Revenue Growth
- **Size Upselling**: Incentivize Large and XL sizes with bulk purchase offers
- **Order Value**: Implement bundle deals to convert single to multiple quantity orders

###  Market Expansion
- **Vegetarian Growth**: Expand vegetarian menu options to capture untapped market
- **Seasonal Campaigns**: Leverage identified peak months for targeted promotions

##  Technical Stack

- ** Power BI**: Dashboard design and interactive visualizations
- ** Excel**: Data cleaning and preprocessing  
- ** Data Analysis**: Statistical analysis and trend identification
- ** Business Intelligence**: Strategic insight generation

##  Future Enhancements

- ** Sentiment Analysis**: Integrate customer reviews and feedback data
- ** Predictive Analytics**: Build forecasting models for revenue prediction
- ** Operational Insights**: Add delivery time tracking and performance metrics
- ** Customer Analytics**: Implement loyalty metrics and return behavior analysis


##  Getting Started

### Prerequisites
- Microsoft Power BI Desktop
- Excel or similar data processing tool

### Installation
1. Clone this repository
   ```bash
   git clone https://github.com/yourusername/Business-Performance-Dashboard.git
   ```
2. Open the `.pbix` file in Power BI Desktop
3. Refresh data connections if needed
4. Explore the interactive dashboard

## Usage

The dashboard provides two main views:
1. **Revenue Analysis**: Focus on financial performance and product profitability
2. **Order Trends**: Analyze temporal patterns and customer behavior

Use the interactive slicers to filter by:
- Pizza Category
- Pizza Name  
- Size
- Month
- Order Type

##  Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

##  Contact

**Sarah Uko**  
Email: ukosarahiniobong@gmail.com
LinkedIn: https://www.linkedin.com/in/datasavysarah/

---

⭐ **Star this repository if you found it helpful!**

*Built with ❤️ and lots of ☕ by Sarah Uko*
