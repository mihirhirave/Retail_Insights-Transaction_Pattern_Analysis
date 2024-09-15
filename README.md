# Retail Insights: Transaction Pattern Analysis

## Overview
This project analyzes retail transaction data to uncover purchasing patterns and associations between products. It employs market basket analysis techniques, including frequent itemset mining and association rule generation, to derive actionable insights for strategic planning in retail.

## Dataset
The dataset contains transaction records from a retail store, including various products such as:
- Candy Bars
- Magazines
- Toothpaste
- Greeting Cards
- Perfume
- Toothbrushes
- and more

## Analysis Steps

1. **Data Preprocessing**
   - Conversion of transaction data into a binary format (True/False for each item in each transaction)

2. **Frequent Itemset Mining**
   - Identification of frequent itemsets using a minimum support threshold of 1%

3. **Association Rule Generation**
   - Generation of rules with a minimum confidence of 10%

4. **Metric Calculation and Interpretation**
   - Calculation and interpretation of support, confidence, lift, leverage, and conviction for generated rules

5. **Rule Analysis**
   - In-depth analysis of top rules based on different metrics (confidence, lift, leverage, conviction)

## Key Findings

- Identification of frequently co-purchased items (e.g., Candy Bars, Magazines, Toothpaste, Greeting Cards)
- Discovery of unexpected associations (e.g., Perfume and Toothbrushes)
- Insights into the effectiveness of different association metrics for retail data

## Tools and Libraries Used

- Python
- Pandas (for data manipulation)
- MLxtend (for association rule mining)
- Matplotlib or Seaborn (for visualizations, if any)

## Strategic Insights

1. Co-location strategy for top-selling items
2. Placement of impulse purchase items near checkout areas
3. Creation of product bundles based on strong associations
4. Implementation of targeted promotions for less frequently purchased items

## Future Work

- Incorporate temporal analysis to identify seasonal trends
- Segment analysis based on customer demographics or purchase frequency
- Experiment with different thresholds for support and confidence
- Integrate pricing data to analyze impact on purchase associations
