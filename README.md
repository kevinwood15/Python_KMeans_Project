# Python_KMeans_Project

This project uses the KMeans ML algorithm to identify segments of the broader population that form the core customer base of a company. 

I leverage two datasets, one of the general population, and one of actual customers of the company. The  data is messy, so I clean it in preparation for the analysis. I engineer new variables when necessary, address missing  values on features and rows and re-encode categorical features into dummies.  

Using the general population data, I apply feature scaling and use principal component analysis to reduce the dimensionality. I reduce 81 features down to 33, which explains 85% of the variance. 

I apply a K means model on a 25% random sample and use the elbow method to decide upon an optimal cluster number (k=21 clusters). 

Lastly, I use the fits from the general population to clean, transform, and cluster the customer data and examine differences between the general population and customer data, before drawing conclusions about the typical customers, and forming recommendations on how to tailer avertising to a target group. 
