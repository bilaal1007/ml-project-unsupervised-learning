# machine_learning_project-unsupervised-learning

## Project Outcomes
-This repository houses a comprehensive unsupervised learning project focusing on a dataset from a wholesale distributor. It aims to analyze annual spending across various product categories by the distributor's clients. The project utilizes advanced data analytics techniques to uncover patterns in customer behavior, enabling strategic business decisions.

### Project Description:
We leverage the "Wholesale Customers" dataset from Kaggle, which contains data on the annual spending of different clients in monetary units across categories like Fresh, Milk, Grocery, Frozen, Detergent_Paper, and Delicassen.


The data set for this project is the "Wholesale Data" dataset containing information about various products sold by a grocery store.
The project will involve the following tasks:

-	Exploratory data analysis and pre-processing: We will import and clean the data sets, analyze and visualize correlations between variables via heat maps, impute missing data with the mean values throughout, and identify outliers using boxplots.

-	Unsupervised learning: We will use the Wholesale Data dataset to perform k-means clustering, hierarchical clustering, and principal component analysis (PCA) to identify patterns and group similar data points together. We will determine the optimal number of clusters using the elbow method and silhouette score and communicate the insights gained through data visualization.

-Furthermore, using the optimal amount of clusters we ran Kmeans clustering and applied the 3 most impactful principal components to plot a 3d scatter plot showing the variance and distribution of the clusters based on the 3 main principal components used.

![image](https://github.com/bilaal1007/ml-project-unsupervised-learning/assets/143028132/69a089b4-9bed-46df-b139-2a0759a9d991)

*an important note:
-  Clustering in this data set are formed based on similarity of the data points, this would indicate that these grocery companies are spending similar amounts on different grocery related products. This could also be indicitive of similar spending patterns of customers which would mean that certain wholesale sales that have little variance and that are clustered together are staple items in a household (milk, detergent products etc) or very popular among their customers etc. 

 I kept outliers to preserve data but log transformed them to limit their skew on the restof the data 

The ultimate goal of the project is to gain buisness insights from the data sets and communicate these insights to stakeholders using appropriate visualizations and metrics to make informed decisions on wholesale data based on the business questions asked.

Key insights derived from this project on wholsale data 
Customer Spending Habits: We found a big cluster in the scatter plot that shows a lot of customers don't really spend much on 'Fresh' and 'Milk' products. Looks like they're putting their money into other stuff instead.

Product Correlations: From the correlation matrix, we can see that there's a pretty strong link between 'Grocery' and 'Detergent Paper'. Seems like these products often get bought together. This could be a big help for thinking about cross-selling strategies and how to manage our inventory.

Principal Component Analysis: The 3D clustering model points out that the factors in Principal Component 1, which is mostly about 'Grocery', 'Milk', and 'Detergent Paper', have the highest sales correlation. This tells us that these categories are super important in our sales mix and we should probably focus on them more in our stocking and marketing.

Market Competition and Strategy: There's a lot of spending in Principal Component 1 among wholesalers, especially on 'Milk', 'Detergent Paper', and 'Grocery'. This means the competition's pretty fierce in these areas. We might wanna think about bringing in some special items or maybe changing our prices to get more sales and stand out from the crowd.
