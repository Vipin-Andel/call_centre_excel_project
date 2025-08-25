# Call Center Analytics Dashboard

![](https://github.com/Vipin-Andel/call_centre_excel_project/blob/main/Call_centre_reportsheet.PNG)

> A comprehensive Excel-based call center performance analytics dashboard providing actionable insights into customer satisfaction, representative performance, and operational metrics.

## Project Overview

This Excel project analyzes **1,000 call center interactions** across a full year (2024), tracking customer satisfaction, purchase behavior, and operational efficiency. Built with advanced Excel features including pivot tables, dynamic charts, and automated reporting.

### Key Features

- **Interactive Dashboards** - Dynamic pivot tables and charts
- **Representative Performance Tracking** - Individual agent metrics and comparisons  
- **Customer Satisfaction Analysis** - Rating trends and quality insights
- **Revenue Analytics** - Purchase amount tracking and correlations
- **Call Duration Analysis** - Efficiency and complexity metrics
- **Temporal Trends** - Monthly and daily pattern analysis

## Dataset Overview

| Metric | Value |
|--------|--------|
| **Total Calls** | 1,000 |
| **Time Period** | Jan 1, 2024 - Dec 31, 2024 |
| **Unique Customers** | 15 |
| **Representatives** | 5 (R01-R05) |
| **Cities Served** | 3 (Cleveland, Columbus, Cincinnati) |
| **Total Revenue** | $96,623 |
| **Avg Satisfaction** | 3.89/5.0 |
| **Customer Satisfaction** | 73.5% rate 4+ stars |

## File Structure

```
call_centre_excel_project.xlsx
├── Data Sheet          # Raw call center data with customer demographics
├── Pivots Sheet        # Dynamic pivot tables and analysis
├── Customer Centre Report  # Executive summary dashboard
└── Assets Sheet        # Representative images and resources
```

## Key Insights & Findings

### Representative Performance

[2]

- **Top Performer (Volume)**: R02 with 218 calls
- **Top Performer (Revenue)**: R03 with $20,872 
- **Highest Satisfaction**: R01 with 3.92/5.0 rating
- **Most Efficient**: R03 with $100.83 average purchase amount

### Seasonal Trends  

[3]

- **Peak Month**: March (155 calls)
- **Busiest Day**: Monday (165 calls)
- **Call Pattern**: Q1 shows highest activity, summer months slower
- **Duration Insight**: 76.1% of calls exceed 1 hour (complex issues)

### Customer Satisfaction

[4]

- **5-Star Reviews**: 30.7% (307 calls)
- **4+ Star Reviews**: 73.5% (735 calls) 
- **Average Rating**: 3.89/5.0
- **Quality Trend**: Consistent satisfaction across all representatives

### Geographic Distribution

- **Cleveland**: 6 customers (40%)
- **Columbus**: 5 customers (33.3%) 
- **Cincinnati**: 4 customers (26.7%)

### Customer Demographics

- **Gender Split**: 60% Female, 40% Male
- **Age Range**: 22-43 years (Average: 32.6 years)
- **Repeat Customers**: High engagement with multiple calls per customer

## Technical Highlights

### Advanced Excel Features Used:
- **Pivot Tables** - Dynamic data summarization and filtering
- **VLOOKUP & INDEX-MATCH** - Data relationships and lookups
- **Conditional Formatting** - Visual performance indicators
- **Data Validation** - Input controls and dropdown menus
- **Dynamic Charts** - Interactive visualizations
- **Dashboard Design** - Professional reporting layout

### Formula Examples:
```excel
=AVERAGEIF(Representative_Range,R01,Satisfaction_Range)
=SUMPRODUCT((Rating>=4)*1)/COUNT(Rating)*100
=NETWORKDAYS(MIN(Date_Range),MAX(Date_Range))
```

## Business Insights

### Recommendations

1. **Leverage R01's Success**: R01 achieves highest satisfaction - analyze techniques for training
2. **Optimize R02's Efficiency**: High call volume but average revenue - focus on upselling
3. **March Capacity Planning**: Prepare for Q1 surge with additional staffing
4. **Monday Support**: Implement Monday-specific protocols for peak demand
5. **Long Call Analysis**: Investigate why 76% of calls exceed 1 hour

### Growth Opportunities

- **Customer Expansion**: Focus on underserved Cincinnati market
- **Quality Improvement**: Target the 26.5% of customers rating below 4 stars
- **Revenue Optimization**: Average purchase amount has room for improvement
- **Efficiency Gains**: Reduce average call duration while maintaining satisfaction

## Acknowledgments

- **Data Source**: Simulated call center operations data
- **Tools Used**: Microsoft Excel, Advanced Formulas, Pivot Tables
- **Inspiration**: Modern call center analytics best practices

## Contact

**Project Maintainer**: github.com/Vipin-Andel
**LinkedIn**: www.linkedin.com/in/contact-andel-vipin
**Email**: andelvipinz05@gmail.com

*Built with ❤️ and lots of ☕ | Last Updated: August 2025*

