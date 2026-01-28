# Sales Exploratory Data Analysis (EDA)

## Project Overview

This project contains an Exploratory Data Analysis (EDA) of sales data, aimed at uncovering critical insights into revenue drivers, customer value, and overall business performance. By analyzing various metrics related to products, customers, orders, and time, this notebook transforms raw sales data into actionable business intelligence.

## Purpose

The primary purpose of this EDA is to establish a robust foundation for strategic decision-making, potential feature engineering for machine learning models, and future sales forecasting. It provides a clear and comprehensive understanding of current sales dynamics and performance.

## Key Business Questions Addressed

This EDA specifically addresses the following questions:

*   Which products are the primary revenue generators, and which contribute least?
*   Which customers are most valuable and contribute significantly to overall sales?
*   How does sales performance evolve over time, and are there noticeable trends or seasonality?
*   What is the overall distribution of revenue across customers, highlighting dependency and potential?
*   Where should the business strategically focus to maximize growth and profitability?

## Data Sources

The analysis utilizes several CSV files, each focusing on a specific aspect of sales performance:

*   `revenue_per_product.csv`: Contains product-level sales data.
*   `revenue_per_customer.csv`: Contains customer-level sales data.
*   `categorywise_performance.csv`: Contains sales data aggregated by product category.
*   `orderTrend_monthly.csv`: Contains monthly sales trend data.

## Key Findings & Business Implications

The EDA reveals several crucial insights:

*   **Product Revenue Concentration:** Revenue is highly concentrated, with the top two products (Laptop X, Smartphone Y) accounting for nearly 73% of total revenue. This highlights a significant dependency risk and suggests a need to evaluate the contribution of lower-performing products.

*   **Customer Lifetime Value & Concentration:** A small cohort of customers (the top 5) generates approximately 80% of the total revenue. This underscores the importance of focusing on high-value accounts for retention and growth, while also exploring strategies to cultivate mid-tier customers.

*   **Revenue Distribution Across Customers:** The revenue distribution is heavily right-skewed, indicating that a few high-value customers contribute a disproportionately large share of revenue. This means the business is highly dependent on these key accounts.

*   **Monthly Revenue Trend:** Monthly revenue exhibits significant fluctuations and high volatility, rather than a steady growth pattern. Sales performance is driven by occasional spikes, suggesting reliance on specific events or product cycles.

*   **Strategic Focus:** The analysis suggests that strategic efforts should prioritize maintaining the success of high-performing products and customers, mitigating risks associated with revenue concentration, and exploring opportunities for growth through targeted campaigns for smaller customers or upselling.

## How to Run the Notebook

To run this EDA locally or in a Colab environment:

1.  **Clone the repository:**
    ```bash
    git clone <url>
    cd <eda-projects>
    ```
2.  **Open in Google Colab:** Upload the `.ipynb` file to Google Colab, or open it directly if you're viewing it on GitHub with Colab integration.
3.  **Upload Data Files:** The notebook expects the data files (`revenue_per_product.csv`, `revenue_per_customer.csv`, `categorywise performance.csv`, `orderTrend_monthly.csv`) to be uploaded. Run the `files.upload()` cells to upload them.
4.  **Execute Cells:** Run the cells sequentially to reproduce the analysis and visualizations.

## Technologies Used

*   Python 3
*   Pandas (for data manipulation and analysis)
*   Matplotlib (for data visualization)
*   Google Colab (for the development environment)




