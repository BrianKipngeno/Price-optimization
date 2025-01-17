# Price-optimization using dynamic pricing

This repository contains an end-to-end analysis of price optimization using a dataset of sales, pricing, and competition data. The goal is to identify the most effective pricing strategies to maximize revenue while maintaining competitiveness.

# 📁 Project Overview

Price optimization is a strategic approach that leverages data on sales, costs, competition, and market trends to:

- Predict demand changes
- Analyze price elasticity
- Enable businesses to set optimal prices

Key methodologies include:

Competitive analysis: Monitoring market positioning to identify pricing trends.

Customer segmentation: Differentiating customers by their willingness to pay.

Mathematical optimization algorithms: Determining the best price points.

This project uses a dataset to explore pricing strategies and compares performance between a store and its competitors.


**Dataset**

The dataset used in this project contains the following features:

- Fiscal_Week_Id: The fiscal week identifier.
- Store_Id: The store identifier.
- Item_Id: The item identifier.
- Price: The price of the item at our store.
- Item_Quantity: The quantity of the item sold.
- Sales_Amount_No_Discount: Sales amount without discount.
- Sales_Amount: Sales amount after discounts.
- Competition_Price: The price of the item at a competing store.
  
Dataset Link: https://bit.ly/3WmEDfg


# 📊 Steps and findings

1. **Data eploration**

    - Loaded the dataset and examined its structure and properties
    - The dataset contains 100,000 entries and 9 columns.
    - It includes pricing and sales data for comparison between the store and competitors.
      
2. **Price distribution comparison**
   
    - Analyzed the distribution of prices for our store versus competitors.
    - Competitor prices are generally higher, peaking in the 100-150 and 200-250 price ranges.
    - Our store’s prices are more evenly distributed with peaks around 100-150.

3. **Price vs. Sales Analysis**
   
    - Visualized the relationship between price and sales amounts for both the store and competitors.

    - Competitors maintain higher and more consistent sales across various price points.
    - Our store shows greater variability in sales, indicating room for optimization.

4. **Price Changes Over Time**
   
    - Compared weekly price trends for our store and competitors.

    - Competitor prices remain stable with a slight upward trend.
    - Our store’s prices fluctuate significantly, contributing to inconsistent sales performance.

5. **Price Elasticity of Demand**

    - Calculated price elasticity to measure the sensitivity of demand to price changes.

    - High variability in elasticity suggests other factors like promotions or market conditions influence demand.

6. **Total Sales Comparison**
    - Compared total sales amounts for our store and competitors:
          - Our Store: $114,100,500
          - Competitors: $696,209,700
    - Competitors generate significantly higher revenue due to effective pricing strategies.

7. **Sales by Price Bracket**
    - Grouped sales into price brackets for both the store and competitors.
    - Competitors outperform in most price brackets, particularly in higher price ranges.
# 🔧 Technologies Used

**Python**: Data analysis and visualization.

**Libraries**:

- pandas and numpy for data manipulation.
- matplotlib and seaborn for static visualizations.
- plotly for interactive visualizations.

# 📈 Dynamic pricing model

A dynamic pricing model is introduced to simulate the performance of optimized pricing strategies. The steps include:

1. **Defining price elasticity metrics**: Calculate the optimal price point based on demand sensitivity.
2. **Simulating scenarios**: Adjust prices dynamically to maximize revenue while maintaining market competitiveness.
3. **Evaluating performance**: Measure the impact of dynamic pricing on total sales and revenue.


# 🛠️ Future Improvements

1. Implement the dynamic pricing model and evaluate its performance.
2. Incorporate additional factors like seasonality and promotions.
3. Develop a recommendation system for optimal pricing strategies.


# 📬 Contact
For questions or collaboration opportunities, feel free to reach out:

Author: Brian Kipngeno

Email: briankosgey@gmail.com
