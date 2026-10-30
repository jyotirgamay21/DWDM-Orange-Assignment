# Datasets - DWDM Tutorial Assignment 2 (Orange Data Mining)

| Folder | Experiment | Files |
|---|---|---|
| 01_data_cleaning | Data Cleaning | input with missing values + mean-imputed output |
| 02_data_reduction | Data Reduction | input + output with Student_ID removed |
| 03_data_transformation | Data Transformation | input + min-max normalised [0,1] output |
| 04_association_rules_apriori | Apriori | transactions.csv (Bread, Milk, Eggs, Butter) |
| 05_statistical_analysis | Statistical Analysis | cleaned student dataset |
| 06_regression | Regression | cleaned student dataset |
| 07_outlier_analysis | Outlier Analysis | cleaned student dataset |
| 08_kmeans_iris | K-Means on Iris | iris.csv |
| 09_clustering_iris_arff | Simple K-Means on iris.arff | iris.csv, iris.arff |

Notes:
- Student dataset values are re-created from the screenshots in the assignment PDF.
- Iris is the standard Fisher Iris dataset (150 rows).
- 04: only one transaction row is visible in the screenshot (all rules have support/confidence 1.0, 50 rules), so transactions.csv contains that row. Replace with your original file if it had more rows.
