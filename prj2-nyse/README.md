# Business Analytics Project: NYSE Financial Analysis

This project is part of my **Udacity Business Analytics Nanodegree**. It focuses on analyzing financial data from a curated NYSE S&P 500 dataset, specifically examining metrics like Cost of Goods Sold (COGS) across various sub-industries. The analysis showcases skills in data interpretation, dashboard creation, and financial forecasting.

## Project Overview

The primary goal of this project is to:
1. **Analyze financial metrics** of NYSE companies using descriptive statistics.
2. **Build interactive dashboards** in Excel/Google Sheets for Profit & Loss statements and financial forecasting.
3. **Generate insights** on cost structures and profitability for better business decision-making.

## Skills Utilized

This project leverages the following skills:
- **Statistical Analysis**: Interpreting mean, median, range, and standard deviation.
- **Excel Functions**: Using IF statements, VLOOKUP, INDEX, MATCH, OFFSET, and data validation techniques.
- **Data Visualization**: Creating visualizations (e.g., bar charts, histograms) to represent business metrics.
- **Financial Modeling**: Forecasting Gross Profit, Operating Profit, and EBIT based on dynamic assumptions.

## Data Source

The dataset is derived from Kaggle’s [New York Stock Exchange S&P 500](https://www.kaggle.com/) page and includes historical financial data for companies in various sub-industries. The data has been cleaned and curated specifically for this project.

## Project Structure

The project consists of the following key tasks:

1. **Exploratory Data Analysis**: Calculated summary statistics and analyzed *Cost of Goods Sold* across different sub-industries.
2. **Task 1 - Summary Statistics**: Analyzed the relationship between ‘GICS Sub Industry’ and ‘Cost of Goods Sold’:
    - Mean COGS: $12.87 billion
    - Median COGS: $4 billion
    - High variability with a standard deviation of $30.93 billion, reflecting right-skewed distribution.
3. **Task 2 - Profit & Loss (P&L) Dashboard**:
    - Created an interactive P&L statement with a dropdown selection for companies, updating historical data dynamically.
4. **Task 3 - Financial Forecasting Model**:
    - Built a forecasting model with Strong, Base, and Weak scenarios for a selected company, incorporating assumptions for revenue growth and margin changes.
5. **Presentation**: Key findings and visualizations are summarized in a presentation document (PDF).

## Key Insights

- **Top 10 Sub-industries by COGS**: Hypermarkets & Super Centers, and Integrated Oil & Gas, among others, have high costs, reflecting significant production and procurement demands.
- **Distribution**: Only 20.35% of sub-industries are above the mean COGS, highlighting the impact of a few high-cost sectors.

## Usage

To explore the project:
1. Open the `summary_statistics.xlsx` file to review descriptive statistics.
2. Navigate to the `P&L_dashboard.xlsx` for a dynamic Profit & Loss statement.
3. Open the `forecast_model.xlsx` file to experiment with the financial forecasting model.

## Requirements

- Excel or Google Sheets
- Basic understanding of financial metrics and Excel functions

## Future Enhancements

Potential areas to extend this project:
- Automate data updates for real-time NYSE data
- Add more granular analysis by exploring additional financial metrics
- Implement more dynamic dashboard features with Power BI or Tableau

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
