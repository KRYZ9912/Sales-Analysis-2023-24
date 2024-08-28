# Sales_Analysis_2023-24
Sales Prediction and Package Size Analysis: A data-driven approach to optimize sales forecasting and inventory management
# Sales Prediction and Package Size Analysis

## Project Overview
This project develops a regression model to predict sales for various product categories and analyzes package size performance using sales data from 2023 and 2024. The aim is to optimize inventory management and improve sales forecasting.

## Key Objectives
1. Develop a regression model to predict sales for various categories
2. Parse and analyze package size information from Inventory ID
3. Determine optimal package sizes and identify sizes for potential discontinuation

## Data and Methodology
- Combined sales data from 2023 and 2024
- Extracted package size information from Inventory ID
- Implemented comprehensive data cleaning processes
- Final dataset shape: (354,298, 12)

## Key Findings
1. Model Performance:
   - Linear Regression: R2 Score of 0.1114
   - Random Forest: R2 Score of 0.9061, showing strong predictive capability

2. Feature Importance:
   - Package Size (31.43%)
   - Genus (22.82%)
   - Quantity (21.09%)

3. Package Size Analysis:
   - Top performing sizes: 72, 58, 79, 115, 4
   - Underperforming sizes: 16, 90, 18, 169, 82

## Recommendations
1. Focus on top-performing package sizes for production and marketing
2. Evaluate underperforming sizes for potential restructuring or discontinuation
3. Utilize the Random Forest model for sales forecasting and inventory management
4. Implement seasonal inventory adjustments based on observed monthly sales trends
5. Conduct regular reviews of package size performance

## Technologies Used
- Python (jupyter Notebook)
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## Future Work
- Explore advanced machine learning techniques for improved prediction accuracy
- Conduct more granular analysis of package size performance within specific product categories

## Author
Krishna Prasad

