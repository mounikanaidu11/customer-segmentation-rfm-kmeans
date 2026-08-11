# Customer Segmentation Analysis (RFM + K-Means Clustering)

## Objective
Segment an e-commerce customer base into distinct groups based on purchasing behaviour using RFM (Recency, Frequency, Monetary) analysis and K-Means clustering, enabling targeted marketing strategies.

## Tech Stack
- Python
- pandas, NumPy
- scikit-learn (KMeans, StandardScaler)
- matplotlib, seaborn
- Jupyter Notebook

## Process
1. Loaded and cleaned the retail sales dataset (handled missing values, duplicates)
2. Calculated descriptive stats — average purchase value, purchase frequency, customer lifetime value
3. Engineered RFM features (Recency, Frequency, Monetary) per customer
4. Standardized features using StandardScaler
5. Applied K-Means clustering, using the Elbow Method to determine the optimal number of clusters (K=4)
6. Visualized clusters using scatter plots (Recency vs Monetary, Frequency vs Monetary)
7. Profiled each cluster (mean RFM values, customer type)
8. Visualized cluster sizes with a bar chart
9. Derived actionable marketing recommendations per customer segment

## Key Findings
Four customer segments were identified:
- **Recent High-Value Customers** — reward and retain
- **Lapsed High-Value Customers** — win-back campaigns
- **Recent Low-Value Customers** — upsell and cross-sell
- **Lapsed Low-Value Customers** — low-cost re-engagement

## Files
- `customer_segmentation.ipynb` — full analysis notebook
