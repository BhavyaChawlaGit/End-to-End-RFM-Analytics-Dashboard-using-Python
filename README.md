# RFM-Analytics-Dashboard-using-Python


This repository contains code for an RFM Analysis Dashboard using Python, Dash, and Plotly. The dashboard provides various visualizations to analyze customer segments based on RFM (Recency, Frequency, Monetary) scores.

- Recency (the date they made their last purchase)
- Frequency (how often they make purchases)
- Monetary value (the amount spent on purchases)

![image](https://github.com/BhavyaChawlaGit/End-to-End-RFM-Analytics-Dashboard-using-Python/assets/112718303/8129102d-1e55-4663-a62e-4fd3717a50fc)


## Dataset

The dataset used for this analysis is `rfm_data.csv`, which includes the following columns:

- `CustomerID`: Unique identifier for each customer
- `PurchaseDate`: Date of the purchase
- `TransactionAmount`: Amount spent in the transaction
- `ProductInformation`: Details about the purchased product
- `OrderID`: Unique identifier for each order
- `Location`: Location of the purchase

## Steps Taken

- `Import Libraries and Load Data`: Import necessary libraries and load the dataset.
- `Data Preparation`: Convert date columns to datetime and calculate recency, frequency, and monetary values.
- `Calculate RFM Scores`: Assign scores to recency, frequency, and monetary values based on defined criteria.
- `RFM Segmentation`: Calculate total RFM score and create customer segments.
- `Visualize Segment Distribution`: Use visualizations to show segment distribution.
- `Analyze Customer Segments`: Assign strategic segments and visualize their distribution.
- `Compare Segment Scores`: Calculate and visualize average RFM scores per segment.


## Analysis and Visualizations

1. **RFM Value Segment Distribution**:
   - Bar chart showing the distribution of customers across different RFM value segments (Low-Value, Mid-Value, High-Value).

![image](https://github.com/BhavyaChawlaGit/End-to-End-RFM-Analytics-Dashboard-using-Python/assets/112718303/fe098956-a59c-47a2-b447-004bf50c1b21)


2. **Distribution of RFM Values within Customer Segment**:
   - Treemap showing customer segments (Champions, Potential Loyalists, At Risk Customers, Can't Lose, Lost) by value.

![image](https://github.com/BhavyaChawlaGit/End-to-End-RFM-Analytics-Dashboard-using-Python/assets/112718303/245ada63-d0a6-4b46-92df-14de0225c8bf)


3. **Correlation Matrix of RFM Values within Champions Segment**:
   - Heatmap showing the correlation matrix for Recency, Frequency, and Monetary scores within the Champions segment.

![image](https://github.com/BhavyaChawlaGit/End-to-End-RFM-Analytics-Dashboard-using-Python/assets/112718303/31740e86-44f9-4896-9460-12e4b2b1a265)


4. **Comparison of RFM Segments**:
   - Bar chart comparing the number of customers in each RFM segment.

![image](https://github.com/BhavyaChawlaGit/End-to-End-RFM-Analytics-Dashboard-using-Python/assets/112718303/dbe322d9-0c7a-44e8-aa3c-9ad9bd2f0228)

5. **Comparison of RFM Segments based on Scores**:
   - Grouped bar chart comparing average Recency, Frequency, and Monetary scores across different RFM segments.

![image](https://github.com/BhavyaChawlaGit/End-to-End-RFM-Analytics-Dashboard-using-Python/assets/112718303/01954f0c-b83f-4853-a300-eaa5a3c59800)



## Installing Dependencies

To install the required Python packages, run the following command:

```
pip install -r requirements.txt
```

## Running the Application
To run the application, navigate to the directory containing rfm.py and run the following command:
```
python rfm.py
```


Dash would run on http://127.0.0.1:8052/
