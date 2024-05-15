# RFM-Analytics-Dashboard-using-Python


This repository contains code for an RFM Analysis Dashboard using Python, Dash, and Plotly. The dashboard provides various visualizations to analyze customer segments based on RFM (Recency, Frequency, Monetary) scores.

## Dataset

The dataset used for this analysis is `rfm_data.csv`, which includes the following columns:

- `CustomerID`: Unique identifier for each customer
- `PurchaseDate`: Date of the purchase
- `TransactionAmount`: Amount spent in the transaction
- `ProductInformation`: Details about the purchased product
- `OrderID`: Unique identifier for each order
- `Location`: Location of the purchase


## Analysis and Visualizations

1. **RFM Value Segment Distribution**:
   - Bar chart showing the distribution of customers across different RFM value segments (Low-Value, Mid-Value, High-Value).

2. **RFM Customer Segments**:
   - Treemap showing customer segments (Champions, Potential Loyalists, At Risk Customers, Can't Lose, Lost) by value.

3. **Distribution of RFM Values within Champions Segment**:
   - Box plots displaying the distribution of Recency, Frequency, and Monetary scores for customers in the Champions segment.

4. **Correlation Matrix of RFM Values within Champions Segment**:
   - Heatmap showing the correlation matrix for Recency, Frequency, and Monetary scores within the Champions segment.

5. **Comparison of RFM Segments**:
   - Bar chart comparing the number of customers in each RFM segment.

6. **Comparison of RFM Segments based on Scores**:
   - Grouped bar chart comparing average Recency, Frequency, and Monetary scores across different RFM segments.

## How to Run the Code

python3 rfm.py

Dash would run on http://127.0.0.1:8052/