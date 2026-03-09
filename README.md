# K-Means Clustering on Salary vs Experience

## Overview

In this project, I implemented the K-Means clustering algorithm to group employees based on their years of experience and salary. The idea is to see whether employees with similar experience levels fall into similar salary groups.

This project helped me understand how clustering works and how data points are grouped based on similarity.

## Dataset

The dataset contains two columns:

* **YearsExperience** – number of years an employee has worked
* **Salary** – salary of the employee

Example:

YearsExperience | Salary
1.1 | 39343
1.3 | 46205
1.5 | 37731
2.0 | 43525
2.2 | 39891

## Tools Used

* Python
* Pandas
* Matplotlib
* Scikit-learn

## Steps Performed

1. Loaded the dataset using pandas.
2. Selected YearsExperience and Salary as features.
3. Used the elbow method to determine the number of clusters.
4. Applied the K-Means clustering algorithm.
5. Visualized the clusters using a scatter plot.

## Output

The algorithm groups employees into clusters based on similar salary and experience patterns.
The visualization also shows the centroids of each cluster.

## What I Learned

* How K-Means clustering works
* What WCSS is and how it is used in the elbow method
* How clustering can help in identifying patterns in data

## Possible Improvements

* Use a larger dataset
* Apply feature scaling
* Compare results with other clustering algorithms
