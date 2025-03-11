# Made by: Aarav Agarwal, IBCP-XI (WACP ID - 1000197)
# CRS: Artificial Intelligence
# Course: Data Mining
# School: Birla Open Minds International School, Kollur

## Summative Assessment 5

### Overview
In this project, I performed Market Basket Analysis on Amazon product data in order to derive insights into customer behavior, pricing patterns and product associations. The analysis includes EDA, K-Means Clustering, Apriori Algorithm Association Rule Mining to find the purchasing trends. <br/>

The live app may be found here: https://aarav-agarwal-sa5.streamlit.app/

### Scope

- To analyze amazon product data, such as the pricing, ratings, categories, etc. <br/>
- To discover pricing distributions, discounts, impacts and sales trends <br/>
- Cluster products based on their similarity by using K-Means clustering <br/>
- Identify frequent item sets using Apriori Algorithm for recommendation insights <br/>
- Visualize key trends in the customer behaviors and product performances. <br/>

### Preprocessing steps

- Removing duplicate records <br/>
- Cleaned price columns by removing symbols and converted it into a numeric form <br/> 
- Imputed missing values <br/>
- Encoded categorical variables <br/>
- Normalized numerical data with MinMaxScaler <br/>
- Created discount percentage column <br/>

### Visualizations

EDA: <br/>
- Histogram and box plots for discounted_price, actual_price, ratings <br/>
- Scatter plot for discounted price and actual price <br/>
- Bar charts for category distribution, popular products and rating trends <br/>
- Heatmap to correlate many different features <br/>

K-Means Clustering: <br/>
- Elbow method to determine optimal k <br/>
- Clustered products based on their price, rating and discount percentage <br/>
- Identified distinct product groups (e.g. premium, budget, high discount) <br/>

Apriori Algorithm Association Rule Mining: <br/>
- Extracted frequent item sets using apriori() <br/>
- Generated association rules (e.g. If a customer buys product A, they may buy product B) <br/>
- Confidence and lift analysis helps to identify strong product relationships <br/> 


### Deployed Streamlit app overview

- Select analysis type (EDA, clustering, association rules, user behavior) <br/>
- Ability to see interactive charts and heatmaps <br/> 
- Explore top selling products and categories <br/>
- Perform real time clustering to segment products <br/>
- Find frequent product associations <br/>


### Citations
https://ijaem.net/issue_dcp/Market%20Basket%20Analysis%20Using%20Apriori%20Algorithm%20with%20Pruning%20Approach.pdf <br/>
https://docs.streamlit.io/ <br/>
https://chatgpt.com <br/>
http://rasbt.github.io/mlxtend/user_guide/frequent_patterns/apriori/ <br/>
https://scikit-learn.org/stable/modules/clustering.html <br/>
