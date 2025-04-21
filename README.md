✈️ Airline Passenger Clustering

🔍 Problem Statement

Global air travel has seen an upward trend in recent times. The maintenance of operational efficiency and maximizing profitability are crucial for airlines and airport authorities. This project aims to help businesses optimize airline and terminal operations by clustering airport passenger traffic data to enhance passenger satisfaction, improve turnover rates, and increase overall revenue.

📊 Approach

We utilized a structured data science pipeline to derive actionable insights:

Data cleaning and conversion of features like Month, Passenger Count, and Year

Feature engineering using:

Log transformation for skewed numerical data

Cyclic encoding of the month to handle seasonality

One-hot encoding for categorical variables like Operating Airline and Boarding Area

Hierarchical clustering using Ward linkage and Euclidean distance

Model evaluation using Silhouette Score (achieved: 0.62)

🔹 Key Features Engineered

month_sin and month_cos for cyclic month encoding

Log-scaled Passenger Count

Encoded categorical variables for improved clustering

🔺 Clustering Summary

The analysis identified three meaningful clusters:

Cluster 0: Moderate passenger count areas/airlines

Cluster 1: High passenger count areas with heavy traffic

Cluster 2: Low traffic terminals/airlines

Sample Insights

Airlines in Cluster 1 consistently serve higher volumes and may need additional resources.

Cluster 2 includes low-demand periods/terminals, which may benefit from optimization or marketing efforts.

👀 Visualizations

Dendrogram for cluster hierarchy interpretation

![image](https://github.com/user-attachments/assets/af2dc6f1-ba4d-4142-8e7d-2a1b12907ed5)

Boxplot of Passenger Count per cluster

![image](https://github.com/user-attachments/assets/75f57234-ee24-4ae3-b96c-07dfccd7236a)

🚀 Tools & Technologies

Python: pandas, numpy, matplotlib, seaborn, scikit-learn, scipy

Jupyter Notebook

🔗 How to Reproduce

Clone this repository

Install dependencies: pip install -r requirements.txt

Run notebooks/clustering_analysis.ipynb

👤 Author

Kamalnath Kuumaran
LinkedIn | GitHub


