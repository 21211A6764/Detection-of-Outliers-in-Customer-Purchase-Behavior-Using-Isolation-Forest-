# Findings 
High Purchase Amount Outliers: Customers with extremely high purchase amounts and frequencies were detected as outliers. These could be bulk buyers or fraudulent activities. 
Low Annual Income Outliers: Some outliers have very low annual income but high purchase amounts, indicating potential financial risk or fraudulent activities. 
Product Category and Loyalty Program: Outliers are distributed across different product categories and loyalty program statuses, indicating no strong correlation with these features. 
Count of Outliers: The analysis identified 5 outliers and 95 inliers in the dataset. 
Characteristics of Outliers: Outliers generally exhibit significant deviations in one or more features compared to inliers. For example, outliers may have unusually high or low AnnualIncome, PurchaseAmount, or PurchaseFrequency. 
Visual Patterns: Scatter plots of AnnualIncome vs PurchaseAmount reveal that outliers are dispersed at the extremes of these distributions. Pair plots show that outliers tend to cluster away from the dense regions of inliers, indicating abnormal behavior. 
Box Plot: Outliers display a wider range of annual income, indicating significant deviation. 
Heatmap: Highlights the interrelationships between features, helping to understand the influence of correlated features on outlier detection. 

# Business Insights 
Targeted Marketing: Genuine outliers with high purchases should be considered for exclusive offers or loyalty programs. Customers identified as outliers can be further analyzed to understand their unique purchasing behavior. This can help in creating targeted marketing strategies to cater to their specific needs. 
Fraud Detection: Investigate customers with unusually high purchase amounts and frequencies for potential fraud. Outliers could potentially indicate fraudulent activities. Monitoring these customers closely and implementing additional verification steps could help in mitigating fraud risks. 
Customer Segmentation: Understanding the characteristics of outliers can aid in refining customer segmentation strategies. For instance, highspending outliers might be classified as premium customers and provided with exclusive offers. 
Risk Management:  Monitor customers with high purchases and low incomes to mitigate financial risk. 
