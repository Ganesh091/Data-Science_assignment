# Data-Science_assignment
1. Project Overview
   
The project aims to:

Analyze transactional, product, and customer data using EDA.
Build a Lookalike Model to recommend similar customers based on transactional behavior.
Perform Clustering to segment customers into meaningful groups.

2. Methodology
EDA:
Merged customer, product, and transaction datasets for analysis.
Identified patterns in total transaction values, product categories, and regional behavior.
Visualized key trends using boxplots and count plots.

Lookalike Model:
Built a customer-product matrix.
Calculated cosine similarity to identify similar customers.
Recommended top 3 lookalike customers for the first 20 customers.

Clustering:
Grouped customers based on aggregated transactional data (Total Value, Quantity, and Price).
Applied KMeans Clustering with 4 clusters.
Evaluated clustering quality using the Davies-Bouldin Index.
