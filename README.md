# Retail Sales Exploratory Data Analysis (EDA)

## Project Overview
This project explores retail sales data using Python to identify sales trends, product performance, regional differences, profitability, and customer rating patterns. It demonstrates a beginner-friendly exploratory data analysis (EDA) workflow, from data quality checks to visualizations and business insights.

**Note:** This project uses a synthetic dataset created for learning and portfolio practice. It does not represent real company transactions or actual business performance.

## Objectives
- Inspect the dataset structure and data quality.
- Calculate overall sales, profit, and customer rating metrics.
- Compare sales and profit across product categories and regions.
- Analyze monthly sales trends.
- Evaluate sales channels and payment methods.
- Identify top-performing products.
- Compare profit margins across product categories.
- Explore average customer ratings by product.

## Tools and Technologies
- Python
- Jupyter Notebook
- Pandas — data loading, cleaning checks, grouping, and analysis
- NumPy — numerical computing
- Matplotlib — data visualization
- Seaborn — installed for potential additional visual analysis

## Dataset
The dataset contains **15,000 rows and 14 columns**, covering a synthetic two-year period from January 2024 to December 2025.

Key fields include:
- Order_ID and Order_Date
- Product and Category
- Region and Sales_Channel
- Payment_Method
- Quantity, Unit_Price, and Discount
- Sales, Cost, and Profit
- Customer_Rating

## Data Quality Checks
- Checked the dataset dimensions and column data types.
- Checked for missing values.
- Checked for duplicate rows.
- Reviewed descriptive statistics for numerical columns.
- Converted Order_Date to a datetime format for monthly analysis.

The checks found no missing values or exact duplicate rows. Negative profit values were retained because they may represent loss-making transactions and should not automatically be treated as errors.

## Key Findings
- **Total sales:** ₹787,905.45
- **Total profit:** ₹248,635.78
- **Average customer rating:** 3.98 out of 5
- **Top sales category:** Clothing, with ₹240,342.28 in sales.
- **Top region by sales:** South, with ₹191,100.77 in sales.
- **Top sales channel:** Online, with ₹382,961.50 in sales.
- **Top product by sales:** Jacket, with ₹76,410.85 in sales.
- **Highest-sales month:** July 2024, with ₹35,199.30 in sales.
- **Lowest-sales month:** February 2025, with ₹27,854.36 in sales.

These are descriptive findings from the synthetic dataset, not evidence of real-world market behavior.

## Visualizations
The notebook includes charts covering:
- Total sales by product category
- Monthly sales trends
- Total sales by region
- Total sales by sales channel
- Top five products by sales
- Profit margin by product category
- Total sales by payment method
- Average customer ratings by product

## Business Recommendations
Based on the patterns in this practice dataset:
1. Investigate what factors contribute to Clothing's higher sales and profit.
2. Explore whether the strong Online channel performance is consistent across products and regions.
3. Review monthly sales fluctuations before planning promotions or inventory.
4. Monitor product-level profitability alongside sales instead of judging performance by revenue alone.
5. Consider customer ratings alongside sales and profit when evaluating product performance.

These recommendations are illustrative. Real business decisions would require validated business data and additional analysis.

## How to Run the Project
1. Download or clone this repository.
2. Install the required libraries:
   `pip install pandas numpy matplotlib seaborn`
3. Open Jupyter Notebook.
4. Open `Retail_Sales_EDA.ipynb`.
5. Ensure the CSV dataset is accessible at the path used in the notebook. If necessary, update the file path in the data-loading cell.
6. Run the notebook cells in order.

## Project Files
- `Retail_Sales_EDA.ipynb` — notebook containing the analysis, code, findings, and visualizations.
- `Retail_Sales_EDA.csv` — synthetic dataset used for analysis.
- `README.md` — project documentation.

## Skills Demonstrated
Python, Pandas, NumPy, data quality checks, exploratory data analysis, data aggregation, descriptive statistics, data visualization, business insight generation, and analytical communication.

## Conclusion
This project demonstrates a structured approach to exploring retail data, summarizing performance, and communicating findings through visualizations. It represents a learning and portfolio project and can be extended with SQL analysis, interactive dashboards, or more advanced statistical techniques.
