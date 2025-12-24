# Customer Purchasing Behavior Analysis

A comprehensive end-to-end analytics project demonstrating professional data analysis workflows, from SQL querying to executive dashboards.

---

## Executive Summary

This project delivers a comprehensive analysis of customer purchasing behavior through an integrated analytics framework. By leveraging SQL for data extraction, Python for statistical analysis, and Power BI for executive visualization, the project provides actionable insights into customer spending patterns, discount effectiveness, and revenue optimization opportunities.

## Business Context

Understanding customer purchasing behavior is fundamental to revenue optimization and strategic planning. This analysis examines the relationship between discount strategies and purchase value, identifies high-value customer segments, and quantifies spending patterns to inform data-driven business decisions.

**Key Business Questions Addressed:**
- How do discounts influence customer purchase amounts?
- Which customer segments generate the highest revenue contribution?
- What are the defining characteristics of premium customers?
- How can we optimize pricing and discount strategies based on behavioral patterns?

## Analytical Approach

The project follows a structured analytics pipeline designed to transform raw transactional data into strategic business intelligence:

**1. Data Extraction & Transformation (SQL)**  
Structured queries isolate relevant customer cohorts, calculate aggregate metrics, and establish baseline performance indicators.

**2. Statistical Analysis (Python)**  
Exploratory data analysis uncovers distributional patterns, validates assumptions, and quantifies relationships between key variables.

**3. Executive Visualization (Power BI)**  
Interactive dashboards translate analytical findings into accessible insights for stakeholders across business functions.

## Dataset Specification

The analysis utilizes customer-level transactional data with the following schema:

| Field | Description | Data Type |
|-------|-------------|-----------|
| Customer ID | Unique customer identifier | Integer |
| Purchase Amount | Transaction value | Decimal |
| Discount Status | Discount application indicator | Boolean |
| Transaction Metadata | Supplementary purchase attributes | Various |

**Data Quality Considerations:** The dataset has been validated for completeness and consistency. Any transformations applied are documented within the analysis scripts.

## Technical Architecture

**Core Technologies:**
- **SQL** – Data querying and business logic implementation
- **Python 3.x** – Statistical analysis and data exploration
  - `pandas` – Data manipulation and aggregation
  - `numpy` – Numerical computing
  - `matplotlib` / `seaborn` – Statistical visualization
- **Power BI Desktop** – Interactive dashboard development
- **Jupyter Notebook** – Reproducible analysis environment

**Repository Structure:**

```
├── Customer_Behaviour_sql_queries.sql    # SQL analysis queries
├── youtube da.ipynb                      # Python analysis notebook
├── Customer_Bevaviour Dashboard.pbix     # Power BI dashboard
└── README.md                             # Project documentation
```

## Analysis Components

**SQL Analytics**

The SQL component focuses on extracting business-critical metrics through structured queries:
- **Customer Segmentation** – Classification based on spending thresholds and discount utilization
- **Comparative Analysis** – Benchmarking individual customer performance against cohort averages
- **Revenue Attribution** – Quantifying contribution by customer segment
- **Behavioral Filtering** – Isolating customers meeting specific business criteria

*All SQL queries are version-controlled in `Customer_Behaviour_sql_queries.sql`*

**Python Statistical Analysis**

The Python notebook (`youtube da.ipynb`) performs comprehensive exploratory data analysis:
- Data profiling and quality assessment
- Descriptive statistical summaries
- Distribution analysis of purchase amounts
- Correlation analysis between discounts and spending behavior
- Visual pattern identification through statistical graphics

*Key Analytical Outputs:*
- Spending distribution characteristics (mean, median, quartiles, variance)
- Discount impact quantification
- Customer behavior pattern identification
- Statistical validation of business hypotheses

**Power BI Dashboard**

The interactive dashboard provides executive-level visibility into customer behavior metrics:

*Dashboard Features:*
- Real-time KPI tracking for customer spending metrics
- Comparative analysis visualizations (discounted vs. full-price purchases)
- Customer segmentation views with drill-down capabilities
- Clean, professional design optimized for stakeholder presentations

*Dashboard file: `Customer_Bevaviour Dashboard.pbix`*

## Key Findings

The analysis reveals several strategic insights:

1. **Revenue Concentration** – A minority of customers generate disproportionate revenue, following a Pareto distribution pattern
2. **Discount Effectiveness** – Distinct purchasing patterns emerge between discounted and full-price transactions, suggesting opportunity for targeted pricing strategies
3. **Spending Benchmarks** – Average purchase value thresholds effectively distinguish premium customer segments
4. **Decision Support** – Visual analytics democratize complex data, enabling rapid insight generation for non-technical stakeholders

## Implementation Guide

**Prerequisites:**
- SQL-compatible database environment (PostgreSQL, MySQL, SQL Server, etc.)
- Python 3.8+ with required packages: `pandas`, `numpy`, `matplotlib`, `seaborn`
- Power BI Desktop (latest version recommended)
- Jupyter Notebook or JupyterLab

**Execution Steps:**

1. **Database Setup** – Load the dataset into your SQL environment and execute queries from `Customer_Behaviour_sql_queries.sql`
2. **Python Analysis** – Open `youtube da.ipynb` in Jupyter and run all cells sequentially to reproduce the analysis
3. **Dashboard Exploration** – Launch `Customer_Bevaviour Dashboard.pbix` in Power BI Desktop to interact with visualizations

## Strategic Recommendations

Based on the analytical findings, the following strategic actions are recommended:
- **Customer Segmentation Strategy** – Implement tiered service models based on spending behavior
- **Discount Optimization** – Refine discount strategies to balance acquisition cost with customer lifetime value
- **Premium Customer Focus** – Develop retention programs targeting high-value customer segments
- **Continuous Monitoring** – Establish regular dashboard reviews to track behavioral trends

## Future Enhancements

To extend the analytical capabilities of this project:
- **Advanced Segmentation** – Implement machine learning clustering algorithms (K-means, DBSCAN) for sophisticated customer grouping
- **Predictive Analytics** – Develop forecasting models for customer lifetime value and churn prediction
- **Time-Series Analysis** – Incorporate temporal patterns to identify seasonal trends and purchasing cycles
- **Automated Reporting** – Integrate with Power BI Service for scheduled report distribution
- **A/B Testing Framework** – Design experimental methodology to test discount strategies
- **Real-Time Integration** – Connect dashboards to live data sources for dynamic reporting

## About This Project

This project exemplifies industry-standard analytics methodology, demonstrating proficiency in:
- Multi-tool integration across the analytics stack
- Business-focused analytical thinking
- Stakeholder communication through visualization
- Reproducible research practices
- End-to-end project delivery

The work reflects real-world analytical workflows used by data teams to transform transactional data into strategic business intelligence.

## Contributing

Contributions, suggestions, and feedback are welcome. Please open an issue or submit a pull request for any improvements.

## License

This project is available for educational and portfolio purposes.

---

**For questions or collaboration opportunities, please reach out via GitHub.**