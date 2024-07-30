

**Machine-Learning-Tasks**

**1. Outlier Detection (House price.ipynb):**

Outlier detection is important in data analysis to identify and handle data points that are significantly different from the rest. Outliers can distort analyses, leading to biased results. Detecting and handling outliers ensures the integrity of data analysis.

**Methods to Detect Outliers:**

- **Mean Function:** Calculate the mean and standard deviation. Outliers are data points outside a certain range around the mean, typically more than 3 standard deviations away.
- **Percentile Method (IQR):** Calculate the first (Q1) and third (Q3) quartiles, and the interquartile range (IQR = Q3 - Q1). Outliers are points below Q1 - 1.5 * IQR or above Q3 + 1.5 * IQR.
- **IQR Method:** Similar to the percentile method, but used for skewed distributions.
- **Normal Distribution:** Calculate Z-scores, with data points having Z-scores greater than a predefined threshold (e.g., 3) considered outliers.
- **Z-score Method:** Similar to the normal distribution method but can be applied to any distribution.

**2. Hypothesis Testing:**

**Q1:** A child psychologist claims working mothers spend at least 11 minutes per day talking to their children. A sample of 1000 working mothers shows an average of 11.5 minutes with a population standard deviation of 2.3 minutes. Conduct a test at a 0.05 significance level.

**Q2:** A coffee shop claims their average wait time is less than 5 minutes. A sample of 40 customers shows a mean wait time of 4.6 minutes with a standard deviation of 0.8 minutes. Perform a hypothesis test at a 0.05 significance level to see if the claim is supported.

**3. Data Preprocessing:**

**Objective:** Design a robust data preprocessing system to handle missing values, outliers, inconsistent formatting, and noise to improve data quality for machine learning.

**Key Components:**

- **Data Exploration:** Explore data, list unique values, and perform statistical analysis. Rename columns.
- **Data Cleaning:** Find and treat missing and inappropriate values, remove duplicates, identify and handle outliers, and replace zeroes in age with NaN. Treat null values appropriately.
- **Data Analysis:** Filter data with age > 40 and salary < 5000, plot age vs. salary, and visually represent the count of people from each place.
- **Data Encoding:** Convert categorical variables into numerical representations using one-hot encoding or label encoding.
- **Feature Scaling:** Perform scaling of features using standard scaler and min-max scaler.

**5. Classification and Clustering:**

**The Iris Dataset:**

Contains 150 samples of iris flowers, each with four features: sepal length, sepal width, petal length, and petal width. The species are Iris setosa, Iris versicolor, and Iris virginica.

**Clustering Techniques:**

- **K-means Clustering:** Partitions data into K clusters by minimizing the variance within each cluster.
- **Agglomerative Clustering:** Builds clusters hierarchically using the Ward linkage method.
- **Hierarchical Clustering:** Produces a dendrogram.
- **Silhouette Coefficient:** Measures how similar a point is to its own cluster compared to other clusters. Higher values indicate better-defined clusters.

