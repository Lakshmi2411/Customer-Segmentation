# Customer-Segmentation

This dataset contains information about 200 customers with the following attributes:

- Gender: Male or Female
- Age: Between 18-70
- Annual Income: $15k to $137k 
- Spending Score: Between 1-99

## Dataset Overview

- Number of rows: 200
- Number of columns: 5
- Columns: CustomerID, Gender, Age, Annual Income, Spending Score
- No missing values

The CustomerID column was dropped as it contained no useful information. The data was cleaned and ready for analysis.

## Observations

- Balanced mix of 89 male and 111 female customers.
- Most customers are aged between 19-54.
- Annual income ranges from $15k to $137k, with most between $20k-$90k.
- Spending scores vary from 1-99, concentrated around 40-80.

This dataset provides a useful sample of customer demographic and financial attributes. It can be leveraged for customer segmentation analysis using clustering algorithms. The mix of age, income and spending attributes allows segmenting customers into distinct profiles.

## 
-Performed exploratory data analysis on customer dataset using Pandas, Matplotlib, and Seaborn to analyze features like age, gender, income, and spending score. 
-Created insightful plots to understand data distributions.
-Applied K-Means clustering algorithm (from scikit-learn) to group customers into distinct segments based on attributes like age, income, and spending habits.
-Determined the optimal number of clusters (k) using the elbow method by analyzing inertia vs number of clusters.
-Profiled and described the identified customer segments based on the clustering model to understand their key characteristics.
-Visualized the clustered data in a 3D scatter plot using Matplotlib to represent customer segments across age, income, and spending score features.
-Implemented end-to-end customer segmentation pipeline in Python from loading data, EDA, feature engineering, model building, and profiling.
-Followed CRISP-DM process by moving from a business understanding of the problem to data understanding, data prep, modeling, and evaluation.
-Demonstrated ability to apply unsupervised learning techniques like clustering to solve real-world problems using Python data science libraries.

