# Cluster-Analysis-for-Company-X

Problem Statement -

Company X, experiencing healthy annual growth in sales, has been trying to identify how to increase net profit margins as a percentage to total revenue. To do this, senior management wants to identify customers that are profitable and non-profitable.  By doing so, Company X can increase efforts on profitable customers.  Any customers that should be profitable through traditional means (Gross Profit Dollars) not categorized as profitable will be brought to light.
We will apply clustering algorithms on the customer population to bring like groups of customers together. Clustering will help us decide which set of customers are most profitable to the company. Not only will ideal clusters of customers be identified, but clusters where a little bit of resources and time will yield a huge boost in profitability could be uncovered. These customers would be low hanging fruit, where a little effort can yield a huge return.   Querying the Sales database from the company’s Business Intelligence tool, Phocas BI, Bids, Customers, and Measures were extracted per customer.  Leveraging R studio, we applied the K-Means algorithm. Through the elbow chart, we identified that 6 clusters would be ideal to group the customers. We exported the output from R to Tableau for visualization of the clusters.  Furthermore, we analyzed these clusters and created various charts using Tableau to get an understanding of which clusters of customers should be focused on and provided more resources from our company.  

Data Decription-

The dataset contains approximately 5000 customer IDs that we analyzed; however, a company cannot focus and commit all their resources to all 5000 customers. 

Method Utilized-

Pre-processing 
  o Identify and remove non-contributing customers 
  o Check data structure
Unsupervised clustering 
  o Attribute selection 
  o K-Means 
  o Optimal K-value 
  o Output
Visualization 
  o Identify “model customers” clusters 
  o Identify “dogs” customers 
  o Identify “low hanging fruit” customers to focus on
Conclusion 
  o Recommendations 
  o Findings & Results 
  o Future Scope and Limitations 
