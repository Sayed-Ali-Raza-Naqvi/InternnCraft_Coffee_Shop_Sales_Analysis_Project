# Coffee Shop Sales Profitability Analysis
## Overview
This project provides a comprehensive analysis of transaction data from a coffee shop to identify profitable and loss-making products, forecast future profits, and understand trends over time. The analysis includes data cleaning, exploratory data analysis, profitability analysis, and predictive modeling.

## Objectives
- Determine Product Profitability: Analyze historical transaction data to identify profitable and loss-making products.
- Develop Strategies: Identify strategies to increase profit margins and mitigate losses.
- Forecast Future Profits: Use predictive modeling techniques to forecast future profits and understand sales trends.

## Dataset Description
The dataset includes transactional data with the following features:
- transaction_id: Unique identifier for each transaction.
- transaction_date: Date of the transaction.
- transaction_time: Time of the transaction.
- transaction_qty: Quantity of products sold.
- store_id: Identifier for the store.
- store_location: Location of the store.
- product_id: Unique identifier for the product.
- unit_price: Price per unit of the product.
- product_category: Category of the product.
- product_type: Type of the product.
-product_detail: Detailed description of the product.

## Steps and Methodology
### 1. Data Cleaning
- Initial Review: Check for missing values, duplicates, and data type mismatches.
- Categorical Data Standardization: Standardize categorical variables for consistency.
- Data Integrity Check: Identify and address anomalies such as negative quantities or unit prices.
- Final Cleaned Dataset: Save the cleaned dataset for analysis and modeling.
### 2. Exploratory Data Analysis (EDA)
- Descriptive Statistics: Summarize the dataset to understand distributions and variability.
- Correlation Matrix: Analyze relationships between numerical variables.
- Transaction Distribution Over Time: Examine transaction patterns by day of the week.
- Sales Distribution by Store Location: Identify sales performance by store location.
- Revenue Analysis by Product Category: Analyze revenue contribution by product category.
### 3. Time-Based Sales Trends: Identify trends and seasonal patterns in sales.
- 3. Profit/Loss Analysis
- Assumption-Based Cost Estimation: Estimate costs based on an assumed profit margin and calculate profit.
- Gross Margin Analysis: Evaluate the profitability of different products and categories.
### 4. Predictive Modeling for Profit Forecasting
- Feature Selection: Choose relevant features based on their correlation with profit.
- Model Training: Train models using Random Forest, Linear Regression, and Lasso Regression.
- Model Evaluation: Assess model performance using metrics such as Mean Absolute Error (MAE) and R-squared (R²).
- Feature Importances and Coefficients: Determine the significance of features from different models.
### 5. Time Series Forecasting
- Time-Based Sales Forecasting: Forecast future sales using the ARIMA model.
- Seasonal Trend Analysis: Analyze seasonal trends to inform inventory and marketing strategies.
## Recommendations
- Boost Sales Volume: Implement strategies to increase transaction quantities.
- Optimize Pricing: Review and adjust unit prices to maximize profitability.
- Focus on High-Impact Products: Invest in and promote products with strong positive impacts on profitability.
- Reevaluate Low-Impact Features: Reassess features with low or zero importance.
- Analyze and Address Decline: Investigate and address factors causing sales decline.
- Capitalize on Seasonal Trends: Align marketing and inventory management with seasonal trends.
## Conclusion
This analysis and forecasting provide actionable insights for improving profitability, reducing losses, and optimizing operations. By following the recommendations and leveraging predictive models, the company can make informed decisions to enhance its financial performance.

