# Analyzing Customer Shopping Trends Using Statistical Methods

This project involves a detailed analysis of customer shopping behavior using statistical methods. The study explores trends and patterns in supermarket transactions, aiming to provide actionable insights for strategic decision-making in retail.

## Features

- **Dataset**: 
  - Transaction data includes invoice ID, branch, city, customer type, gender, product line, unit price, quantity, tax, total, date, payment method, and customer ratings.
  - Provides insights into customer behavior, sales patterns, and product performance.

- **Statistical Analysis**:
  - Chi-Square, Kruskal-Wallis, Paired t-test, Independent t-test, and ANOVA to test hypotheses.
  - Regression analysis using Linear Regression and Lasso Regression to identify key factors influencing sales.

- **Data Visualizations**:
  - Histograms, scatter plots, box plots, pie charts, bar charts, and correlation matrices.
  - Visual representations highlight sales distributions, relationships, and trends.

## Objectives

- Analyze customer behavior and shopping trends.
- Identify factors influencing sales, including pricing, product line, and taxation.
- Provide insights into optimizing inventory, pricing strategies, and customer engagement.

## Key Insights

- **Pricing and Quantity**:
  - Unit price and quantity positively impact total sales, highlighting the importance of strategic pricing.
  
- **Taxation**:
  - A strong positive correlation exists between tax and sales, indicating high-value items drive revenue.

- **Customer Ratings**:
  - Ratings show a trend toward positive feedback, though they do not directly correlate with sales.

## Methods

1. **Data Preprocessing**:
   - Handled missing values, outliers, and irrelevant data.
   - Applied normalization, tokenization, and feature extraction techniques.

2. **Statistical Methods**:
   - Hypothesis testing to explore relationships between categorical and quantitative variables.
   - Regression models (Linear and Lasso) to predict total sales based on independent variables.

3. **Visualization**:
   - Used various charts to represent data distributions and relationships.
   - Scatter plots and correlation matrices identify trends and strengths of relationships.

## Results

- Lasso Regression provided a slightly better fit than Linear Regression by selecting the most impactful predictors.
- Taxation and product quantity emerged as critical factors influencing sales.
- Visualizations revealed patterns in product popularity, branch performance, and customer demographics.

## Tools & Technologies

- Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, and Statsmodels
- Jupyter Notebook for analysis and visualization

## Future Work

- Enhance regression models to account for complex relationships.
- Apply real-time data monitoring for sales trends.
- Explore advanced machine learning techniques for predictive analysis.

## License

This project is licensed under the [MIT License](LICENSE).

