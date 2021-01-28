# Telco_Customer_Churn_Clustering

** Full notebook: https://github.com/Jess625/Telco_Customer_Churn_Clustering/blob/main/Telco_Customer_Churn_Clustering.ipynb
** NOTE: If GitHub isn't rendering the notebook, see full notebook here: https://nbviewer.jupyter.org/github/Jess625/Telco_Customer_Churn_Clustering/blob/main/Telco_Customer_Churn_Clustering.ipynb

## 📊 Dataset: 
* https://www.kaggle.com/blastchar/telco-customer-churn?select=WA_Fn-UseC_-Telco-Customer-Churn.csv
* 7K+ records containing customer details for a Telco company and whether the customer churned or not in the last month

## ✅ Goals of Analysis:
* Clean and prepare data for cluster analysis
* Conduct feature selection (there are 21 attributes and it's best to find the attributes most closely related to churn to input into the k-means clustering algorithm)
* Employ the Elbow Chart Method to identify the best number of clusters to use as the k-means parameter
* Analyze and describe clusters

## 🔍 Initial Results:
* Cluster 1: Most at risk to churn
    * Highest percentage of churned customers
    * Shortest average tenure
    * Lowest amount of avg monthly charges
    * Lowest amount of avg total charges
    * Highest percentage of month to month contracts
    * Lowest percentage of Fiber Optic Internet users
    * Lowest percentage enrolled in paperless billing
<br />
<br />
   
* Cluster 2: Least at risk to churn
    * Highest percent enrolled in paperless billing
    * Highest percent enrolled in tech support
    * Highest percent enrolled in online security
    * Nearly 77% enrolled in Fiber Optic Internet (highest of any cluster)
    * Longest average tenure
    * Highest avg monthly charges
    * Highest avg total charges
    * Lowest number of month to month contracts
<br />
<br />
* Cluster 3: Somewhat likely to churn
    * This group is basically in the middle of all the above mentioned qualities between cluster 1 and 2
